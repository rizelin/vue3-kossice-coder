<template>
  <div class="name">
    {{ name }}
  </div>
</template>

<script>
export default {
  setup() {
    const name = 'kossice Coder';
    return {
      name
    }
  }
}
</script>

<style>
.name {
  color: red;
}
</style>
