<script>
</script>

<style type="text/scss">
    .subsection-wrapper {
        border-top: 2px solid #46bbb5;
        margin: 75px;
    }
</style>

<div class="subsection-wrapper">
    <h2>
        <slot name="title">No Title</slot>
    </h2>
    <slot name="content"/>
</div>