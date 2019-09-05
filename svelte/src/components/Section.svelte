<script>
    export let colored = false;

    let classes = "";
    classes += (colored) ? "colored" : "";
    classes += " ";
</script>

<style type="text/scss">
    .section-wrapper {
        padding: 25px;

        h1 {
            text-align: center;
        }

        .content {
            margin: 0 250px;

            .text {
                padding: 0 200px;
            }
        }
    }

    .colored {
        background-color: #faf8e8;
    }
</style>

<div class="section-wrapper {classes}">
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