<template>
  <main
    class="kasi-background min-h-screen p-10 justify-center font-sans"
  >
    <div class="backdrop bg-white container mx-auto rounded-xl p-10">
      <div class="kasi-headline">
        <h1 class="text-4xl">Welcome to the <span class="text-red-500 text-5xl font-bold">K</span>as<span class="text-red-500 text-5xl font-bold">I</span></h1>
      </div>
      <div class="kasi-content flex flex-row">
        <KasiVideo />
        <KasiChat />
      </div>
    </div>
  </main>
</template>

<script setup>
  useHead({
    title: 'This is the KasI!',
    meta: [
      { name: 'description', content: "This is probably the closes we'll ever get to General Artificial Intelligence" }
    ]
  })
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Comic+Neue:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');

.kasi-background {
  background-image: url('/blue-banana-pattern.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>