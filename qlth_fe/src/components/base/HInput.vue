<template>
  <div>
    <input :type="typeInput" class="m-input" :placeholder="placeHolder" />
  </div>
</template>

<script>
export default {
  props: ["placeHolder", "width", "typeInput"],
};
</script>

<style scoped>
.m-input {
  height: 40px;
  border: 1px solid #bbbbbb;
  border-radius: 4px;
  padding-left: 16px;
  box-sizing: border-box;
  width: 100%;
}

.m-input:focus {
    outline: none;
    border: 1px solid #019160;
}
</style>