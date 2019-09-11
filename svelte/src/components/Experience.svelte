<script>

</script>

<style type="text/scss">
    .experience-wrapper {
        margin: 25px 0;
        display: flex;

        .info {
            min-width: 300px;
            max-width: 300px;
            margin-right: 10px;

            .location {
                font-weight: bold;
            }
        }

        .location,
        .title,
        .time {
            margin-bottom: 10px;
        }
    }
</style>

<div class="experience-wrapper">
    <div class="info">
        <div class="location">
            <slot name="location">Title</slot>
        </div>
        <div class="title">
            <slot name="title">Name</slot>
        </div>
        <div class="time">
            <slot name="time">xxxx - xxxx</slot>
        </div>
    </div>
    <div class="description">
        <slot name="description">Description</slot>
    </div>
</div>