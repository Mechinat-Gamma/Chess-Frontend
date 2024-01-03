<script>
    import NavBar from "$lib/NavBar.svelte";
</script>

<NavBar />
<slot />

<style>
    :global(*) {
        margin: 0;
        padding: 0;
    }

    :root {
        font-family: Inter, sans-serif;
        font-feature-settings: 'liga' 1, 'calt' 1; /* Chrome-specific bug; Inter font */
        background-color: #2B292E;
        color: white;
        user-select: none;
        font-size: 18.018px;
        font-weight: 400;
    }

    @supports (font-variation-settings: normal) {
        :root { font-family: InterVariable, sans-serif; }
    }
</style>