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
</template>
<script setup>
useHead({
    title: "My Home Page",
    meta:[
        {name: 'description', content:'My Home Page'}
    ]
})
</script>