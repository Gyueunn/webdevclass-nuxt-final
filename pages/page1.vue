<template>
    <main class="flex flex-col gap-10 justify-between">
        <div class="bg-cover bg-bottom" style="background-image: url('/A.jpg')">
            <div class="bg-white bg-opacity-40"></div>
                NU Life
                <Bucket color="indigo" title="Indigo Bucket">
                    Bucket 1
                </Bucket>
                <Bucket color="amber" title="Amber Bucket">
                    Bucket 2
                </Bucket>
                <Bucket color="sky" title="Sky Bucket">
                    Bucket 3
                </Bucket>
        </div>
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