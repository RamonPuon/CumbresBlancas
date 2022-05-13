<template>
   
    <section class="proyect_container">
        <div class="proyect_left">
            Monitoreo de Glaciares
            <i class="uil uil-angle-down"></i>
        </div>
        <div class="proyect_right">
            <div class="proyect_upperright">
                Educación
                <i class="uil uil-angle-down"></i>
            </div>
            <div class="proyect_bottomright">
                Cumbres Blancas & Limpias
                <i class="uil uil-angle-down"></i>
            </div>
        </div>
    </section>

</template>

<script>
export default {
    name: "ProyectPage",
    data() {
        return {
            image: "@/assets/placeholder_2.jpg"
        };
    },
}
</script>

<style>
    .proyect_container{
        display: flex;
        justify-content: first baseline;
    }

    .proyect_left{
        width: 50%;
        height: 500px;
        background-image: url("../assets/Glaciares.jpeg");
        background-size: cover;
    }

    .proyect_right{
        display: flex;
        flex-direction: column;
        width: 50%;
    }

    .proyect_upperright{
        width: 100%;
        height: 250px;
        background-image: url("../assets/placeholder.jpg");
        background-size: cover;
    }

    .proyect_bottomright{
        width: 100%;
        height: 250px;
        background-image: url("../assets/CumbresBlancas_limbias.png");
        background-size: cover;
    }

    .uil-angle-down{
        font-size: 1.5rem;
    }
</style>