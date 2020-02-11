<template>
  <div id="app">
    <h3 class="form-heading">Columbia New Employee Intake Form</h3>
    <IntakeForm />
  </div>
</template>

<script>
import IntakeForm from "./components/IntakeForm.vue";

export default {
  name: "App",
  components: {
    IntakeForm
  }
};
</script>

<style scoped>
#app {
  width: 800px;
  height: 100%;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  padding: 10px 10px;
  border: 1px solid black;
}

.form-heading {
  text-align: center;
}
</style>
