<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <button @click="goToDatbook" type="button" class="btn btn-secondary">
      secondary
    </button>
    <button @click="goToDatbook" type="button" class="btn btn-success">
      success
    </button>
    <button @click="goToDatbook" type="button" class="btn btn-primary">
      primary
    </button>
  </div>
</template>

<script>
export default {
  methods: {
    goToDatbook() {
      this.$router.push({ name: "no-entry" });
    },
  },
};
</script>
