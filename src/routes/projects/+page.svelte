<script>
    import Header from "../+page.svelte"
    import Heading from "../shared/Heading.svelte";
    import Footer from "../shared/Footer.svelte";
</script>
<div class="container">
    <Header/>
    <Heading content="Projects"/>
    <div class="wrapper">
        <div class="backend">
            <ul>
                <li>
                    <a href="https://github.com/st0ppers/ExpenseAPI">Expense API</a>
                    <p>- Simple CRUD Api that works with mongoDB to store my expenses for each month.</p>
                </li>
                <li>
                    <a href="https://github.com/st0ppers/DraftKingsAcademyProject">Academy project</a>
                    <p>- Academy project for DraftKings</p>
                </li>
            </ul>
        </div>
        <div class="frontend">
            <ul>
                <li>
                    <a href="https://github.com/st0ppers/ExpenseWithReact">Expense frontend</a>
                    <p>- The front end that visualizes the records in the DB.</p>
                </li>
            </ul>
        </div>
    </div>
    <Footer/>
</div>
<style>
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
        text-decoration: none;
        font-family: Roboto, monospace
    }

    p {
        color: white;
        display: flex;
        font-family: Roboto, monospace
    }

    .container {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
    }

    .wrapper {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    .backend {
        width: 50%;
        margin-left: 10%;
    }

    .frontend{
        width: 50%;
        margin-left: 10%;
    }
</style>