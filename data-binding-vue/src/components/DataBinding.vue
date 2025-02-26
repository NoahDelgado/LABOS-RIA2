<template>
  <div id="name-container">
    <p>{{ name }}</p>
  </div>
  <ul>
    <li v-for="item in items" :key="item">{{ item }}</li>
  </ul>
</template>

<script>
export default {
  data() {
    return {
      name: 'John Doe',
      items: ['Item 1', 'Item 2', 'Item 3', 'Item 4']
    };
  }
};
</script>
