<template>
   <section class="home_second">
        <div class="head_second">
            <h2>LOS GLACIARES<br> EN MÉXICO</h2>
            <p>
                Lorem Ipsum es simplemente el texto de relleno de las imprentas y<br>
                archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de<br>
                las industrias desde el año 1500, cuando un impresor (N. del T. persona<br>
                que se dedica a la imprenta) desconocido usó una galería de textos.
            </p>
        </div>
        <div class="second_images">
            <div class="left_image"></div>
            <div class="right_image"></div>
        </div>
    </section>
</template>

<script>
export default {
    name: "HomeSecond"
}
</script>

<style>
    
.head_second{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.head_second h2{
    font-size: 2.2rem;
}

.head_second p{
    font-size: 1rem;
}

.second_images{
    display: flex;
}

.left_image{
    background-image: url("../assets/Citlaltepetl.jpeg");
    width: 33%;
    height: 500px;
    background-position-y: -100px;
    background-repeat: no-repeat;
    background-size: cover;
}

.right_image{
    background-image: url("../assets/iztaccihuatl.png");
    width: 67%;
    height: 500px;
    background-position-y: -100px;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>