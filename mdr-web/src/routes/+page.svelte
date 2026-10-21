<div id="homepage" class="container has-background-light mt-5 mb-5">
   <header id="mainheader" class="is-flex is-flex-direction-column is-justify-content-center is-align-items-center">
      cabecera
   </header>
   <nav id="mainmenu" class="is-block">
     Navegación
   </nav>
   <section id="secmusica" class="section is-block">
      Música
   </section>
   <section id="secvideos" class="section is-block">
      Vídeos
   </section>
   <section id="seccontacto" class="section is-block">
      contacto
   </section>
</div>

<style>
    #homepage
    {
        display: grid;
        grid-template-rows: 30% 10% 30% 30% auto;

    }

    #mainheader {
        background-color: lightblue;
    }

    #mainmenu
    {
        background-color: lightcoral;
    }

    #secmusica
    {
        background-color: lightgreen;
    }

    #secvideos
    {
        background-color: lightgrey;
    }

    #seccontacto
    {
        background-color: lightpink;
    }
</style>

<script lang="ts">
    document.title="Portada - Mad Duende Records";
</script>
