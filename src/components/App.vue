<template>
  <ul v-for="resource in storedResources" :key="resource.id">
    {{
      resource.title
    }}
  </ul>
</template>

<script>
export default {
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          title: 'Offial Guide',
          descriptio: 'The official Vue JS documentation',
          link: 'https://vuejs.org'
        },
        {
          id: 'google',
          title: 'Google',
          descriptio: 'The official Google searchpage',
          link: 'https://google.com'
        }
      ]
    };
  }
};
</script>

<style></style>
