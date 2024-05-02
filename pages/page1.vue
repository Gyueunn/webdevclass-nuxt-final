<template>
    <main class="bg-dodger-blue-50">
        <section class="max-w-screen-md mx-auto min-h-full flex flex-col-reverse md:flex-row-reverse justify-between">
            <article class="h-96 flex flex-row flex-1 items-center p-8">
                <div>
                    <p class="font-bold text-4xl text-dodger-blue-900">
                        This is
                    </p>
                    <span class="font-bold text-4xl text-blue-800">
                        My NU Life
                    </span> 
                    <p>There are many new things I experienced through NU's campus life. It will be remembered as a good memory. I would like to introduce some memorable things from NU's life below.</p>        
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
                <h2 class="card-title">Basketball game</h2>
                <p>It was my first time watching a college basketball team play. It was so impressive that all of NU's gathered their hearts and cheered passionately, and I enjoyed the game so much.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/picnic2.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Picnic</h2>
                <p>It's hard to expect sunny weather with rain in Seattle. So having a picnic on New's spacious lawn on an unusually nice day was a really happy memory. The good music, friends, and delicious bagels were so perfect.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/International.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">International club</h2>
                <p>Through the activities of the international club, I was able to participate in the ICCB, share Korean food with other friends, and gain various experiences. Above all, I liked the fact that I was able to meet and make new friends of different nationalities.</p>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/evening.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">Evening</h2>
                <p>The evening is the biggest party in NU. The Museum of Pop Culture, where the party took place, was also a wonderful place. The most memorable moment was when I danced to an exciting song with my friends, leaving pictures in the photo booth.</p>
            </div>
        </div>
    </main>
</template>
<script setup>
useHead({
    title: "NU Life Page",
    meta:[
        {name: 'description', content:'My NU Life Page'}
    ]
})
</script>