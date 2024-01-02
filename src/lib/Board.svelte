<!-- Chess Board Component -->

<div class="chess-board">
    <div class="row">
        <div></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteQueen.svg" alt="White Queen" /></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
    <div class="row">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
</div>

<style>
    .chess-board {
        --square-width: 3.8rem;
        position: relative;
        display: flex;
        flex-direction: column;
        background-color: white;
        border: .5rem solid white;
        border-radius: .5rem;
    }

    .chess-board > .row {
        display: flex;
    }

    .row > * {
        display: flex;
        justify-content: center;
        align-items: center;
        width: calc(var(--square-width));
        padding: 2px;
        aspect-ratio: 1/1;
    }

    .row:nth-child(2n) > *:nth-child(2n-1) {
        background-color: #48454A;
    }

    .row:nth-child(2n-1) > *:nth-child(2n) {
        background-color: #48454A;
    }

    .pawn {
        width: var(--square-width);
        aspect-ratio: 2/1.5;
    }
</style>
