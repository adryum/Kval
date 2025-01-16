<script setup>
import HelloWorld from './components/def/HelloWorld.vue'
import TheWelcome from './components/def/TheWelcome.vue'
import TextButton from "@/components/TextButton.vue";
</script>

<template>
  <header>
<!--    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />-->

<!--    <div class="wrapper">-->
<!--      <HelloWorld msg="You did it!" />-->
<!--    </div>-->
  </header>

  <main>
<!--    <TheWelcome />-->
    <TextButton text="button" :action="() => {console.log('asd')}"/>
  </main>
</template>

<style scoped>

</style>
