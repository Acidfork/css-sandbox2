
<header>
    My really cool header
</header>
<main>
    <div class="tooltip">Tooltip 🥲</div>
    <p>This is some juicy content.</p>
</main>

<style>
    header {
        position: relative;
        z-index: 2;
        background-color: deeppink;
        padding-block: 32px;
        font-size: 32px;
        text-align: center;
    }

    main {
        z-index: 1;
        position: relative;
        padding: 32px;
    }

    .tooltip {
        position: absolute;
        z-index: 999999999;
        background-color: white;
        top: -20px;
        inset-inline: 0;
        margin: 0 auto;
        width: fit-content;
        font-size: 20px;
        padding-inline: 14px;
        padding-block: 6px;
        border-radius: 8px;
        box-shadow: 0px 6px 26px -12px rgba(0,0,0,0.75);
    }
</style>