<template lang="html">
  <div class="header">
    <div>{{msg}}</div>
    <div class="right"><img src="./icon_menu.png" alt=""></div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg:'ddddddsdd'
    }
  },
  computed: {},
  mounted () {},
  methods: {},
  components: {}
}
</script>

<style lang="css">
.header{
  width: 100%;
  text-align: center;
  padding: 20px 0;
  background: #ccc;
  font-size: 30px;
  position: relative;
}
.right{
  position: absolute;
  right: 0;
  top: 0;
}
</style>
