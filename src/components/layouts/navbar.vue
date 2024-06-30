<template>
    <div class="search-container">

      <input 
        type="text" 
        v-model="search" 
        class="search-input" 
        placeholder="Search..."
      />
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        search: ''
      };
    },
    methods: {
      searchClicked() {
        
        console.log('Search clicked');
      }
    }
  };
  </script>
  
  <style scoped>
  .search-container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;

    padding: 20px;
  }
  
  
  .search-input {
    width: 100%;
    max-width: 400px;
    padding: 10px 40px 10px 20px; 
    font-size: 16px;
    border: 1px solid #ccc;
    color: white;
    border-radius: 25px;
    outline: none;
    transition: all 0.3s ease;
  }
  
  .search-input:focus {
    border-color: green;
  }
  </style>
  