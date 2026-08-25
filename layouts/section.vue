<template>
  <div class="slidev-layout section" :style="style">
    <img
      src="/backgrounds/bg-section.png"
      class="background"
    />
    <div class="main-content my-auto w-full">
      <slot />
    </div>
  </div>
</template>
