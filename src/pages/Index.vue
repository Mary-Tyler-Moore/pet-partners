<template>
  <q-page class="flex flex-center">
    <q-card class="my-card">
      <img src="https://github.com/Mary-Tyler-Moore/readme-gifs/blob/master/pet-partners/Mary-Tyler-Moore.png?raw=true" />

      <q-card-section>
        <div class="text-h6">We have the Baby Yoda</div>
        <div class="text-subtitle2">by Mary-Tyler-Moore</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ lorem }}
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
    }
  }
}
</script>

<style lang="scss" scoped>
.my-card {
  width: 100%;
  max-width: 800px;
}  
</style>
