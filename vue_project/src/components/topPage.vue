<template>
  <div>
    <div class="top">
      <addcard></addcard>
    </div>
  </div>
</template>

<script>
import addcard from './addCard'

export default {
  components: {
    addcard
  }
}
</script>

<style>
  .top {
    background-image: linear-gradient(180deg, #cdcecf, #577080);
    height: 950px;
  }
</style>
