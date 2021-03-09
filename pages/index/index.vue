<template>
  <view>
    <!-- <web-view style="width: 100vw; height: 100vh;" src="/hybrid/html/index.html"></web-view> -->
    <unity src="/hybrid/html/Build/WebGL.json"  unityLoader="/hybrid/html/Build/UnityLoader.js"></unity>
  </view>
</template>

<script>
import Unity from 'vue-unity-webgl';
export default {
  components: {
    Unity
  },
  data() {
    return {
      title: 'Hello'
    };
  },
  onLoad() {},
  methods: {}
};
</script>

<style>
/* @media screen and (max-width: 640px) {
   #unity-container {
      display: none;
   } 
} */

</style>
