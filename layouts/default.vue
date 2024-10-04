<script setup>
import Navbar from '~/components/Navbar'
import Footer from '~/components/Footer'
import { onMounted } from 'vue'
import { useFlowbite } from '~/composables/useFlowbite'

// initialize components based on data attribute selectors
onMounted(() => {
    useFlowbite(() => {
        initFlowbite();
    })
}); 
useHead({
  title: 'PANGIT',
  meta: [
    { name: 'description', content: 'Компьютерная игра в жанре экшена, приключения от 3-го лица в открытом миром' }
  ],
  bodyAttrs: {
    class: 'bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-stone-800 to-stone-950 overflow-x-hidden scroll-smooth h-full'
  },
  link: [
    { rel: 'icon', type: 'image/png', href: '../assets/img/favicon.svg' }
  ],
  script: [ { innerHTML: 'console.log(\'Hello world\')' } ]
});

</script>

<template>
    <main>
        <Navbar />
        <slot />
        <Footer />
    </main>
</template>

<style scoped>

</style>