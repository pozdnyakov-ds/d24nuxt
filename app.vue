<template>
  <div>
    Wellcome into branch
    <NuxtWelcome />
  </div>
</template>

<script setup>
onMounted(() => {
  console.log("MODE: ", process.env.NODE_ENV)
  //...
})

</script>