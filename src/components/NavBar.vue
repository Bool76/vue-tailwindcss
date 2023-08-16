<!--./src/components/NavBar.vue -->

<template>
    <header class="p-6 bg-white shadow-md">
      <nav>
        <ul class="flex justify-end text-lg">
          <li class="hover:text-blue-500 cursor-pointer px-4">
            <a>Home</a>
          </li>
          <li class="hover:text-blue-500 cursor-pointer px-4">
            <a to="/blog">Blog</a>
          </li>
          <li class="hover:text-blue-500 cursor-pointer px-4">
            <a to="about">About</a>
          </li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: "NavBar",
  };
  </script>