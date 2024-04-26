<template>
    <div class="bg-cover bg-Top" style="background-image: url('/HP.png')">
        <div class="bg-black bg-opacity-50">
            <Hero/>
        </div>
    </div>
    <div class="py-20">
        <Chat/>
    </div>  
</template>
<script setup>
useHead({
    title: "My Home Page",
    meta:[
        {name: 'description', content:'Hi'}
    ]
})
</script>