<template>
    <section class="home_first">
        <div class="donation_button">
            <span>¡Dona ahora!</span>
        </div>    
        <div class="first_text">
            <span class="red22">SE EXTINGUEN</span>
            <br> 
            <span>LOS GLACIARES</span>
            <br> 
            <span>EN MÉXICO</span>
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
                Actualmente solo dos zonas tienen glaciares en México. Después de la pequeña edad de hielo <br> solo han existido tres volcanes activos que han albergado glaciares: Popocatepetl, Iztaccíhuatl y Citlaltépetl.<br> Los glaciares de México se encuentran condenados a la extinción a causa del cambio climático,  por esto, <br> es urgente generar estrategias para la mitigación y adaptación de los impactos del cambio climático <br> y trabajar hacia un compromiso y una acción colectiva para la preservación de los entornos de montaña.
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
    position: fixed;
    left: 0rem;
    bottom: 50%;
    }
    .first_text{
        padding-left: 12rem;
    }
    .first_text > span{
    font-size: 64px;
    font-weight: bold;
    }

    .red22 {
        color: rgb(250,42,94);
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
    position: fixed;
    right: 0rem;
    bottom: 50%;

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