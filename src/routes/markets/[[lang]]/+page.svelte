<script>
    import {page} from '$app/stores';

    const greetingMapping = {
        eng: 'English -> Hello',
        es: 'Spanish - Hola',
        fr: 'French = Bonjour'
    }

    const {lang = 'eng'} = $page.params

    const greeting = greetingMapping[lang];
</script>

<h3>Language page : {greeting}</h3>