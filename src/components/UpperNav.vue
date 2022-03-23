<template>
    <div>
        <header class="header">
        <img src="../assets/mexico.png" alt="mexico" class="header_icon">
        <p>ES</p>
        <i class="uil uil-angle-down"></i>
    </header>
    <nav>
        <img src="../assets/logo_blanco.png" alt="logo" class="cumbre_logo">
        <div class="nav_title">
            <p>¿Quiénes somos?</p>
        </div>
        <div class="nav_title">
            <p>Proyectos</p>
        </div>
        <div class="nav_title">
            <p>¿Cómo ayudar?</p>
        </div>
        <div class="nav_title contact_title">
            <p>Contáctanos</p>
        </div>
    </nav>
    </div>
</template>

<script>
export default {
    name: 'UpperNav'
}
</script>

<style>
    .header {
    height: 24px;
    display: flex;
    align-items: center;
    column-gap: 4px;
    justify-content: right;

    }

    .header_icon{
    height: 100%;
    }

    nav{
    background-color: black;
    height: 104px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    
    }

    .cumbre_logo{
    width: 180px;
    }

    .nav_title{
    color:white;
    margin: 0;
    position: relative;
    bottom: -20px;
    font-weight: bold;

    }

    .contact_title{
    color: black;
    background-color: white;
    }
    .contact_title p{
    padding: 4px 20px;
    margin: 0;
    }
</style>