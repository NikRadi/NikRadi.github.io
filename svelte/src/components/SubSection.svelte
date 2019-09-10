<script>
</script>

<style type="text/scss">
    .subsection-wrapper {
        border-top: 2px solid #46bbb5;
        margin: 75px 0;
        padding: 0 50px;
    }
</style>

<div class="subsection-wrapper">
    <h2>
        <slot name="title">Title</slot>
    </h2>
    <slot name="content"/>
</div>