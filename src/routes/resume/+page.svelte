<script lang="ts">
    import Navigation from "../+page.svelte";
    import Heading from "../shared/Heading.svelte";
    import Education from './Components/Education.svelte'
    import Experience from "./Components/Experience.svelte";
    import SoftSkills from "./Components/SoftSkills.svelte";
    import ProgrammingSkills from "./Components/ProgrammingSkills.svelte";
    import Footer from "../shared/Footer.svelte";
</script>
<div class="container">
    <Navigation/>
    <Heading content="Resume"/>

    <div class="row">
        <Education/>
        <Experience/>
    </div>

    <div class="row">
        <SoftSkills/>
        <ProgrammingSkills/>
    </div>
    <Footer/>
</div>
<style>
    .row {
        display: flex;
        flex-direction: row;
        margin-top: 30px;
    }

    div {
        color: white;
        font-family: Roboto, monospace
    }

    .container {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
    }
</style>