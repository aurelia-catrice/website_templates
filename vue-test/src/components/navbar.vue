<template>

    <div class="top">
        <div class="bar">
            <a href="#home" class="bar-left bar-item">Gourmet au Catering</a>
            <div class="bar-right">
                <a href="#about" class="bar-item">About</a>
                <a href="#menu" class="bar-item">Menu</a>
                <a href="#contact" class="bar-item">Contact</a>
            </div>
        </div>
    </div>

</template>

<style>

    .top {
        overflow: hidden;
        position: fixed;
        z-index: 1;
        background-color: #FFFF;

        display: block;
        top: 0;
        width: 100%;
        height: 50px;
        box-shadow: 0 2px 10px 0 rgb(0 0 0 / 12%);
    }
    .bar .bar-item {
        padding: 12px 12px;
        float: left;
        width: auto;
        outline: 0;
    }
    .bar-right {
        float: right;
    }
    .bar > a, .bar-right > a {
        font-family: "Playfair Display";
        letter-spacing: 4px;
        color: #000;
        text-decoration: none;
    }
    .bar > a:hover, .bar-right > a:hover {
        color: #8c8c8c;
        transition: 0.5s;
    }

</style>