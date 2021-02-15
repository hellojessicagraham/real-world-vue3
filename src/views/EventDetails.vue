<template>
  <div class="event-details">
    <h1>{{ event.title }}</h1>
    <span>{{ event.time }} on {{ event.date }} @ {{ event.location }}</span>
    <p>{{ event.description }}</p>
  </div>
</template>

<script>
export default {
  data() {
      return {
          event: null
      }
  },
  created () {
      // fetch event by id
      // set local data
  }
}
</script>