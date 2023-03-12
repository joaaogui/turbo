<script setup></script>

<template>
  <div class="top-bar">
    <a href="https://www.linkedin.com/in/joaaogui/"
      ><img src="@/assets/linkedin.png"
    /></a>
    <a href="https://github.com/joaaogui/"><img src="@/assets/github.png" /></a>
    <a href="mailto:joaaogui@gmail.com"
      ><img src="@/assets/mail-black.png"
    /></a>
    <a href="https://github.com/joaaogui/j.me/"
      ><img src="@/assets/source-code.png"
    /></a>
  </div>
</template>

<style scoped lang="scss">
.top-bar {
  @apply text-4xl bg-gray-100 w-full flex flex-row justify-end gap-4 h-14  p-2;
  a {
    img {
      @apply h-full hover:opacity-60;
    }
  }
}
</style>
