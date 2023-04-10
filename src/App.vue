<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="min-w-screen min-h-screen bg-gray-200 flex items-center justify-center px-5 py-5">
    <div class="rounded-lg shadow-xl bg-gray-900 text-white" style="width:450px;">
        <div class="border-b border-gray-800 px-8 py-3">
            <div class="inline-block w-3 h-3 mr-2 rounded-full bg-red-500"></div><div class="inline-block w-3 h-3 mr-2 rounded-full bg-yellow-300"></div><div class="inline-block w-3 h-3 mr-2 rounded-full bg-green-400"></div>
        </div>
        <div class="px-8 py-6">
          <div class="pl-28 pb-3">
            <img class="h-auto max-w-full inline-block w-40 h-40 rounded-full" src="photo.jpg" width="64" height="64" alt="User 01" />
          </div>

            <p><em class="text-blue-400">const</em> <span class="text-green-400">aboutMe</span> <span class="text-pink-500">=</span> <em class="text-blue-400">function</em>() {</p>
            <p>&nbsp;&nbsp;<span class="text-pink-500">return</span> {</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;name: <span class="text-yellow-300">'Ameerah'</span>,</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;position: <span class="text-yellow-300">'Web Developer'</span>,</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;course: <span class="text-yellow-300">'Level 5 Diploma in Web Development'</span>,</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;school: <span class="text-yellow-300">'Politeknik Brunei'</span>,</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;hobby: <span class="text-yellow-300">'Read and collect books'</span></p>
            <p>&nbsp;&nbsp;}</p>
            <p>}</p>
        </div>
    </div>
</div>
</template>

<!-- <style scoped>
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
</style> -->
