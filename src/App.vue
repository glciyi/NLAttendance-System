<template>
  <div id="app">
    <img src="./assets/logo.png">
    <button @click = "dianji">{{ btn }}</button>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      btn : '按钮',      
    }
  },
  created() {
    this.dianji();
  },
  methods : {
    dianji () {
      alert(1);
    }
  }

}
</script>

<style>

</style>
