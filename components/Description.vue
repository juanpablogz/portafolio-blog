<template>
  <div class="container-description">
    <div class="text-description">
      <h1 class="title-description">{{ $t('hello') }}</h1>
      <p>{{ $t('studied') }}</p>
      <!-- <strong style="margin-bottom: 10px">{{ $t('contact') }}</strong> -->
      <!-- <p style="color:blue">https://www.linkedin.com/in/juan-pablo-gomez-zapata-b9a50a17b/</p> -->



        <button class="button primary" href="https://drive.google.com/file/d/103uQIk5U59i2pcvmADrbjcv51hrQ9QMx/view?usp=sharing" target="_blank">
          <a style="padding: 20px" href="https://drive.google.com/file/d/1w0F_8E_3eS8qGiitBqG2dOZRD3U5v7P9/view?usp=sharing" target="_blank"
            >{{ $t('dowload') }}</a
          >
        </button>
        <button class="button secondary" href="https://api.whatsapp.com/send?phone=573506956606" target="_blank">
          <a style="padding: 20px" href="https://api.whatsapp.com/send?phone=573506956606" target="_blank"
            >{{ $t('speak') }}</a
          >
        </button>

    <div class="title-index">{{ $t('title') }}</div>
    </div>
    <div class="image-index">
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

  font-size: 24px;
  margin: 15px 0px;
}
</style>
