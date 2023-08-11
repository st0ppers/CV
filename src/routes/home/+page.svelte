<script>
    import Header from "../+page.svelte";
    import {base} from "$app/paths";
</script>

<Header/>
<div class="wrapper">
    <img alt="smily"
         src="https://play-lh.googleusercontent.com/IeNJWoKYx1waOhfWF6TiuSiWBLfqLb18lmZYXSgsH1fvb8v1IYiZr5aYWe0Gxu-pVZX3=w240-h480-rw">
    <div>
        <p>Hello,</p>
        <p>I am <b>Alexander Damov</b>, junior full stack developer currently working in DraftKings</p>
        <p>Also I am pursuing a bachelors degree in Software technology.</p>
        <a href="{base}/projects">My projects</a>
    </div>
</div>

<style>
    .wrapper {
        display: flex;
        align-items: center;
        justify-content: center;
        justify-items: center;
        flex-wrap: wrap;
        width: 100vh;
        margin: auto;
        height: 100vh;
        overflow: hidden;
        background-color: #222222;
    }

    img {
        width: 20%;
        height: 20%;
        padding: 30px;
        border-radius: 50%;
    }

    p {
        font-size: 20px;
        color: white;
        font-family: Roboto, monospace
    }

    a {
        display: flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        color: white;
        width: 100%;
        font-size: 20px;
        font-family: Roboto, monospace
    }
</style>
