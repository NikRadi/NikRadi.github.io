<style type="text/scss">
    $navbar-height: 80px;

    nav {   
        background-color: #46bbb5;
        height: $navbar-height;
        display: flex;
        margin-bottom: 50px;

        .navbar-brand {
            color: #333;
            font-size: 28px;
            margin-left: 40px;
            margin-right: 40px;
        }

        .navbar-items {
            color: white;
            font-size: 24px;
            margin-left: 80px;
            margin-right: 80px;
        }

        .navbar-brand,
        .navbar-items {
            height: $navbar-height / 2;
            margin-top: $navbar-height / 4;
            margin-bottom: $navbar-height / 4;
            display: flex;
            align-items: center;
        }
    }
</style>

<nav>
    <div class="navbar-brand">
        <h1>
            <slot name="brand"></slot>
        </h1>
    </div>
    <div class="navbar-items">
        <slot></slot>
    </div>
</nav>