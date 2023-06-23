<template>
  <div id="app">
    <MenuButton />
    <LiveFeed />
    <MotorSliders />
  </div>
</template>

<script>
import MenuButton from './components/MenuButton.vue';
import LiveFeed from './components/LiveFeed.vue';
import MotorSliders from './components/MotorSliders.vue';

export default {
  name: 'App',
  components: {
    MenuButton,
    LiveFeed,
    MotorSliders,
  },
};
</script>
