<script setup lang="ts">
import MyComponent from "./MyComponent";

function handleEvent(message: string) {
  alert(message)
}
</script>

<template>
  <div>
    <MyComponent @custom="handleEvent" message="Hello World!"></MyComponent>
  </div>
</template>