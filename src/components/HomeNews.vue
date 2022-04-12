<template>
   <section class="home_news">
       <h2>Noticias</h2>
       <div class="news">
           <div class="new">
               <img src="https://images.pexels.com/photos/691668/pexels-photo-691668.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260" alt="mountain">
               <p>
               Lorem Ipsum es simplemente el texto de relleno de las imprentas y
                archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de
                las industrias desde el año 1500, cuando un impresor (N. del T. persona
                que se dedica a la imprenta) desconocido usó una galería de textos.
                </p>
           </div>
           <div class="new">
               <img src="https://images.pexels.com/photos/691668/pexels-photo-691668.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260" alt="mountain">
               <p>
               Lorem Ipsum es simplemente el texto de relleno de las imprentas y
                archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de
                las industrias desde el año 1500, cuando un impresor (N. del T. persona
                que se dedica a la imprenta) desconocido usó una galería de textos.
                </p>
           </div>
           <div class="new">
               <img src="https://images.pexels.com/photos/691668/pexels-photo-691668.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260" alt="mountain">
               <p>
               Lorem Ipsum es simplemente el texto de relleno de las imprentas y
                archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de
                las industrias desde el año 1500, cuando un impresor (N. del T. persona
                que se dedica a la imprenta) desconocido usó una galería de textos.
                </p>
           </div>
       </div>
   </section>
</template>

<script>
export default {
    name: "HomeNews"
}
</script>

<style>
    .home_news{
        width: 100%;
        height: 650px;
        background-image: url("../assets/Se\ extinguen\ los\ glaciares.jpeg");
        background-size: cover;
        background-position-y: -100px;
        background-repeat: no-repeat;
        
    }
    .home_news h2{
        font-size: 3rem;
    }

    .news{
        padding: 0px;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }

    .new{
        width: 240px;
        height: 450px;
        border: 0.8px solid blue;
    }
    .new img{
        width: 100%;
    }
</style>