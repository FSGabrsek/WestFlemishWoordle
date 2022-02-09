<script>
    export let path

    export let onClick;
</script>

<button on:click="{onClick}">
    <svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 0 24 24" width="24">
        <path fill="var(--color-tone-3)" d={path} />
    </svg>
</button>

<style>
    button {
        border: none;
        background: none;

        cursor: pointer;
    }

    svg {
        padding-inline: 4px;
    }

    *:not(svg),
    *:not(foreignObject) > svg {
        transform-origin: 0 0;
    }
</style>