<template>
  <div class="container-projects custom-experience">
    <div class="projects-jp">
      <h2>Sobre mi</h2>
      <p>
        Hola mi nombre es juan pablo, soy desarrollador de software, vivo en
        medellin,colombia.Desarrollo aplicaciones web, principalmente con Vuejs,
        Quasar y NuxtJs. En el backend he realizado Api rest con ruby on rails
      </p>
      <h2>Experiencia laboral</h2>
      <div>
        Especialista en casa
        <strong>junio de 2018 - presente (emprendimiento propio)</strong>
      </div>
      <p>
        Desarrollo front end de todo el software con el que se controlan
        servicios médicos, especialmente servicios de fisioterapia. Este
        servicio puede ser tomado de manera remota y en domicilio del paciente
      </p>
      <div>31Rooms <strong>noviembre de 2020 - junio de 2021</strong></div>
      <p>
        Desarrollador front end vuejs, desarrollo de diversos proyectos con
        tecnologias como vuejs, nuxt y quasar. Prouectos como estrella
        restaurante, since.love
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      experience: [{}]
    };
  }
};
</script>

<style>
.dark-mode strong {
  color: #2cc4a0;
}
</style>
