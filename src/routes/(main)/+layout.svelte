<header class="layout-header">
    Header
</header>

<div class="main-container">
    <slot />
</div>

<footer class="layout-footer">
    Footer
</footer>


<style>
    .layout-header{
        background-color: red;
        color: white;
        padding: 20px;
    }

    .layout-footer{
        background-color: purple;
        color: white;
        padding: 20px;
    }

    .main-container{
        height: 20vh;
    }
</style>