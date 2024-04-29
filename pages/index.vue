<template>
    <div class="bg-cover min-h-full bg-Top" style="background-image: url('/HP.png')">
        <div class="bg-white bg-opacity-30">
            <Hero/>
        </div>
    </div>
    <div class="py-20">
        <Chat/>
    </div>  
</template>
<script setup>
useHead({
    title: "Home Page",
    meta:[
        {name: 'description', content:'Home Page'}
    ]
})
</script>