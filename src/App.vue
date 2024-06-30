<template>
  <v-card>
    <v-layout>
       <!-- sidebar -->
        <sidebar />
      <!-- main content -->
      <v-main style="height:100vh; background-color: #2d2d2d" >
              <!-- navbar -->
               
       <navbar />

      </v-main>
    </v-layout>
  </v-card>
</template>

<script setup>
import navbar from './components/layouts/navbar.vue'
import sidebar from './components/sidebar.vue';
</script>
