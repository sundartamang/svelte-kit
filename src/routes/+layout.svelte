<header class="layout-header">Hader</header>

<div class="main-container">
    <slot />
</div>

<footer class="layout-footer">Footer</footer>

<style>
    .layout-header {
        padding: 10px;
        background-color: red;
        font-size: 18px;
        color: white;
    }

    .layout-footer {
        padding: 10px;
        background-color: purple;
        font-size: 18px;
        color: white;
    }

    .main-container {
        height: 30vh;
    }
</style>
