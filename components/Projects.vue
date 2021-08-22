<template>
  <div>
    <div class="title-projects">Proyectos en los que participado</div>
    <div v-for="project in projects" :key="project.id">
      <div class="container-projects">
        <div class="project">
          <a :href="project.link" target="_blank"><img class="img-project" :src="project.img" alt="" /></a>
          <div>
            <div class="title-project">{{ project.name }}</div>
            <p>{{ project.description }}</p>
          </div>
        </div>
      </div>
      <hr>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          name: "Since.love",
          description: "Proyecto de citas. En este proyecto participe en el front end, realice diversos componentes en los cuales el más destacado fue la sección de videollamada",
          tecnologies: "xxxx",
          img:"https://res.cloudinary.com/dutj1bbos/image/upload/v1615506917/Captura_de_Pantalla_2021-03-11_a_la_s_6.55.05_p._m._bzdvya.png",
          link: "https://www.since.love/"
        },
        {
          name: "Estrella restaurante",
          description: "Realizado con quasar, en el cual tienes un menú y puedes seleccionar diferentes características y agregarlas al carrito, una vez termines tu pedido, te redirigirá a whatsapp con un mensaje personalizado con todo tu pedido.",
          tecnologies: "xxxx",
          img:"https://res.cloudinary.com/dutj1bbos/image/upload/v1625950103/Captura_de_Pantalla_2021-07-10_a_la_s_3.48.05_p._m._ijznga.png",
          link: "https://estrellarestaurante.com/"
        },
        {
          name: "Especialista en casa",
          description: "Especialista en casa, un proyecto de fisioterapia, el cual tiene dos modelos de negocio. Atención domiciliaria y atención virtual, para la parte virtual hicimos una integración con calendly. Fue realizado en nuxt",
          tecnologies: "xxxx",
          img:"https://res.cloudinary.com/dutj1bbos/image/upload/v1625950334/Captura_de_Pantalla_2021-07-10_a_la_s_3.52.03_p._m._v6ny9j.png",
          link: "https://www.especialistaencasa.com/"
        },
        {
          name: "Pokedex",
          description: "Pokedex, listado pokémons Favoritos. fue realizado con vuejs, nuxt,vuex, local storage y conexión a la api https://pokeapi.co/",
          tecnologies: "xxxx",
          img:"https://res.cloudinary.com/dutj1bbos/image/upload/v1625950239/Captura_de_Pantalla_2021-07-10_a_la_s_3.50.29_p._m._nvsoxg.png",
          link: "https://pokedexjpgz.netlify.app/"
        },
        {
          name: "Hulu clon",
          description: "Hulu clon realizado con React, NextJs, TailwindJs y conexión a la api the movie DB, despliegue en vercel",
          tecnologies: "xxxx",
          img:"https://res.cloudinary.com/dutj1bbos/image/upload/v1629675008/Captura_de_Pantalla_2021-08-22_a_la_s_6.29.47_p._m._veau7c.png",
          link: "https://hulu-jpgz.vercel.app/"
        }
      ]
    };
  }
};
</script>
