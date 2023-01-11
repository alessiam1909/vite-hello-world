<script>

export default{
    name: "AppTitle",
    data(){
        return{
            title : "La mia prima app con Vite!"
        }
    }
}
</script>


<template lang="">
    <div class="title">
        <h1>
            {{title}}
        </h1>
    </div>
</template>


<style>

    .title{
        background-color: rgb(175, 137, 211);
        padding: 20px;
        border-radius: 20px;
        border: 1px solid black;
        box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, .2);
    }
    h1{
        color: rgb(123, 219, 219);
        text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
    }

</style>