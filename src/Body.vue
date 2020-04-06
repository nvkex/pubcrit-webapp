<template>
    <div id = "tv-shows">
        <ul>
            <li v-for = "series in tvseries" v-on:click = "series.show = !series.show" :key = "series">
                <h2>{{ series.name }}</h2>
                <h3 v-show = "series.show">{{ series.myScore }}</h3>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  data () {
    return {
        tvseries:[
            {name:'The Outsider',myScore:'8.7',show:false},
            {name:'Peaky Blindes',myScore:'8.8',show:false},
            {name:'Black Sails',myScore:'8.3',show:false},
            {name:'Doom Patrol',myScore:'8.2',show:false},
            {name:'Vikings',myScore:'8.0',show:false},
            {name:'The 100',myScore:'7.5',show:false},
            {name:'La Casa de Papel',myScore:'8.9',show:false},
            {name:'Kingdom',myScore:'8.6',show:false},
            {name:'Jamtara',myScore:'8.2',show:false},
        ]
    }
  }

}
</script>

<style scoped>
#tv-shows{
    width: 100%;
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
    box-sizing: border-box;
}
ul{
    display: flex;
    flex-wrap: wrap;
    list-style-type: none;
    padding: 0;
}
li{
    background-color: lightblue;
    flex-grow: 1;
    flex-basis: 300px;
    text-align: center;
    padding: 30px;
    border: 1px solid #222;
    margin: 10px;
}
li:hover{
    cursor: pointer;
}
    
</style>
