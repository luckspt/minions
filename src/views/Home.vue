<script setup lang="ts">
import bobImage from '../assets/bob.jpg';
</script>

<template>
    <div id="container">
        <div id="subcontainer">
            <h1>Minions</h1>
            <img :src="bobImage" />
        </div>
    </div>
</template>

<style scoped>
#container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 90vh;
}
#subcontainer {
  display: flex;
  flex-direction: column;
  align-items: center;
}
img {
  width: 100%;
  max-width: max(70%, 700px);
  border-radius: 10px;
}
</style>