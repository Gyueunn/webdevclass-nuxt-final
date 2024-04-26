<template>
    <div 
    class="rounded-xl border border-gray-300 p-4 flex-1"
    :class="`bg-${color}-800 text-${color}-100`"
    >
    <div class="font-bold text-3xl">{{ title }}</div>
        <slot/> {{ color }}
        <!-- <div class="bg-sky-800 text-sky-100"></div> -->
        <!-- <div class="bg-amber-800 text-amber-100"></div> -->
        <!-- <div class="bg-indigo-800 text-indigo-100"></div> -->
        <!-- <div class="bg-blue-800 text-blue-100"></div> -->
    </div>
</template>
<script setup>
const props = defineProps({
    color: {
        default: "blue",
        required: true
    },
    title: {
        default: ""
    }
})
</script>