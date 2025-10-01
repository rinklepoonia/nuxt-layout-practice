<script setup>

</script>
<template>
    <div class="bg-[#001B3A] p-5   rounded-xl flex flex-col gap-3">
        <NuxtLink :to="obj.path" v-for="(obj, index) in SIDEBAR_DATA_LIST" :key="index" class="">
           
                <p class="text-white text-base font-medium text-center bg-[#1A9BFF] p-2 rounded-lg">{{ obj.label }}</p>
            
        </NuxtLink>
    </div>
</template>
<script setup>
</script>