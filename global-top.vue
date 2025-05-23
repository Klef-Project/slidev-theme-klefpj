<template>
  <footer class="absolute bottom-0 left-0 right-0 p-0 p-l-2 bg-sky-200 flex align-center">
    <p class="text-s p-0 m-0">{{ $slidev.configs.title }}</p>
    <div class="grow-36" />
    <div class="flex p-0 px-2 align-center">
      <carbon:logo-github />
      <p class="text-s p-0 m-0">{{ $slidev.configs.file }}</p>
      <p class="text-s p-0 m-0 pl-4"> # {{ $slidev.nav.currentPage }}</p>
    </div>
  </footer>
</template>

<style>
  .align-center {
  align-items: center;
  }
</style>
