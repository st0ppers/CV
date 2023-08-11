<script lang="ts">
    import {base} from "$app/paths";
</script>
<div class="wrapper">
    <a href="{base}/resume">Resume</a>
    <a href="{base}/home">About me</a>
    <a href="{base}/contact">Contact</a>
</div>

<style>
    .wrapper{
        display: flex;
        justify-content: end;
        padding: 20px;
    }
    a{
        text-decoration: none;
        padding-left: 20px;
        color: white;
    }
</style>