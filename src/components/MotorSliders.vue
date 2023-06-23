
<script>
import { VSlider } from 'vuetify/lib/components';

export default {
  name: 'MotorSliders',
  components: {
    VSlider,
  },
  data() {
    return {
      leftMotorValue: 0,
      rightMotorValue: 0,
    };
  },
};
</script>

<template>
  <v-app>
    <v-card>
      <div class="motor-sliders">
        <div class="slider">
          <label>Left Motor</label>
          <v-slider v-model="leftMotorValue" :thumb-label="leftMotorValue" direction="vertical"></v-slider>
        </div>
        <div class="slider">
          <label>Right Motor</label>
          <v-slider v-model="rightMotorValue" min="0" max="100" :thumb-label="rightMotorValue" direction="vertical"></v-slider>
        </div>
      </div>
    </v-card>
  </v-app>
</template>


<style scoped>
.motor-sliders {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin-top: 20px;
}

.slider {
  margin-bottom: 10px;
  width: 45%; /* Adjust the width as per your preference */
}

label {
  font-size: 18px;
}
</style>
