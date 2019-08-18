<template>
  <div>
    <div class="index-background">
        <img src="./../assets/index1.png" style="position: absolute;width: 100%;bottom: 0;"></img>
        <img src="./../assets/moon.png" style="position: absolute; height: 8.75rem;top: 0;left:0;"></img>
        <img src="./../assets/title.png" style="position: absolute; width: 18.96%;top: 7.55rem;left: 40%;"></img>
        <img src="./../assets/decorate.png" style="position: absolute; width: 91.56%; left: 4.22%; bottom: 22.08%;"></img>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.index-background{
    width: 100%;
    height: 30rem; 
    background-color: #2A272B; 
    margin: 0;
    position: relative;
}

</style>
