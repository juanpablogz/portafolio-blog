<template>
  <div class="container-dark-mode">
    <button
      v-show="$colorMode.preference != 'dark'"
      style="background: transparent; border: none; position: absolute; z-index: 2; max-width: 30px"
      @click="$colorMode.preference = 'dark'"
    >
      <svg style="color: black; max-width: 30px">
        <path
          fill="currentColor"
          d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z"
        ></path>
      </svg>
    </button>
    <button
      v-show="$colorMode.preference != 'light'"
      style="background: transparent; border: none; position: absolute; max-width: 30px"
      @click="$colorMode.preference = 'light'"
    >
      <svg style="color: white; max-width: 30px">
        <path
          fill="currentColor"
          d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z"
        ></path>
      </svg>
    </button>
    <div class="language">
      <div ><nuxt-link  class="language-letter" :to="switchLocalePath('es')" style="margin-right: 5px">Español |</nuxt-link></div>
      <div ><nuxt-link  class="language-letter" :to="switchLocalePath('en')">English</nuxt-link></div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      change: true
    };
  },
  methods: {
  }
};
</script>
<style>
button {
  cursor: pointer;
}
body {
  background-color: #fff;
  color: rgba(0, 0, 0, 0.8);
}
.dark-mode body {
  background-color: #091a28;
  color: #ebf4f1;
}
.sepia-mode body {
  background-color: #f1e7d0;
  color: #433422;
}
.language {
    display: flex;
    justify-content: flex-end;
}
.language-letter {
  color: black;
  font-weight: bold;

}
</style>
