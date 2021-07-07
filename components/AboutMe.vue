<template>
  <div class="flex justify-between items-center">
    <div class="w-3/5">
      <div>
        <div class="flex flex-row items-center">
          <div class="w-230">
            <h2 class="title__items">Acerca de mí</h2>
          </div>
          <div class="line__title"></div>
        </div>
        <div>
          <p class="text pt-16">
            Hola! Mi nombre es <span class="color__decoration">Leonardo</span> y me
            encanta el desarrollo de apps, sistemas y todo con el tema de la tecnologia ya
            que es algo que me apaciona investigar y aprender.
            <span class="color__decoration"
              >Soy desarrollador backend con conocimientos</span
            >
            en el frontend, me gusta aprender por mi cuenta ya que me gusta hacer lo que
            me apaciona en mi tiempo libre.
          </p>
          <br />
          <p class="text pb-8">
            Actualmente he estado trabajando y/o utilizando las siguientes tecnologias:
          </p>
        </div>
        <div class="flex flex-row">
          <div class="pr-8">
            <ul>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> Vtex </span>
              </li>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> Golang </span>
              </li>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> JavaScript </span>
              </li>
            </ul>
          </div>

          <div>
            <ul>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> Vtex </span>
              </li>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> Golang </span>
              </li>
              <li>
                <span>
                  <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                </span>
                <span class="text-md"> JavaScript </span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="img__cover">
        <img class="img relative" src="../assets/img/me.svg" alt="me" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style>
.img {
  width: 280px;
  height: 280px;
  bottom: 15px;
  right: 15px;
}

.img:hover {
  bottom: 10px;
  right: 10px;
  transition: all 0.5s;
}

.img__cover {
  width: 280px;
  height: 280px;
  border: 1px solid var(--decoration);
  border-radius: 10px;
}

.w-230 {
  width: 230px;
}
</style>
