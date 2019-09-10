<script>
    export let bgcol = "#ffffff";
    export let tcol = "#444444";
</script>

<style type="text/scss">
    .section-wrapper {
        padding: 25px;

        h1 {
            text-align: center;
        }

        .content {
            margin: 0 auto;
            max-width: 1100px;

            .text {
                margin: inherit;
                max-width: 800px;
            }
        }
    }
</style>

<div class="section-wrapper" style="background-color: {bgcol}; color: {tcol};">
    <h1>
        <slot name="title">No Title</slot>
    </h1>
    <div class="content">
        <div class="text">
            <slot name="text"/>
        </div>
        <slot name="content"/>
    </div>
</div>