<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex flex-col w-screen h-screen bg-slate-600 text-3xl pl-10 px-5 py-10 font-semibold font-mono ">
    <div class="flex flex-col p-3 bg-slate-500 w-fit rounded-2xl shadow-md">
      <!---user icon plus subject combo-->
      <div class="flex gap-5 items-center">
        <div class="w-6 h-6 rounded-full bg-neutral-300"></div>
        <span class="text-l font-semibold">NUMBERS</span>
      </div>
       <!--brief description-->
      <div class="flex max-w-xs">
       <p class="text-s">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem vero quos provident officia suscipit ad doloribus atque dolor similique excepturi. Voluptatibus architecto, distinctio maxime unde iste temporibus tempora. Natus, ipsum?</p>
      </div>
    </div>
    <span><li>1</li></span>
    <span><li>2</li></span>
    <span><li>3</li></span>
    <span><li>4</li></span>
    <span><li>5</li></span>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
