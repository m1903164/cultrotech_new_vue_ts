<template>
  <div class="login">
    <div class="login__container">
      <NInput type="text" placeholder="Введите телефон"/>
      <NInput type="text" placeholder="Введите пароль"/>
      <NButton>Войти</NButton>
    </div>
  </div>
</template>

<script setup lang="ts">
import { NButton, NInput } from 'naive-ui';
</script>

<style scoped>
.login {
  background-color: #D6A673;
  height: 100vh;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.login__container {
  //display: flex;
  //flex-direction: column;
  //justify-content: center;
  max-width: 350px;
}
</style>