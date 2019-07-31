<script>
    export let id;
</script>

<style type="text/scss">
    .section-wrapper {
        margin: 100px 0px 100px 150px;

        h1 {
            margin-left: 40px;
        }
    }
</style>

<div class="section-wrapper">
    <h1 id={id}>
        <slot name="title"></slot>
    </h1>
    <slot name="content"></slot>
</div>