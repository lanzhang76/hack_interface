<template>
  <div>
    <span>Current Mode: {{ picked }}</span>
    <br />
    <input type="radio" id="one" value="Write" v-model="picked" />
    <label for="one">Write</label>
    <br />
    <input type="radio" id="two" value="Group Improv" v-model="picked" />
    <label for="two">Group Improv</label>
    <br />
    <input type="radio" id="three" value="Rant" v-model="picked" />
    <label for="two">Rant</label>
    <br />
  </div>
</template>>

<script>
export default {
  name: "modes",
  data() {
    return {
      picked: ""
    };
  },
  methods: {}
};
</script>

<style scoped>
</style>