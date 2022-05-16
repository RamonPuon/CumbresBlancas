<template>
    <section class="proyect_container">
       <div class="proyect1">
           <h2 class="proyects_title">Conoce Nuestros Proyectos</h2>
       </div>
    </section>

</template>

<script>
export default {
    name: "ProyectPage",
    data() {
        return {
            images:[{image: "../assets/conejo.jpeg"}, {image: "../assets/Citlaltepetl.jpeg"}]
        };
    },
}
</script>

<style>
    .proyect_container{
        display: flex;
        justify-content: first baseline;
    }

    .proyect1 {
        background-image: url('../assets/proyect1.jpeg');
         width: 100%;
        height: 800px;
        background-size: cover;
        background-position-y: -40px;
        background-repeat: no-repeat;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .proyects_title{
        color: white;
        position: absolute;
        left: 35rem;
        bottom: 13rem;
        font-size: 3rem;
    }

    
</style>