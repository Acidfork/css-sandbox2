<script>
    import '../styles.css'
</script>

<div class="container">

    <!-- <div class="box item-1">A</div>
    <div class="box item-2">B</div> -->
    <!-- <div class="modal-backdrop" /> -->
    <!-- <div class="modal">
        <div class="box item-3"></div>
    </div> -->
    
    <div class="content-wrapper">
        <div class="big-box">
            <div class="circle" />
        </div>
        <div class="content">

        </div>
    </div>
        <div class="content-wrapper">
        <div class="big-box">
            <div class="circle" />
        </div>
        <div class="content">

        </div>
    </div>
        <div class="content-wrapper">
        <div class="big-box">
            <div class="circle" />
        </div>
        <div class="content">

        </div>
    </div>
    <!-- </div>
        <div class="big-box">
        <div class="circle" />
    </div>
        <div class="big-box">
        <div class="circle" />
    </div> -->
</div>

<style>

    .content-wrapper {
        border: 4px solid black;
        display: flex;
        height: 700px;
        margin-block-end: 100px;
    }

    .content {
        height: 100%;
        border: 4px solid black;
        background-color: red;
        flex: 1;
    }

    .container {
        height: 200%;
    }
    .big-box {
        height: 100%;
        width: 300px;
        border: 4px solid black;
        /* position: relative */
    }

    .circle {
        height: 100px;
        width: 100px;
        border-radius: 50%;
        background-color: cadetblue;
        border: 2px solid black;
        position: sticky;
        top: 0px;
    }

    .box {
        height: 100px;
        width: 100px;
        display: grid;
        place-content: center;
        font-size: 4rem;
        border: 4px solid black;
        position: relative;
    }
    
    .item-1 {
        background-color: gray;
        /* z-index:1; */
    }
    .item-2 {
        background-color: deeppink;
        margin-inline-start: 20px;
        margin-block-start: -40px;
    }

    .item-3 {
        position: absolute;
        top: 200px;
        left: 500px;
        background-color: cadetblue;
    }

    .modal-backdrop {
        position: fixed;
        height: 100%;
        inset:0;
        background-color: hsl(0deg 0% 0% / .5);
    }

    .modal {
        position: relative;
        width: 300px;
        height: 200px;
        background-color: white;
        inset: 0;
        margin: auto;
        overflow: auto;
    }



</style>