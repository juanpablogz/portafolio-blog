<template>
  <div class="container-projects custom-experience">
    <div class="projects-jp">
      <h2>{{ $t("about") }}</h2>
      <p>{{ $t("description") }}</p>
      <h2>{{ $t("experience") }}</h2>
      <div>

        <strong>{{ $t("especialista_experience") }}</strong>
      </div>
      <p>{{ $t("description_especialista") }}</p>
      <div>

        <strong>{{ $t("rooms") }}</strong>
      </div>
      <p>
        {{ $t("rooms_description") }}
      </p>

      <div>
        <strong>{{ $t("sanvicente") }}</strong>
      </div>
      <p>
        {{ $t("sanvicente_description") }}
      </p>

      <div>
        <strong>{{ $t("arlene") }}</strong>
      </div>
      <p>
        {{ $t("arlene_description") }}
      </p>
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

<style>
.dark-mode strong {
  color: #2cc4a0;
}
</style>
