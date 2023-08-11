<script>
    import Header from "../+page.svelte"
</script>

<Header/>
<h1>My projects</h1>
<ul>
    <li>
        <a href="https://github.com/st0ppers/ExpenseAPI">Expense API</a>
        <p>Simple CRUD Api that works with mongoDB to store my expenses for each month.</p>
    </li>
    <li>
        <a href="https://github.com/st0ppers/ExpenseWithReact">Expense frontend</a>
        <p>The front end that visualizes the records in the DB.</p>
    </li>
    <li>
        <a href="https://github.com/st0ppers/DraftKingsAcademyProject">Academy project</a>
        <p>Academy project for DraftKings</p>
    </li>
</ul>

<style>
    h1 {
        color: white;
    }

    ul {
        color: white;
        list-style: none;
    }

    li {
        color: white;
        padding: 10px;
    }

    a {
        color: white;
    }

    p {
        color: white;
        display: flex;
    }
</style>