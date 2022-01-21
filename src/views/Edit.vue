<template>
  <div class="edit">
    <div class="top"></div>
    <div class="bottom">
      <div class="hierarchy"></div>
      <div class="canvas"></div>
      <!-- <div class="inspector"></div> -->
    </div>
  </div>
</template>

<style lang="scss" scoped>
.edit {
  display: flex;
  flex-direction: column;
  height: 100%;
}
.top {
  height: 40px;
  background: #ccc;
  border-bottom: 1px solid #000;
}
.bottom {
  display: flex;
  flex: 1;
}
.hierarchy {
  width: 100px;
  background: #ccc;
}
</style>
