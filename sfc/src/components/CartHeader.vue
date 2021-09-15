<template>
    <h1>{{upperTitle}}</h1>
</template>

<script>
    export default{
        data: () =>{
            return{
                title:"vue cart"
            }
        },
        computed:{
            upperTitle:function(){
                return this.title.toUpperCase();
            }
        }
    }
</script>

<style>

</style>