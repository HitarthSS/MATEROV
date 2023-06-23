<template>
  <button class="menu-button">Menu</button>
</template>

<script>
export default {
  name: 'MenuButton',
};
</script>

<style scoped>
.menu-button {
  padding: 10px 20px;
  background-color: #444;
  color: #fff;
  font-size: 16px;
  border: none;
  cursor: pointer;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

.menu-button:hover {
  background-color: #555;
}

.menu-button:focus {
  outline: none;
}
</style>
