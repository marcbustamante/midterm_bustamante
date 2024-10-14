<template>
    <div>
      <h1>Welcome</h1>
      <nav>
        <router-link to="/home">Home</router-link> |
        <router-link to="/products">Products</router-link>
      </nav>
      <p>Your Name: Marc Leobenz Bustamnate</p>
      <p>Program: BSIT</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Home',
  }
  </script>
  
  <style scoped>
  div {
    font-family: 'Courier New', Courier, monospace;
  }
  </style>