<template>
  <div>
    <div>
      <div class="fixed bottom-0 left-12">
        <ul class="flex items-center flex-col">
          <li>
            <i class="bx bxl-github icon py-2"></i>
          </li>
          <li>
            <i class="bx bxl-linkedin icon py-2"></i>
          </li>
          <li>
            <i class="bx bxl-whatsapp icon py-2"></i>
          </li>
          <li>
            <i class="bx bxl-telegram icon py-2"></i>
          </li>
          <li class="pt-8">
            <div class="line"></div>
          </li>
        </ul>
      </div>
    </div>

    <div>
      <div class="fixed bottom-0 right-12">
        <ul class="flex items-center flex-col">
          <li>
            <i class="bx bx-message-square-dots icon"></i>
          </li>
          <li class="pt-8">
            <div class="line"></div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MenuFixed",
};
</script>

<style>
.line {
  height: 150px;
  background: var(--title);
  width: 3px;
}
</style>
