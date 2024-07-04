<template>
    <nav>
      <ul>
        <li>
          <router-link to="/" exact active-class="active-link">Main</router-link>
        </li>
        <li>
          <router-link to="/about" exact active-class="active-link">About</router-link>
        </li>
      </ul>
    </nav>
  </template>
  
  <script setup>
  import { RouterLink } from 'vue-router';
  </script>
  
  <style scoped>
nav {
  background-color: #f1f1f1;
  padding: 10px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline;
  margin-right: 10px;
}

li .active-link {
  background-color: #4caf50;
  color: white;
  padding: 5px 10px;
  border-radius: 5px;
}
</style>