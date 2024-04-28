<template>
    <main class="bg-dodger-blue-50">
        <section class="max-w-screen-md mx-auto min-h-full flex flex-col-reverse md:flex-row-reverse justify-between">
            <article class="h-96 flex flex-row flex-1 items-center p-8">
                <div>
                    <span class="font-bold text-4xl text-dodger-blue-900">
                        This is
                    </span>
                    <span class="font-bold text-4xl text-blue-800">
                        My NU Life
                    </span> 
                    <p>dsdsdsd</p>        
                </div>
            </article>
            <article class="flex-1 bg-cover bg-center" style="background-image: url('/campus.jpeg');">
                <div class="p-8 w-full h-96"></div>
            </article>
        </section>
    </main>
    <main class="grid grid-cols-1 sm:grid-cols-2 p-10 gap-8">
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/basketball.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Shoes!</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid 
                    cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/picnic2.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Shoes!</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/International.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">International club</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/evening.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Shoes!</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
    </main>
</template>
<script setup>
useHead({
    title: "My NU Life Page",
    meta:[
        {name: 'description', content:'My NU Life Page'}
    ]
})
</script>