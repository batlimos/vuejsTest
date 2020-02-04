<template>
  <div class="about">
    <h1>{{pagename}}</h1>
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
