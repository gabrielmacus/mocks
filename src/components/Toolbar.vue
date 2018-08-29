<template>
  <ul class="toolbar">

    <li @click="insertBlock()" class="tool">
      Bloque
    </li>


  </ul>
</template>

<script>
  export default {
    name: 'Toolbar',
    methods:
    {
      insertBlock()
      {

      }
    },
    data () {
      return {


      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import "../assets/_theme.scss";
  .toolbar
  {
    width: 100%;
    background: $main-background;

  }
  .tool
  {

    transition:all 0.2s;
    color:$main-color;
    padding:$main-padding;
    cursor:pointer;
  width:auto;
  display:inline-block;
    &:hover
     {

      color:$secondary-color;
      background: $secondary-background;
     }
  }


</style>
