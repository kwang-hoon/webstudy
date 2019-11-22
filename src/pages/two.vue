<template>
  <div id="two">
    <h1>여기는 페이지2입니다.</h1>
    <router-link to="/two/temptwo?temp_query=1">temptwo로 쿼리보내기</router-link>
  </div>
</template>

<script>
export default {
  name: "two"
};
</script>