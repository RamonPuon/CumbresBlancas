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
                    <textarea name="message" id="" cols="0" rows="10" class="contact_input"></textarea>
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
    }

    .contact_content {
        display: flex;
        flex-direction: column;
    }

    .contact_input{
        outline: none;
        border:none;
        border-bottom: solid;
        border-bottom-width: 0.1rem;
        border-block-color: #2c3e50;
    }

    
</style>