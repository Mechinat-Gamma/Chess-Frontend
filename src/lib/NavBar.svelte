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
        padding-top: 12px;
        padding-bottom: 12.75px;
    }

    .navbar-title {
        font-size: 26.849px;
        font-weight: 500;
        padding-right: 42.71px;
    }

    .navbar-item {
        padding-right: 29.62px;
        padding-top: 18px;
    }

    .navbar-icon {
        width: 27.468px;
        height: 27.799px;
        padding-right: 11.45px;
        padding-left: 25.02px;
    }

    .profile {
        margin-left: auto;
        padding-right: 30px;
        padding-top: 0;
        padding-bottom: 0;
    }

    .profile-container {
        display: flex;
        align-items: center;
        justify-content: center;
        padding-top: 13px;
        gap: 6px;
    }

    .pic {
        height: 32px;
        width: 32px;
        background-color: #BFBFBF;
        border-radius: 50%;
    }

    .dropdown {
        width: 12px;
    }

    .username {
        font-size: 16px;
        padding-left: 2px;
    }

    .rating {
        background-color: #37548B;
        padding-right: 6px;
        padding-left: 6px;
        padding-top: 1px;
        padding-bottom: 1px;
        border-radius: 9.307px;
        margin-right: 10px;
        font-size: 14px;
        font-weight: 350;
    }
</style>
