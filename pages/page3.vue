<template>
    <main class="bg-dodger-blue-50">
        <section class="max-w-screen-md mx-auto min-h-full flex flex-col-reverse md:flex-row-reverse justify-between">
            <article class="h-96 flex flex-row flex-1 items-center p-8">
                <div>
                    <h1 class="font-bold text-3xl text-dodger-blue-900">This is My NU Class!</h1>
                    <p>dsdsdsd</p>        
                </div>
            </article>
            <article class="flex-1 bg-cover bg-center" style="background-image: url('/page3_main.jpeg');">
                <div class="p-8 w-full h-96"></div>
            </article>
        </section>
    </main>
    <main class="grid grid-cols-1 sm:grid-cols-2 p-10 gap-8">
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/wd_class.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Web Development</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid 
                    cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/sp2.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Speaking VI</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/gm.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Grammar V</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/cp.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Computer Programming I</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt velit laboriosam beatae aliquid cumque itaque, repellat nemo incidunt natus repellendus porro magni maxime dolor officia labore possimus? Perspiciatis, voluptatibus magni.</p>
            </div>
        </div>
    </main>
</template>
<script setup>
useHead({
    title: "My Study Page",
    meta:[
        {name: 'description', content:'My Study Page'}
    ]
})
</script>