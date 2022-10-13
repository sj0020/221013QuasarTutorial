<template>
  <div>
    <h3>Hello from Sarah</h3>
    <q-banner class="bg-primary text-white">
      Unfortunately, the credit card did not go through, please try again.
      <template v-slot:action>
        <q-btn flat color="white" label="Dismiss" />
        <q-btn flat color="white" label="Update Credit Card" />
      </template>
    </q-banner>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

</style>