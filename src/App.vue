<template lang="html">
  <div id="app">
    <headJB></headJB>
  </div>
</template>

<script>
import headJB from './components/headJB/headJB'
// import footer from './components/footer/footer'
export default {
  name:"app",
  components: {
    headJB
  }
}
</script>

<style lang="css">
</style>


<!-- <template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>

</style> -->
<!-- <template lang="html">
  <div id="app">
    <h1 v-html="titer"></h1>
    <input v-model="newinput" @keyup.enter="inputclick">
    <div v-for="item in items" :class="{ div01:item.isFinished }" @click="togglediv(item)">
      {{ item.lable }}
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      titer:'<span>11</span>adasdasdasdasd',
      items:[
        {
          lable:'coding',
          isFinished:false
        },
        {
          lable:'working',
          isFinished:true
        }
      ]
    }
  },
  //方法
  methods: {
    togglediv:function(item) {
      item.isFinished = !item.isFinished
    },
    inputclick:function(){
      this.items.push({
        lable:this.newinput,
        isFinished:false
      })
      this.newinput=''
    }
  },
  components: {}
}
</script>

<style lang="css">
.div01{
  text-decoration: underline;
}
</style> -->
