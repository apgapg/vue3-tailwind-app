<template>
  <div class="bg-purple-500 min-h-screen text-white px-16 flex flex-col justify-around py-4">
    <div>
      <div class="text-white text-xl text-center">This is a Vue3 + Tailwindcss demo</div>
      <div class="text-white text-xl pt-4 text-center">Made with ❤️ by Ayush P Gupta</div>
    </div>

    <div class="flex justify-around">
      <div class="pt-8">
        <div>1. Install Vue CLI</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">npm install -g @vue/cli
# OR
yarn global add @vue/cli</code></pre>
      </div>
      <div class="pt-8">
        <div>2. Create Vue Project</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">vue create my-app</code></pre>
      </div>
      <div class="pt-8">
        <div>3. Add Tailwindcss (npm:@tailwindcss/postcss7-compat)</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">vue add tailwindcss</code></pre>
      </div>
    </div>
    <div class="flex justify-around">
      <div class="pt-8">
        <div>4. Generate config file</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">npx tailwindcss init -p</code></pre>
      </div>
      <div class="pt-8">
        <div>5. Import tailwindcss in main.js</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">import '@/assets/tailwind.css'
</code></pre>
      </div>
      <div class="pt-8">
        <div>6. Check if Tailwind works</div>
        <pre class="bg-gray-800 w-min text-start p-8 mt-4 rounded shadow-xl"><code class="text-start">npm run serve

// Try adding a class to a div
// like bg-red-500</code></pre>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
