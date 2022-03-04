<template>
  <form action="">
    <input type="email" placeholder="Enter Email" />

    <input type="password" placeholder="Enter Password" />
    <Button title="register"></Button>
  </form>
</template>

<script>
import Button from "../components/Button.vue";
export default {
  components: { Button },
};
</script>

<style>
form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
}
input {
  width: 50%;
  padding: 1rem 1.2rem;
  height: 0.5rem;
  border: none;
}
</style>
