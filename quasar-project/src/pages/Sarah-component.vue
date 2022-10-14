<template>
  <div>
    <h3>Hello from Sarah</h3>
    
    <div id="chip">
      <div class="q-pa-md q-gutter-md">
    <div>
      <q-chip icon="event">Add to calendar</q-chip>
      <q-chip icon="bookmark">Bookmark</q-chip>
      <q-chip icon="alarm" label="Set alarm" />
      <q-chip class="glossy" icon="directions">Get directions</q-chip>
    </div>
    <div>
      <q-chip color="primary" text-color="white" icon="event">
        Add to calendar
      </q-chip>
      <q-chip color="teal" text-color="white" icon="bookmark">
        Bookmark
      </q-chip>
      <q-chip class="glossy" color="orange" text-color="white" icon-right="star">
        Star
      </q-chip>
      <q-chip color="red" text-color="white" icon="alarm" label="Set alarm" />
      <q-chip color="deep-orange" text-color="white" icon="directions">
        Get directions
      </q-chip>
      <q-chip>
        <q-avatar icon="bookmark" color="red" text-color="white" />
        Bookmark
      </q-chip>
      <q-chip>
        <q-avatar color="red" text-color="white">50</q-avatar>
        Emails
      </q-chip>
      <q-chip>
        <q-avatar>
          <img src="https://cdn.quasar.dev/img/avatar5.jpg">
        </q-avatar>
        John
      </q-chip>
    </div>
  </div>
    </div>
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