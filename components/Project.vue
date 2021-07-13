<template>
  <div>
    <div>
      <div>
        <h3 class="title__items title_main__projects">
          Algunas cosas que he desarrollado
        </h3>
      </div>
      <div class="line__title"></div>
    </div>

    <div>
      <div>
        <div class="flex flex-row justify-center">
          <div class="relative left__50px">
            <img width="630" height="380" src="../assets/img/project.svg" alt="" />
          </div>

          <div class="relative right__50px center__card">
            <div class="text-right pb-4">
              <span class="header__title">Proyectos destacados</span>
              <h5 class="title__project">Tema de Halcyon</h5>
            </div>
            <div class="text-right border__card flex justify-center items-center p-8">
              <p class="text__project text-right">
                Un tema azul oscuro mínimo para VS Code, Sublime Text, Atom, iTerm y más.
                Disponible enMercado de Visual Studio, Control de paquetes, Administrador
                de paquetes Atom, y sobre el nivel del mar.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div>
      <div>
        <div class="flex flex-row justify-center pt-16">
          <div class="relative left__50px center__card z-10">
            <div class="text-left pb-4">
              <span class="header__title">Proyectos destacados</span>
              <h5 class="title__project">Tema de Halcyon</h5>
            </div>
            <div class="text-left border__card flex justify-center items-center p-8">
              <p class="text__project text-left">
                Un tema azul oscuro mínimo para VS Code, Sublime Text, Atom, iTerm y más.
                Disponible enMercado de Visual Studio, Control de paquetes, Administrador
                de paquetes Atom, y sobre el nivel del mar.
              </p>
            </div>
          </div>
          <div class="relative right__50px">
            <img width="630" height="380" src="../assets/img/project.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Project",
};
</script>

<style>
.border__card {
  width: 542px;
  height: 210px;

  background: var(--secondary);
}

.title__project {
  font-family: Saira;
  font-style: normal;
  font-weight: 600;
  font-size: 30px;
  line-height: 30px;

  color: #ffffff;
}

.header__title {
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 30px;

  color: var(--decoration);
}

.text__project {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 30px;

  color: #fff;
}

.left__50px {
  left: 50px;
}
.right__50px {
  right: 50px;
}

.center__card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  bottom: 15px;
}

.title_main__projects {
  position: relative;
  left: 230px;
  padding-bottom: 4rem;
  overflow: hidden;
  width: fit-content;
}
</style>
