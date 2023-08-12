<script lang="ts">
    import Navigation from "../+page.svelte";
    import Heading from "../shared/Heading.svelte";
    import Footer from "../shared/Footer.svelte";
    import Cellphone from "svelte-material-icons/Cellphone.svelte";
    import Mail from "svelte-material-icons/Email.svelte";
</script>
<div class="container">
    <Navigation/>
    <Heading content="Contact"/>
    <div class="wrapper">
        <div class="img">
            <div class="picture">
                <Cellphone color="white" size="5rem"/>
            </div>
            <div class="text-content">
                <p>Call me</p>
            </div>
            <div class="text-content">
                <p>089-241-0428</p>
            </div>
        </div>
        <div class="img">
            <div class="picture">
                <Mail color="white" size="5rem"/>
            </div>
            <div class="text-content">
                <p>Email me</p>
            </div>
            <div class="text-content">
                <p>alexsander.damov@yahoo.com</p>
            </div>
        </div>
    </div>
    <Footer/>
</div>

<style>

    .wrapper {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        height: 69%;
        margin-top: 5%;
    }

    .img {
        width: 50%;
    }

    .picture {
        text-align: center;
    }

    .text-content {
        text-align: center;
        color: white;
        font-size: 1.5rem;
        font-family: Roboto, monospace
    }

    .container {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
        overflow: hidden;
    }

</style>