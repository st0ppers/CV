<script lang="ts">
    import Mail from "svelte-material-icons/Email.svelte.js";
</script>
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

<style>
    .img {
        width: 50%;
        margin-left: 10%;
    }

    .picture {
        text-align: center;
    }

    .text-content {
        text-align: center;
        color: white;
        font-weight: bold;
        font-size: 1.5rem;
        font-family: Roboto, monospace
    }
</style>