<script>
    export let rating;
</script>

<style type="text/scss">
    .circle {
        height: 25px;
        width: 25px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
    }

    .filled {
        background-color: black;
    }
</style>

<span class="circle {(rating > 0) ? "filled" : ""}"/>
<span class="circle {(rating > 1) ? "filled" : ""}"/>
<span class="circle {(rating > 2) ? "filled" : ""}"/>
<span class="circle {(rating > 3) ? "filled" : ""}"/>
<span class="circle {(rating > 4) ? "filled" : ""}"/>