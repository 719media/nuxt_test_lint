<script setup>

const someVariable = 'apple';
const someOtherVariableWithoutSemicolon = 'banana'
  const someOtherVariableIndentedWrong = 'cucumber';
</script>
<template>
  <div>
    <div v-text="someVariable" />
    <div v-text="someOtherVariableWithoutSemicolon" />
    <div v-text="someOtherVariableIndentedWrong" />
  </div>
</template>
