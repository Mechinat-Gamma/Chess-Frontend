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
        padding-top: 1.95rem;
        padding-right: 6.7rem;
        padding-left: 6.7rem;
    }

    .title-flex {
        display: flex;
        flex-direction: column;
        gap: 1.8rem;
        align-items: baseline;
    }

    .title {
        font-size: 5.85rem;
        font-weight: 700;
        line-height: 100%;
        word-spacing: 100rem;
        margin-top: 2rem;
    }

    .play-button {
        background-color: #37548B;
        font-size: 1.5rem;
        font-weight: 500;
        border-radius: 100rem;
        padding-left: 1.4rem;
        padding-right: 1.4rem;
        padding-top: .45rem;
        padding-bottom: .45rem;
    }
</style>
