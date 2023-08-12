<script lang="ts">
    import Instagram from "svelte-material-icons/Instagram.svelte";
    import GitHub from "svelte-material-icons/Github.svelte";
    import LinkedIn from "svelte-material-icons/Linkedin.svelte";
    import IconButton from '@smui/icon-button';
</script>
<div class="wrapper">
    <div>
        <IconButton class="button" href="https://www.instagram.com/stoppers44/" target="_blank">
            <Instagram class="gap" color="white" size="2rem"/>
        </IconButton>
    </div>
    <div>
        <IconButton class="button" href="https://github.com/st0ppers" target="_blank">
            <GitHub color="white" size="2rem"/>
        </IconButton>
    </div>
    <div>
        <IconButton class="button" href="https://www.linkedin.com/in/alexsander-damov-8a634a237/" target="_blank">
            <LinkedIn color="white" size="2rem"/>
        </IconButton>
    </div>
</div>

<style>
    .wrapper {
        display: flex;
        justify-content: center;
        margin-top: auto;
        padding: 0 5rem;
        gap: 5rem;
    }

    .button {
        background-color: #222222;
        color: inherit;
        border: none;
        padding: 0;
        font: inherit;
        cursor: pointer;
        outline: inherit;
    }
</style>