<template>
  <div style="background-color: blue" class="text-center">
    <h1 font="Times New Roman" style="color: white; text-transform: uppercase" class="py-4">
     Blogbook
    </h1>
  </div>
  <div>
    <img src="../assets/profile-foto.jpg" alt="profile" width="100" />
  </div>
  <div class="mt-16 mx-10">
    <div id="Enis Çağrı Eroğlu">
      <h1 class="text-center">Enis Çağrı Eroğlu</h1>
    </div>
  </div>
  <p class="text-center">Blog Yazılarım</p>
  <div class="mt-16 mx-10">
    <div  class="text-center">
      <v-text-field
      v-model="Ekle.id"
      label="Yeni yazı"
        outlined
        class="mt-4 text-field"
      ></v-text-field>
      <v-btn
        color="purple"
        variant="tonal"
        class="mt-4"
        @click="Ekle"
      >
       Ekle
      </v-btn>
    </div>
  </div>
  <div>
    <div id="Yeni yazı">
      <h2 class="text-center player-name">{{ Ekle}}</h2>
  </div>
  </div>

  </template>
  <script>
</script>
<script setup>
import { ref } from "vue";

var Ekle = ref([Ekle]);



</script>


