<template>
  <div>
     <img src="@/assets/img/home.jpg" :style="{height:height+'px',width:width+'px'}">
  </div>
</template>

<script>
export default {
  data () {
    return {
       height:0,
       width:0
    }
  },
  mounted() {
     this.height = window.innerHeight;
     this.width = window.innerWidth
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
