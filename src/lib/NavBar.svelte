<!-- Navigation Bar Component -->

<div class="navbar">
    <img src="/Images/ChessIcon.svg" class="navbar-icon" alt="Chess Logo" draggable="false" />
    <span class="navbar-title">Chess</span>
    <span class="navbar-item">Home</span>
    <span class="navbar-item">Play</span>
    <span class="navbar-item">My Stats</span>
    <span class="navbar-item">Ranking</span>
    
    <div class="profile">
        <div class="profile-container">
            <span class="pic"></span>
            <span class="username">Mechina-Hanich</span>
            <div class="rating">#78</div>
            <img class="dropdown" src="/Images/Dropdown.svg" alt="Dropdown"/>
        </div>
    </div>
</div>

<style>
    .navbar {
        background-color: #1D2022;
        display: flex;
    }

    .navbar > * {
        padding-top: .67rem;
        padding-bottom: .7rem;
    }

    .navbar-title {
        font-size: 1.5rem;
        font-weight: 500;
        padding-right: 2.4rem;
    }

    .navbar-item {
        padding-right: 1.7rem;
        padding-top: 1rem;
    }

    .navbar-icon {
        width: 1.5rem;
        height: 1.5rem;
        padding-right: .64rem;
        padding-left: 1.4rem;
    }

    .profile {
        margin-left: auto;
        padding-right: 1.7rem;
        padding-top: 0;
        padding-bottom: 0;
    }

    .profile-container {
        display: flex;
        align-items: center;
        justify-content: center;
        padding-top: .7rem;
        gap: .3rem;
    }

    .pic {
        height: 1.8rem;
        width: 1.8rem;
        background-color: #BFBFBF;
        border-radius: 50%;
    }

    .dropdown {
        width: .7rem;
    }

    .username {
        font-size: .9rem;
        padding-left: .1rem;
    }

    .rating {
        background-color: #37548B;
        padding-right: .3rem;
        padding-left: .3rem;
        padding-top: 1px;
        padding-bottom: 1px;
        border-radius: .5rem;
        margin-right: .55rem;
        font-size: .8rem;
        font-weight: 350;
    }
</style>
