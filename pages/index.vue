<template>
  <div>
      <navbar />
      <sidebar />
      <contentComponent />
  </div>
</template>

<script>
import navbar from '../components/navbar/navbar';
import sidebar from '../components/sidebar/sidebar';
import contentComponent from '../components/content/content-component';

export default {
  components: {
    navbar,
    sidebar,
    contentComponent
  }
}
</script>

