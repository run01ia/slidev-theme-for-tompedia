<template>
  <div class="slidev-layout content" :style="style">
    <img
      src="/backgrounds/bg-content.png"
      class="background"
    />
    <div class="main-content my-auto w-full">
      <slot />
    </div>
  </div>
</template>
