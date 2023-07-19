<script setup>
import CustomInput from './components/CustomInput.vue'
import {reactive} from "vue";

const form = reactive({
  name: ''
})
</script>

<template>
  <CustomInput v-model="form.name" placeholder="Placeholder sent by props"/>

  {{ form }}
</template>
