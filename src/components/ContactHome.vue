<template>
    <section class="contact_container">
        <h2 class="contact_title">Contacto</h2>
        <p>Nos da mucho gusto tu interés en nosotros. Déjanos saber como podemos ayudarte</p>
        <div class="form_container">
            <form action="" class="contact_form">
                <div class="contact_content">
                    <label for="" class="contact_label">Nombre</label>
                    <input type="text" class="contact_input">
                </div>

                <div class="contact_content">
                    <label for="" class="contact_label">Correo electrónico</label>
                    <input type="text" class="contact_input">
                </div>

                <div class="contact_content">
                    <label for="" class="contact_label">¿Como podemos ayudarle</label>
                    <textarea name="message" id="" cols="0" rows="10" class="contact_message"></textarea>
                </div>

                <div class="contact_button_container">
                    <div>
                        <input type="checkbox" name="suscribe" id="suscribe">
                        <label for="suscribe">Suscribirme</label>
                    </div>
                    
                    <input type="button" value="Enviar">
                </div>
            </form>
        </div>
    </section>
</template>

<script>
export default {
    name: "ContactHome"
}
</script>

<style>
   
    .contact_container {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding-left: 10rem;
    }
    .contact_title{
        font-size: 3rem;
        align-content: left;
        margin-bottom: 0;
        color: #2c3e50;
    }

    .form_container{
        display: flex;
        margin-bottom: 4rem;
        padding-top: 1rem;
    }

    .contact_content {
        display: flex;
        flex-direction: column;
        padding-bottom: 1rem;
        align-items: flex-start;
    }

    .contact_input{
        outline: none;
        border:none;
        border-bottom: solid;
        border-bottom-width: 0.1rem;
        border-block-color: #2c3e50;
        padding-top: 4rem;
        width: 20rem;
    }

    .contact_message{
        outline: none;
        border:none;
        border-bottom: solid;
        border-bottom-width: 0.1rem;
        border-block-color: #2c3e50;
        width: 20rem;
        height: 9rem;
    }

    .contact_button_container{
        display: flex;
        justify-content: space-evenly;
    }

    
</style>