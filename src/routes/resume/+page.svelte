<script>
    import Navigation from "../+page.svelte";
    import Heading from "../shared/Heading.svelte";
    import Education from './Components/Education.svelte'
    import Experience from "./Components/Experience.svelte";
    import SoftSkills from "./Components/SoftSkills.svelte";
    import ProgrammingSkills from "./Components/ProgrammingSkills.svelte";
</script>

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
</style>

