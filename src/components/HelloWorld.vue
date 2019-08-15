<template>
<Gallery :images="images" ></Gallery>
</template>

<script>
import Gallery from "vue-cover-gallery"
export default {
  name: 'HelloWorld',
  data() {
    return { 
      images: [ 
         {
            title: "Moon hill bridge",
            href: "https://image.redbull.com/rbcom/010/2015-07-27/1331737542701_2/0010/1/1500/1000/1/moon-hill-natural-bridge-in-china.jpg"},
            
            {
            title: "The sunset",
            href: "http://cphpost.dk/wp-content/uploads/2019/05/forest-1950402__340.jpg"
            },
                {
            title: "Blissful night in the dessert",
            href: "https://mysticjaisalmer.com/wp-content/uploads/2018/01/blissful-night-in-the-desert-of-thar-1024x798.jpg"},
            {
             title: "The sunset",
            href: "https://www.digitalcare.org/wp-content/uploads/2016/11/Free-Desktop-Wallpaper-feature.jpg"
            },
                {
            title: "Ocean view from sky",
            description: "",
            href: "https://croatia.hr/sites/default/files/2017-08/00_nature_0.jpg"},
            {
             title: "Ocean view",
            href: "http://neulabs-wpengine.netdna-ssl.com/wp-content/uploads/2014/01/nature-05-700x1050.jpg"
            },
                 {
            title: "Beautiful mountain",
            href: "http://ghettojuice.wdfiles.com/local--files/file:clark-little/clark-little.jpg"},
     ],
    }
  },
  props: {
    msg: String
  },components:{
    Gallery
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >

</style>
