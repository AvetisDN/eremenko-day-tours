<script setup></script>

<template>
  <div class="day-tours">
    <div class="image-1">
      <img src="/images/1.png" alt="" />
      <div class="overlay">
        <h4>1 Day</h4>
        <p>Pakistan Monument, Lok Virsa & Margalla Hills of Islamabad Tour</p>
      </div>
    </div>
    <div class="image-2">
      <img src="/images/2.png" alt="" />
      <div class="overlay">
        <h4>2 Day</h4>
        <p>Pakistan Monument, Lok Virsa & Margalla Hills of Islamabad Tour</p>
      </div>
    </div>
    <div class="image-3">
      <img src="/images/3.png" alt="" />
      <div class="overlay">
        <h4>3 Day</h4>
        <p>Pakistan Monument, Lok Virsa & Margalla Hills of Islamabad Tour</p>
      </div>
    </div>
    <div class="image-4">
      <img src="/images/4.png" alt="" />
      <div class="overlay">
        <h4>4 Day</h4>
        <p>Pakistan Monument, Lok Virsa & Margalla Hills of Islamabad Tour</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.day-tours {
  @apply grid grid-cols-4 grid-rows-2 gap-5;
}
.day-tours > div {
  @apply relative  rounded-[20px] overflow-hidden;
  box-shadow: 2px 2px 2px 2px rgba(0, 0, 0, 0.25);
}
.image-1 {
  grid-column: 1 / 3;
  grid-row: 1 / 3;
}
.image-2 {
  grid-column: 3 / 5;
}
img {
  @apply w-full h-full object-cover;
}

.overlay {
  @apply absolute left-0 bottom-0 w-full h-full text-white p-6 bg-gradient-to-b from-[rgba(0,0,0,0)] to-[rgba(0,0,0,0.6)] flex flex-col justify-end gap-4;
}
.overlay h4 {
  @apply text-lg;
}
.overlay p {
  @apply text-xl;
}
</style>
