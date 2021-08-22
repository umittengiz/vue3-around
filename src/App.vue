<template>
  <div id="nav">
    <router-link :to="{ name: 'EventList' }">Events</router-link> |
    <router-link :to="{ name: 'EventDetails', params: { id: 123 } }"
      >Test Event</router-link
    >
  </div>
  <router-view />
</template>

<style></style>
