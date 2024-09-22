<template>
  <div class="vite">
    <micro-app
      :name="name"
      :url="url"
      iframe
    ></micro-app>
  </div>
</template>

<script>
export default {
  name: 'vite-sub-app',
  data () {
    return {
      name: 'vite-sub-app',
      url: 'http://localhost:5173/'
    }
  }
}
</script>
