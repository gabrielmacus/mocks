<template>
  <div class="workspace" >

    <div class="toolbar-wrapper">
      <toolbar></toolbar>
    </div>

    <div class="mockbox-wrapper">
      <mockbox></mockbox>
    </div>

  </div>

</template>

<script>
  import Toolbar from '@/components/Toolbar'
  import Mockbox from '@/components/Mockbox'

  export default {
    components:{Toolbar,Mockbox},
    name: 'Workspace',
    data () {
      return {

      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  .workspace
  {

    width:100%;
    height:100%;

    .mockbox-wrapper
    {
      width: auto;
    }

    .toolbar-wrapper
    {
      width: 100%;
      max-width: 80px;
      height: 100%;
    }

    .toolbar
    {
      left:0;
      width:100%;
      height: 100%;
      top:0;
      transition:all 0.2s;
    }


  }


</style>
