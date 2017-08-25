<template>
    <div class="flex" id="content1">
        <header class="header">更多</header>
        <div id="content">内容
             <!-- <img  v-lazy.content1="url">  -->
        </div>
        
        
    </div>
</template>


<script>
import Vue from "vue"
// import { Lazyload } from 'mint-ui';
// Vue.use(Lazyload);
// Vue.component(Popup.name, Popup);
    export default {
        data(){
            return {
               url:"http://fuss10.elemecdn.com/7/85/e478e4b26af74f4539c79f31fde80jpeg.jpeg"
            }
        }
    }
</script>

<style scoped>
    image[lazy=loading] {
        width: 40px;
        height: 300px;
        margin: auto;
        }
</style>
