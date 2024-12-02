<script setup>
import Hello from './components/HelloComponent.vue'
import TemplateSyntax from './components/TemplateSyntax.vue'
import ReactiveFundamentals from './components/ReactivityFundamentals.vue'
import FormInputBindings from './components/FormInputBindings.vue'
import HelloMyName from './components/HelloMyName.vue'
import MyPlus from './components/MyPlus.vue'
import MyBmi from './components/MyBmi.vue'
</script>

<template>
  <MyBmi></MyBmi>
  <hr />
  <MyPlus></MyPlus>
  <hr />
  <HelloMyName></HelloMyName>
  <hr />
  <FormInputBindings></FormInputBindings>
  <hr />
  <ReactiveFundamentals></ReactiveFundamentals>
  <hr />
  <div>Hello</div>
  <hr />
  <span><Hello></Hello></span>
  <hr />
  <TemplateSyntax></TemplateSyntax>
  <hr />
</template>

<style scoped></style>
