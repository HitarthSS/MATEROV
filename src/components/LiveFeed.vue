<template>
  <div class="live-feed-container">
    <div class="live-feed">
      <h1>Live Feed</h1>
      <!-- Add any additional content here -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'LiveFeed',
};
</script>

<style scoped>
.live-feed-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 70%;
  height: 50;
  margin: 0 auto; /* Added to center the container horizontally */
  border: 2px solid #ccc;
  border-radius: 10px;
}

.live-feed {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
}

h1 {
  font-size: 24px;
  margin-bottom: 10px;
}
</style>
