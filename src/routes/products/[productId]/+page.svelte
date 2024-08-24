<script>
    import { page } from "$app/stores";
    import {
        goto,
        replaceState,
        beforeNavigate,
        afterNavigate,
    } from "$app/navigation";

    const { productId } = $page.params;

    const goToHomePage = () => {
        goto("/", { replaceState: true });
    };

    beforeNavigate((navigation) => {
        console.log("before navigation ", navigation);
    });

    afterNavigate((navigation) => {
        console.log("after navigation ", navigation);
    });
</script>

<h1>Products detail of {productId}</h1>

<br />
<button on:click={goToHomePage}>Home page</button>
