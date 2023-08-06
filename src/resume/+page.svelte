<script>
    import Header from "../routes/+page.svelte"
</script>

<Header/>

<div class="heading">
    <h1>Resume</h1>
</div>

<div class="wrapper">
    <p class="title">Education</p>

    <div class="box">
        <p class="sub-point">
            2014 - 2019
        </p>
        <div class="inner-box">
            Highschool diploma
        </div>
    </div>
    <div class="sub-point-box">
        <p class="sub-heading">
            PGASG "Architect Kamen Petkov"
        </p>
    </div>

    <div class="box">
        <p class="sub-point">
            2021 - Current
        </p>
        <div class="inner-box">
            Bachelor's degree
        </div>
    </div>
    <div class="sub-point-box">
        <p class="sub-heading">
            Paisii Hilendarski University of Plovdiv
        </p>
    </div>
</div>
<style>

    .wrapper {
        width: 50%;
        margin-left: 10%;
    }

    .title {
        font-size: 20px;
        display: flex;
        padding: 0;
        margin: 4% 0 0 10%;
    }

    .box{
        display: flex;
        margin-left: 10%;
    }

    .sub-point {
        border-radius: 60px;
        border: solid rgb(0, 124, 237);
        padding: 2px 5px;
    }

    .inner-box {
        display: flex;
        align-items: center;
        color: gray;
        padding-left: 10px;
    }

    .sub-point-box {
        display: flex;
        margin: 0 14%;
    }

    .sub-heading {
        padding: 0;
        margin: 0;
    }

    .heading {
        padding: 0.2%;
        border-bottom: solid #333333;
        border-top: solid #333333;
    }

    h1 {
        color: white;
        margin-left: 3%;
    }

    p {
        color: white;
    }

    div {
        color: white;
    }

</style>
