<template>
  <div class="flex justify-center">
    <div style="width: 640px">
      <div>
        <div class="flex flex-row items-center">
          <div class="w-230">
            <h2 class="title__items">Acerca de mí</h2>
          </div>
          <div class="line__title"></div>
        </div>
        <div class="space-sm"></div>
        <div class="w-full pt-9">
          <el-tabs tab-position="left" class="w-tab">
            <el-tab-pane label="Prodequa">
              <div>
                <h4 class="title__tab">
                  Desarrollador de Software
                  <span class="color__decoration">@ Prodequa</span>
                </h4>
                <h5 class="subtitle__tab pb-4">Mayo de 2021 - actualidad</h5>
                <div>
                  <ul>
                    <li class="flex items-start">
                      <div class="arrow__tab">
                        <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                      </div>
                      <div class="text-md">
                        Desarrollando Ecommerce en Vtex, facil de implementar y de rapido
                        desarrollo
                      </div>
                    </li>
                    <li class="flex items-start">
                      <div class="arrow__tab">
                        <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                      </div>
                      <div class="text-md">
                        Desarrollando Ecommerce en Vtex, facil de implementar y de rapido
                        desarrollo
                      </div>
                    </li>
                    <li class="flex items-start">
                      <div class="arrow__tab">
                        <i class="bx bx-right-arrow" style="color: #64ffda"></i>
                      </div>
                      <div class="text-md">
                        Desarrollando Ecommerce en Vtex, facil de implementar y de rapido
                        desarrollo
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </el-tab-pane>
            <el-tab-pane label="HydroPumps">Config</el-tab-pane>
            <el-tab-pane label="Luis Howard">Role</el-tab-pane>
          </el-tabs>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Experience",
};
</script>

<style>
.title__tab {
  font-family: Saira;
  font-style: normal;
  font-weight: 600;
  font-size: 22px;
  line-height: 30px;
  color: #fff;
}
.subtitle__tab {
  font-family: Saira;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  color: var(--second);
}

.w-tab {
  width: 700px;
}

.arrow__tab {
  padding-top: 0.3rem;
  padding-right: 1rem;
}
</style>
