<script setup></script>

<template>
  <div
    class="
      w-full
      h-full
      flex flex-column
      align-items-center
      justify-content-center
    "
  >
    <router-view></router-view>
  </div>
</template>

<style>
body {
  color: var(--text-color);
  font-family: var(--font-family);
}
#reload-toast .p-toast-message .p-toast-message-content {
  justify-content: center !important;
}
</style>
