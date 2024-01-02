<!-- Navigation Bar Component -->

<script>
    import RatingTag from "./RatingTag.svelte";
</script>

<div class="navbar">
    <img src="/Images/ChessIcon.svg" class="navbar-icon" alt="Chess Logo" />
    <span class="navbar-title">Chess</span>
    <span class="navbar-item">Home</span>
    <span class="navbar-item">Play</span>
    <span class="navbar-item">My Stats</span>
    <span class="navbar-item">Ranking</span>
    
    <div class="profile">
        <div class="profile-container">
            <span class="pic"></span>
            <span class="navbar-item">Martinez</span>
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
        font-size: 18.018px;
        font-weight: 400;
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
        padding-right: 20px;
        padding-top: 0;
    }

    .profile-container > .navbar-item {
        padding-right: 15px;
    }

    .profile-container {
        display: flex;
    }

    .pic {
        height: 32px;
        width: 32px;
        background-color: #BFBFBF;
        border-radius: 50%;
        margin-right: 10px;
        margin-top: 13px;
    }

    .dropdown {
        width: 12px;
        padding-top: 15px;
        padding-right: 10px;
    }
</style>