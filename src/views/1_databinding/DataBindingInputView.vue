<template>
  <div>
    <input type="text" v-model="userId" />
    <p>{{ userId }}</p>
    <button @click="myFunction">클릭</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'asd'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    myFunction() {
      console.log(this.userId)
    }
  }
}
</script>
