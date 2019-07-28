<script>
    export let href;
</script>

<style type="text/scss">
    a {
        margin-left: 20px;
        margin-right: 20px;
    }
</style>

<a href={href}>
    <slot></slot>
</a>