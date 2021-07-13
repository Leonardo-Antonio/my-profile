<template>
  <div class="py-1 fixed w-full bg-primary shadow__header z-50">
    <div class="flex justify-between container mx-auto">
      <div class="flex items-center">
        <span>
          <img src="../assets/img/logo.svg" alt="" />
        </span>
      </div>
      <div class="flex items-center">
        <ul class="flex items-center">
          <li class="item__menu px-4">Sobre mí</li>
          <li class="item__menu px-4">Experiencia</li>
          <li class="item__menu px-4">Proyectos</li>
          <li class="item__menu px-4">Trabajemos</li>
          <li class="pl-4">
            <a href="https://google.com">
              <ButtonSmall />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Header",
};
</script>

<style>
.shadow__header {
  box-shadow: 2px 7px 20px 1px rgba(9, 0, 0, 0.25);
}
</style>
