<template>
    <footer>
      <p>{{ copyright }} - {{ year }}</p>
    </footer>
</template>

<script>
export default{
  data(){
    return {
      copyright: "Tüm Hakları Saklıdır. (c)",
      year: 2023
    }
  }
}
</script>

<style scoped>
footer{
  background: #7d4141;
  padding: 6px;
}
p{
  color: rgb(234, 223, 223);
  text-align: center;
}
</style>