<template>
  <div class="form">
    <form action="">
      <input type="text" placeholder="Enter First Name" />
      <input type="text" placeholder="Enter Last Name" />
      <input type="email" placeholder="Enter Email" />
      <input type="date" placeholder="Enter Birth Date" />
      <input type="password" placeholder="Enter Password" />
      <input type="phone" placeholder="Enter Phone Number" />
      <div class="custom-select">
        <select name="sex" id="sex">
          <option value="Male">Male</option>
          <option value="Female">Female</option>
        </select>
      </div>
      <input type="text" placeholder="Enter Department" />
      <input type="text" placeholder="Enter Institution" />
      <Button title="register"></Button>
    </form>
  </div>
</template>

<script>
import Button from "../components/Button.vue";

export default {
  components: { Button },
};
</script>
<style scoped>
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
select {
  display: inline-block;
  box-sizing: border-box;
  padding: 0.5em 2em 0.5em 0.5em;
  border: 1px solid #eee;
  font: inherit;
  line-height: inherit;
  -webkit-appearance: none;
  -moz-appearance: none;
  -ms-appearance: none;
  appearance: none;
  background-repeat: no-repeat;
  background-image: linear-gradient(45deg, transparent 50%, currentColor 50%),
    linear-gradient(135deg, currentColor 50%, transparent 50%);
  background-position: right 15px top 1em, right 10px top 1em;
  background-size: 5px 5px, 5px 5px;
}
</style>
