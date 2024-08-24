<script>
    import { page } from "$app/stores";
    import { goto } from "$app/navigation";

    const { productId } = $page.params;

    const goToHomePage = () => {
        goto("/");
    };
</script>

<h1>Products detail of {productId}</h1>

<br />
<button on:click={goToHomePage}>Home page</button>
