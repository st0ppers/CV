<script lang="ts">
    export let content: string;
</script>

<div class="heading">
    <h1>{content}</h1>
</div>

<style>
    .heading {
        padding: 0.2%;
        border-bottom: solid #333333;
        border-top: solid #333333;
    }

    h1 {
        color: white;
        margin-left: 3%;
        font-family: Roboto, monospace
    }
</style>
