<template>
  <footer>
    <p>{{ cpy }}</p>
  </footer>
</template>

<script>
export default {
  data () {
    return {
      cpy: 'Copyright 2020 NVKEX'
    }
  }

}
</script>

<style>
    footer{
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        background:#222;
        padding: 6px;
    }
    p{
        color: lightgreen;
        text-align: center;
    }
</style>
