<template>
  <div class="slidev-layout cover" :style="style">
    <img
      src="/backgrounds/bg-cover.png"
      class="background"
    />
    <div class="main-content my-auto w-full">
      <slot />
    </div>
  </div>
</template>
