<template>
  <div class="events">
    <h1>Event Listing</h1>
    <EventCard />
    <BaseIcon />
  </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'

export default {
  components: {
    EventCard
  }
}
</script>

<style scoped>
.events {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
