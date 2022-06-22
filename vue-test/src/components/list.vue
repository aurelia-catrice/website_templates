<template>  
    <div class="container container-margin-top container-margin-side" id="projects">
        <h2>Assortments</h2>
        <template v-for="(item, index) in list">
        <div v-if="index % 3 == 0" class="row-padding">
            <div class="col-padding">
                <div class="container-in-topleft container-back-white">
                    <h4>{{ item.title }}</h4>
                </div>
                <img v-bind:src="item.image" alt="waffle">
            </div>
        </div>
        </template>
    </div>
</template>

<script>
export default {
  data() {
    return {
        list: [{title:"Scrambled eggs", image:"/scrambledeggs.png"}, {title:"Blueberry Pancakes", image:"/bluberriespancakes.jpg"}, {title:"Honey Almond Granola", image:"/granola.webp"}, {title:"Garlic Bread", image:"/granola.webp"}, {title:"English Scones", image:"/granola.webp"}, {title:"Belgian wafle", image:"/granola.webp"}]
    }
  }
}
</script>

<style>
.container-in-topleft {
  width: 90%;
  margin-bottom: 1%;
}
.row-padding {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
}
.col-padding {
    float: left;
    margin: 1%;
    padding: 0;
    width: 400px;
    height: auto;
    flex: 2 0 21%;
}
.col-padding > img {
    width: 400px;
    height: 280px;
}

.container-back-white {
    background-color: #FFFF;
}

</style>