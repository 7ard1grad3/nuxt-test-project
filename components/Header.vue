<template>
  <header>
    <ul class="nav_items">
      <li>
      <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
      <nuxt-link to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
  header {
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: beige;
  }
  .nav_items {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 80%;
  }
  .nav_items a{
    text-decoration: none;
    color: black;
  }
  .nav_items a:hover,
  .nav_items a:active
  {
    text-decoration: none;
    color: rgb(95, 150, 13);
  }
</style>
