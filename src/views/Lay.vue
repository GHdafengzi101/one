<template>
  <div class="menu">
    <div class="header">header</div>
    <div class="main">main</div>
    <div class="footer">footer</div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style>
.menu {
  width: 100%;
  height: 100%;
}
.header{
  height: 30%;
  background-color: rgb(146, 232, 238);
}
.main{
  height: 60%;
  background-color: rgb(211, 245, 179);
}
.footer{
  height: 10%;
  background-color: rgb(127, 143, 177);
}
</style>
