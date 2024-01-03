<script>
    import Board from "$lib/Board.svelte";
</script>

<div class="hero-flex">
    <div class="title-flex">
        <p class="title">Find Your Next Game.</p>
        <div class="play-button">Play Now</div>
    </div>
    <Board />
</div>

<style>
    .hero-flex {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 35px 120px;
    }

    .title-flex {
        display: flex;
        flex-direction: column;
        gap: 65px;
        align-items: baseline;
    }

    .title {
        font-size: 105px;
        font-weight: 700;
        line-height: 100%;
        word-spacing: 9999px;
        margin-top: 50px;
    }

    .play-button {
        background-color: #37548B;
        font-size: 27.723px;
        font-weight: 500;
        border-radius: 42.43px;
        padding-left: 25px;
        padding-right: 25px;
        padding-top: 8px;
        padding-bottom: 8px;
    }
</style>
