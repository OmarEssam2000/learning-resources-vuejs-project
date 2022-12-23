<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  props: ['title']
}
</script>

<style scoped>
*{
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
header {
  width: 100%;
  height: 5rem;
  background-color: rgba(2, 101, 250, 0.805);
  display: flex;
  justify-content: center;
  align-items: center;
}

header h1 {
  color: white;
  margin: 0;
}
</style>