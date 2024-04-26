<template>
    Travel
    <main class="flex flex-col gap-10 justify-between">
        <Bucket color="indigo" title="Indigo Bucket">
            Bucket 1
        </Bucket>
        <Bucket color="amber" title="Amber Bucket">
            Bucket 2
        </Bucket>
        <Bucket color="sky" title="Sky Bucket">
            Bucket 3
        </Bucket>
    </main>
        <!-- <main class="bg-cover bg-top h-full" style="background-image: url('/campus.jpeg')">
        <div class="bg-black bg-opacity-40">
            <Hero/>
            <main class="flex flex-col gap-10 justify-between">
        <Bucket color="indigo" title="Indigo Bucket">
            Bucket 1
        </Bucket>
        <Bucket color="amber" title="Amber Bucket">
            Bucket 2
        </Bucket>
        <Bucket color="sky" title="Sky Bucket">
            Bucket 3
        </Bucket>
    </main>
        </div>
    </main> -->
</template>
<script setup>
useHead({
    title: "My Travel Page",
    meta:[
        {name: 'description', content:'My Travel Page'}
    ]
})
</script>