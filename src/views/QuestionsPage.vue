<template>
  <div>
    <h3>Questions Page</h3>

    {{ data }}
  </div>
</template> 
<script>
export default {
  name: "QuestionsPage",
  props: ["data"],
  data() {
    return {
      questions: null,
    };
  },
  mounted() {
    console.log("data coming from the router", this.data);
  },
};
</script>
<style lang="">
</style>