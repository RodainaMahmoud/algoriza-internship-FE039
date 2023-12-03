<template>
    <div class="drop-down-container"></div>
  </template>
  
  <script>
  export default {
    name: 'DropDown',
    props: {},
  }
  </script>
  
  <style scoped>
  .drop-down-container {
    width: 100%;
    display: flex;
    overflow: auto;
    min-height: 100vh;
    align-items: center;
    flex-direction: column;
  }
  </style>
  