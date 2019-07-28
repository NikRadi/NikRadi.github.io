<script>
    export let href;
</script>

<style type="text/scss">
    a {
        color: #ff8000;
        font-weight: bold;

        &:hover {
            color: #ce6700;
        }
    }
</style>

<a href={href}>
    <slot></slot>
</a>