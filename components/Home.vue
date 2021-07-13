<template>
  <div class="container__home">
    <div>
      <h4 class="title__top">Hola, mi nombre es</h4>
    </div>
    <div>
      <h1 class="title__main">Leonardo Antonio Nolasco Leyva.</h1>
    </div>
    <div>
      <h2 class="title__bottom">DESARROLLADOR DE SOFTWARE</h2>
    </div>
    <div>
      <p class="text">
        Soy <span class="color__decoration">desarrollador de software</span> con
        experiencia en el front y backend, actualmente me encuntro trabajando en
        <span class="color__decoration">Prodequa</span>
        centro de desarrollo de software a medida y ayuda tecnologia para hacer el mundo
        digital.
      </p>
    </div>

    <div class="pt-9">
      <button class="btn-primary py-4 w-3/6 color__decoration text__btn">
        Ponerse en contacto
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {};
  },
  methods: {},
};
</script>

<style>
.title__top {
  font-family: Saira;
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 40px;

  color: var(--decoration);
}

.title__main {
  font-family: Saira;
  font-style: normal;
  font-weight: bold;
  font-size: 80px;
  line-height: 80px;
  color: var(--title);
}

.title__bottom {
  font-family: Saira;
  font-style: normal;
  font-weight: bold;
  font-size: 35px;
  line-height: 80px;
  color: var(--second);
}

.container__home {
  width: 870px;
}

.text__btn {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
}
</style>
