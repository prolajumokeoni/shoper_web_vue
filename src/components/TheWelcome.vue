
<script setup>
// import LoginForm from '../components/LoginForm.vue'
// import CreatePassword from './CreatePassword.vue';
import RegisterForm from './RegisterForm.vue';
</script>
<template>
  <div class="wrapper">
    <div class="left">
      <img src="../assets/frame.png" />
    </div>
    <div class="right">
      <!-- <LoginForm /> -->
<RegisterForm />
<!-- <CreatePassword /> -->
    </div>
  </div>
</template>
<style>
.wrapper {
  width: 100%;
  display: flex;
  flex-direction: row;
}
.left {
  width: 50%;
}
</style>