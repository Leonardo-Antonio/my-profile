<template>
  <div>
    <div class="btn flex justify-center items-center color__decoration">
      <span>Resumen</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "ButtonSmall",
};
</script>

<style>
.btn {
  border: 2px solid var(--decoration);
  box-sizing: border-box;
  border-radius: 20px;

  width: 150px;
  height: 40px;

  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 80px;
}

.btn:hover {
  background-color: var(--hover_btn);
  transition: all 0.3s;
}
</style>
