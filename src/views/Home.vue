<template>
  <div class="container">
    <div class="row">
      <Suggestions />
    </div>
    <div class="row">
    <div class="col-1">
    </div>
    <div class="col-7"> 

      <InstagramCard />

    </div>
    <div class="col-3">
      <Storycard />
    </div>
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
import InstagramCard from '@/components/InstagramCard.vue'
import Storycard from '@/components/Storycard.vue'
import Suggestions from '@/components/Suggestions.vue'

export default {
  name: 'home',
  components: {
    InstagramCard,
    Storycard,
    Suggestions
  }
}
</script>



<style lang="scss">

  .card {
    margin-bottom: 20px;
  }
</style>