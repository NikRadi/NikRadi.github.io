<script>
    export let rating = 0;
</script>

<style type="text/scss">
    $circle-size: 20px;

    .rating-wrapper {
        height: 50px;
        display: flex;

        .title {
            width: 100px;
            font-size: 15px;
            font-weight: 600;
        }

        .rating {
            margin: auto 0;
        }
    }

    .circle {
        height: $circle-size;
        width: $circle-size;
        background-color: #bbbbbb;
        border-radius: 50%;
        display: inline-block;
    }

    .filled {
        background-color: #46bbb5;
    }
</style>

<div class="rating-wrapper">
    <div class="title">
        <p>
            <slot>Rating</slot>
        </p>
    </div>
    <div class="rating">
        <span class="circle {(rating > 0) ? "filled" : ""}"/>
        <span class="circle {(rating > 1) ? "filled" : ""}"/>
        <span class="circle {(rating > 2) ? "filled" : ""}"/>
        <span class="circle {(rating > 3) ? "filled" : ""}"/>
        <span class="circle {(rating > 4) ? "filled" : ""}"/>
    </div>
</div>