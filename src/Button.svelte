<script>
    export let text;
</script>

<svelte:options tag="arc-btn" />
<button on:click>{text}</button>

<style type="text/scss">
$color: hotpink;

button {
    background-color: $color;
}
</style>