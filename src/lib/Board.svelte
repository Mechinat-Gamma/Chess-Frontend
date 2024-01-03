<!-- Chess Board Component -->

<div class="chess-board">
    <div class="row">
        <div><img class="pawn" src="/Images/Pawns/BlackTower.svg" alt="Black Tower" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackHorse.svg" alt="Black Horse" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackRook.svg" alt="Black Rook" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackQueen.svg" alt="Black Queen" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackKing.svg" alt="Black King" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackRook.svg" alt="Black Rook" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackHorse.svg" alt="Black Horse" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackTower.svg" alt="Black Tower" /></div>
    </div>
    <div class="row">
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/BlackPawn.svg" alt="Black Pawn" /></div>
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
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhitePawn.svg" alt="White Pawn" /></div>
    </div>
    <div class="row">
        <div><img class="pawn" src="/Images/Pawns/WhiteTower.svg" alt="White Tower" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteHorse.svg" alt="White Horse" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteRook.svg" alt="White Rook" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteQueen.svg" alt="White Queen" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteKing.svg" alt="White King" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteRook.svg" alt="White Rook" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteHorse.svg" alt="White Horse" /></div>
        <div><img class="pawn" src="/Images/Pawns/WhiteTower.svg" alt="White Tower" /></div>
    </div>
</div>

<style>
    .chess-board {
        --square-width: 3.6rem;
        position: relative;
        display: flex;
        flex-direction: column;
        background-color: white;
        outline: .5rem solid white;
        border: 1px solid #B3B2B4;
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
