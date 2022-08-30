<template>
  <div class="bg-">
    <div
      class="phone-width bg-white container-fluid min-vh-100 d-flex flex-column"
    >
      <Nuxt />
    </div>
  </div>
</template>
<style>
.phone-width {
  max-width: 390px;
  width: 100%;
  overflow: hidden;
}
input {
  accent-color: #3f37c9;
}
</style>
<script>
export default {};
</script>
