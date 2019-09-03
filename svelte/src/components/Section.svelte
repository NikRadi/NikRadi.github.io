<script>
    import { getNumberOfSections } from "stores/sections";

    let classes = "";
    classes += (getNumberOfSections() % 2 === 0) ? "colored" : "";
    classes += " ";
</script>

<style type="text/scss">
    .section-wrapper {
        padding: 25px;

        h1 {
            text-align: center;
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
    <slot name="content"/>
</div>