<template>
   <header class="sticky top-0 bg-weather-primary shadow-lg">
    <nav class=" container flex flex-col gap-4 sm:flex-row justify-between items-center text-white py-6">
        <router-link :to="{name:'home'}">
            <div class="flex items-center gap-3">
            <i class="fa-solid fa-sun text-2xl text-white"></i>
                <p class="text-2xl">The Local Weather</p>
            </div>

        </router-link>
        
        <div class="flex gap-3 items-center">
            <i class="fa-solid fa-circle-info
             text-2xl hover:text-weather-secondary duration-150 cursor-pointer"></i>

             <i class="fa-solid fa-plus text-2xl hover:text-weather-secondary duration-150 cursor-pointer"></i>
        </div>
    </nav>
   </header>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>