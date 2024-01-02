<script>
    import Board from "$lib/Board.svelte";
</script>

<div class="hero-flex">
    <div class="title-flex">
        <p class="title">Find Your Next Game.</p>
    </div>
    <Board />
</div>

<style>
    .hero-flex {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 50px 120px;
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
</style>
