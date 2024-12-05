<template>
  <q-page class="column flex-center">
    <div class="q-my-md">
      <h1 class="q-ma-auto bg-red-500 q-pa-md">UnoCSS</h1>
    </div>
    <div class="q-my-md">
      <button
        bg="blue-400 hover:blue-500 dark:blue-500 dark:hover:blue-600"
        text="sm white"
        p="y-2 x-4"
        border="2 rounded blue-200"
      >
        Button
      </button>
    </div>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage',
})
</script>
