<template>
    <section class="home_first">
        <div class="donation_button">
            <span>¡Dona ahora!</span>
        </div>    
        <div class="first_text">
            <p>SE EXTINGUEN<br> LOS GLACIARES<br> EN MÉXICO</p>
            <div class="first_sub">
                <div class="first_sub_sub">
                    <h1>7</h1>
                    <p>SE HAN EXTINGUIDO</p>
                </div>
                <div class="first_sub_sub">
                    <h1>3</h1>
                    <p>SE EXTINGUEN</p>
                </div>
                <div class="first_sub_sub">
                    <h1>15</h1>
                    <p>AÑOS LES QUEDA</p>
                </div>
            </div>
        </div>
        <div class="first_logos">
            <i class="uil uil-facebook"></i>
            <i class="uil uil-instagram"></i>
            <i class="uil uil-youtube"></i>
        </div> 
    </section>

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
    name:"HomeFirst"
}
</script>

<style>
    .home_first{
    width: 100%;
    height: 650px;
    background-image: url("../assets/Se\ extinguen\ los\ glaciares.jpeg");
    background-size: cover;
    background-position-y: -100px;
    background-repeat: no-repeat;
    display: flex;
    justify-content: space-between;
    align-items: center;
    }

    .donation_button{
    color: white;
    font-weight: bold;
    background-color: black;
    padding: 12px;
    border-radius: 0 5px 5px 0;
    }
    .first_text{
    position: relative;
    left: -208px;
    }
    .first_text > p{
    font-size: 64px;
    }

    .first_sub{
    display: flex;
    justify-content: space-between;
    row-gap: 8px;
    }


    .first_sub_sub > h1{
    color: darkcyan;
    font-size: 48px;
    margin: 0;
    }
    .first_sub_sub > p{
    text-decoration: underline;
    text-underline-offset: 16px;
    font-weight: bold;
    font-size: 12px;

    }

    .first_logos{
    display: flex;
    flex-direction: column;
    padding: 0 4px;
    background-color: black;
    color: white;
    border-radius: 5px 0 0 5px;
    }


        
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