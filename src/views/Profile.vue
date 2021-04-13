<template>
  <div class="about">
    <h1>This is an profile page. My name is Hrvoje.</h1>

    <HelloWorld msg="Ovu smo komponentu iskoristili na dva mjesta." />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
