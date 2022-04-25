<template>
  <div class="demo">
    <h2>學校名稱:{{ schoolName }}</h2>
    <h2>學校地址:{{ schoolAddress }}</h2>
    <button @click="showMsg">點擊提示學校</button>
  </div>
</template>

<script>
export default {
  name: School,
  data() {
    return { schoolName: "板新", schoolAddress: "新北市" };
  },
  methods: {
    showMsg() {
      console.log(this);
    },
  },
};
</script>

<style>
.demo {
  background-color: orange;
}
</style>
