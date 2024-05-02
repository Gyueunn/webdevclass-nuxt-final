<template>
    <section class="bg-dodger-blue-50">
        <section class="max-w-screen-md mx-auto min-h-full flex flex-col-reverse md:flex-row-reverse justify-between">
            <article class="h-96 flex flex-row flex-1 items-center p-8">
                <div>
                    <span class="font-bold text-4xl text-blue-800">
                        My Courses
                    </span> 
                    <span class="font-bold text-4xl text-dodger-blue-900">
                        in NU
                    </span>
                    <p>These are the courses I took during my exchange period. I took two courses related to computer science, which is my major and two CELE courses for exchange students. These courses helped me improve my English and major skills.</p>        
                </div>
            </article>
            <article class="flex-1 bg-cover bg-center" style="background-image: url('/page3_main.jpeg');">
                <div class="p-8 w-full h-96"></div>
            </article>
        </section>
    </section>
    <section class="grid grid-cols-1 sm:grid-cols-2 p-10 gap-8">
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/wd_class.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">
                    Course Tittle: Web Development [BMGT 3543 / INTC 3543]
                </h2>
                <h2 class="card-title">
                    Instructor: Tim Mushen
                </h2>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/sp1.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">
                    Course Tittle: Speaking VI [LANG 0663]
                </h2>
                <h2 class="card-title">
                    Instructor: Lisa Kim
                </h2>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/gm.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">
                    Course Tittle: Grammar V [LANG 0523]
                </h2>
                <h2 class="card-title">
                    Instructor: Sara Wright
                </h2>
            </div>
        </div>
        <div class="card w-50 bg-base-100 shadow-xl">
            <figure><img src="/cp.jpeg"></figure>
            <div class="card-body">
                <h2 class="card-title">
                    Course Tittle: Computer Programming I [INTC 2083]
                </h2>
                <h2 class="card-title">
                    Instructor: Kevin Gallo
                </h2>
            </div>
        </div>
    </section>
</template>
<script setup>
useHead({
    title: "Courses Page",
    meta:[
        {name: 'description', content:'My Courses Page'}
    ]
})
</script>