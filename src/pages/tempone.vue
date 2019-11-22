<template>
  <div id="tempone">
    <h1>여기는 tempone 입니다.</h1>
    <p>전달된 파라미터 : {{tempParam}}</p>
  </div>
</template>

<script>
export default {
  name: "tempone",

  computed: {
    tempParam() {
      return this.$route.params.one_param;
    }
  }
};
</script>