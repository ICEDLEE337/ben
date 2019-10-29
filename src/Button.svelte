<script>
    export let text;
    export let theme;
</script>

<svelte:options tag="arc-btn" />
<button on:click>{text}</button>

<style type="text/scss">
$color: lightgreen;

button {
    font-weight: bold;
    background-color: $color;
}
</style>