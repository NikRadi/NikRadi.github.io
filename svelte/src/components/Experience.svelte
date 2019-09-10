<script>

</script>

<style type="text/scss">
    .experience-wrapper {
        margin: 25px 0;
    }
</style>

<div class="experience-wrapper">
    <div class="experience-location">
        <slot name="location">Title</slot>
    </div>
    <div class="experience-time">
        <slot name="time">xxxx - xxxx</slot>
    </div>
    <div class="experience-title">
        <slot name="title">Name</slot>
    </div>
    <div class="experience-description">
        <slot name="description">Description</slot>
    </div>
</div>