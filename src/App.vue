<template>
    <div>
        <app-header></app-header>
        
        <div class="container">
            <div> {{ name }} </div>
        </div>
        
        <comp-footer></comp-footer>
    </div>
</template>

<script>
    import compFooter from './Components/Header_footer/Footer.vue';

    export default {
        data(){
            return {
                name: "Francis"
            }
        },
        components:{
            compFooter
        }
    }
</script>


<style>
    body {
        padding:0;
        margin:0;
        font-family: 'Roboto', sans-serif;
    }

    .container {
        min-height: 84vh;
        box-sizing: border-box;
        padding: 20px;
    }
</style>