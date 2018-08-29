<script>
  export default {

    name: 'Mockbox',
    props:
      {
        columns:{type:Number,default:48},
        rows:{type:Number,default:48}
      },
    data () {
      return {

      }
    }
  }
</script>
<template>
  <div class="mockbox" v-bind:style="{ gridTemplateRows:'repeat('+rows+',1fr)',gridTemplateColumns:'repeat('+columns+',1fr)'}">


  </div>
</template>

<style scoped lang="scss">
  .mockbox
  {
    display: grid;
    height: 100%;
    width: 100%;
  }
</style>
