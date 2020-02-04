<template>
  <div class="about">
    <h1>{{pageName}}</h1>
    <p>{{pageDesc}}</p>
  </div>
</template>

<script>


export default {
  data() {
    return {
      pageName: "about page",
      pageDesc :"lorem upsum"
    }
  },
  components: {
  }
};
</script>
