<template>
  <div>
    <div class="title-projects">{{ $t('title') }}</div>
    <div v-for="project in $t('projects')" :key="project.id">
      <div class="container-projects">
        <div class="project">
          <a :href="project.link" target="_blank"><img class="img-project" :src="project.img" alt="" /></a>
          <div>
            <div class="title-project">{{ project.name }}</div>
            <p>{{ project.description }}</p>
            <!-- <div style="background: red">{{ i18n }}</div> -->
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
    };
  }
};
</script>
