<template>
  <div class="container-description">
    <div class="text-description">
      <h1 class="title-description">{{ $t('hello') }}</h1>
      <p>{{ $t('studied') }}</p>
      <!-- <strong>{{ $t('contact') }}</strong>
      <p style="color:blue">https://www.linkedin.com/in/juan-pablo-gomez-zapata-b9a50a17b/</p> -->
      <a
        href="https://drive.google.com/file/d/18mPbD10ghFoQzcnDIInmJ6qxLHl95vhB/view?usp=sharing"
        target="_blank"
      >
        <button class="button primary">{{ $t('dowload') }}</button>
        <button class="button secondary">
          <a href="https://api.whatsapp.com/send?phone=573506956606" target="_blank"
            >{{ $t('speak') }}</a
          >
        </button>
      </a>
    <div class="container-projects title-index">{{ $t('title') }}</div>
    </div>
    <div>
      <img
        class="img-description"
        src="https://res.cloudinary.com/dutj1bbos/image/upload/v1625946455/48387013_2163826213882758_4487837926322864128_n_d7kwc6.jpg"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {}
};
</script>

<style>
a {
  text-decoration: none;
  color: white;
}
.title-index {
  display: flex;
  justify-content: end;
  font-size: 24px;
  margin: 15px 0px;
}
</style>
