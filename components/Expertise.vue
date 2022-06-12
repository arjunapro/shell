<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <li class="flex items-center">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm mr-1"></Html>
          Html<br>
          7+ years
        </li>

        <li class="flex items-center">
          <Css class="h-10 w-10 rounded-sm drop-shadow-sm mr-1"></Css>
          Css<br>
          7+ years
        </li>
        <li class="flex items-center">
          <Javascript class="h-10 w-10 mr-1"></Javascript>
          Javascript<br>
          7+ years
        </li>

        <li class="flex items-center">
          <Vuejs class="h-10 w-10 mr-1"></Vuejs>
          Vue.js<br>
          5+ years
        </li>
        <li class="flex items-center">
          <Bootstrap class="h-10 w-10 mr-1"></Bootstrap>
          Bootstrap<br>
          4+ years
        </li>
        <li class="flex items-center">
          <Nuxt class="h-10 w-10 mr-1"></Nuxt>
          Nuxt.js<br>
          2+ years
        </li>
        <li class="flex items-center">
          <TailwindCss class="h-10 w-10 mr-1"></TailwindCss>
          Tailwind Css<br>
          2+ years
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <PHP class="h-10 w-10 mr-1"></PHP>
          PHP<br>
          7+ years
        </li>
        <li class="flex items-center">
          <Mysql class="h-10 w-10 mr-1"></Mysql>
          Mysql<br>
          7+ years
        </li>
        <li class="flex items-center">
          <Laravel class="h-10 w-10 mr-1"></Laravel>
          Laravel<br>
          5+ years
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";
import Css from "../assets/devicon/css.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import TailwindCss from "../assets/devicon/tailwindcss.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Bootstrap from "../assets/devicon/bootstrap.svg?inline";
import Laravel from "../assets/devicon/laravel.svg?inline";
import PHP from "../assets/devicon/php.svg?inline";
import Mysql from "../assets/devicon/mysql.svg?inline";
import Node from "../assets/devicon/node.svg?inline";

export default {
  components: {
    Javascript,
    Html,
    Css,
    Bootstrap,
    Vuejs,
    TailwindCss,
    Nuxt,
    Laravel,
    Node,
    PHP,
    Mysql,
  },
};
</script>
