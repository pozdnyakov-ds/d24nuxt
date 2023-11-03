<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup>
onMounted(() => {
  console.log("MODE: ", process.env.NODE_ENV)
  //...
})

</script>