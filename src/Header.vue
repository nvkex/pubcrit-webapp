<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  data () {
    return {
      title: 'PUBCRIT'
    }
  }

}
</script>

<style>
    header{
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        background:lightgreen;
        padding: 10px;
    }
    h1{
        color:#222;
        text-align: center;
    }
</style>
