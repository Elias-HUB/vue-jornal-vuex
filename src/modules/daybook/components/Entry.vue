<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <!-- Titulo -->
    <div class="entry-title d-flex">
      <span class="text-success fs-3 fw-bold">15</span>
      <span class="mx-1 fs-4">Julio</span>
      <span class="mx-2 fs-5 fw-light">2021, jueves</span>
    </div>
    <div class="entry-description">
      Aliqua aliqua ea minim magna sunt incididunt anim adipisicing eiusmod
      dolore ex. Mollit ex incididunt cupidatat non deserunt sint exercitation
      adipisicing nostrud aute amet nisi cupidatat ullamco. Commodo irure quis
      ad amet consectetur cupidatat velit. Cupidatat laboris consectetur laborum
      velit Lorem aute deserunt commodo tempor occaecat elit commodo ullamco.
      Incididunt nostrud adipisicing aliqua ut deserunt laborum.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;
  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
    font-size: 12px;
  }
}
</style>
