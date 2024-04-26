<template>
    <section class="container mx-auto px-8 py-28 sm:px-12 ">
        <div class="text-white text-center">
            <h1 class="sm:mb-18 w-full text-center p-20 text-4xl sm:text-6xl font-extrabold pt-3 dark:text-slate-50 sm:mx-auto sm:w-4/5">
                Hello, Let me introduce
                <p class="text-blue-800 text-5xl sm:text-7xl"> My Exchange Student</p>
                Life in NU!!
            </h1>
       </div>
    <div class="grid grid-cols-2 gap-4 md:grid-cols-4">
        <nuxt-link to="/page1">  
        <div
        class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
        >
        <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="h-8 w-8"
        >
            <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 21h18M3 10h18M5 6l7-3l7 3M4 10v11m16-11v11M8 14v3m4-3v3m4-3v3"
            ></path>
        </svg>
        <div class="mt-3 text-sm font-semibold">About NU Life</div>
        </div>
        </nuxt-link>
        <nuxt-link to="/page2">  
        <div
        class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
        >
        <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="h-8 w-8"
        >
            <g
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            >
            <path
                d="M9 5H7a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-2"
            ></path>
            <path
                d="M9 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v0a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2zm5 6h-2.5a1.5 1.5 0 0 0 0 3h1a1.5 1.5 0 0 1 0 3H10m2 0v1m0-8v1"
            ></path>
            </g>
        </svg>
        <div class="mt-3 text-sm font-semibold">About Travel in Seattle</div>
        </div>
        </nuxt-link>
        <nuxt-link to="/page3">  
        <div
        class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
        >
        <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="h-8 w-8"
        >
            <g
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            >
            <path d="M14 3v4a1 1 0 0 0 1 1h4"></path>
            <path
                d="M17 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7l5 5v11a2 2 0 0 1-2 2zM9 7h1m-1 6h6m-2 4h2"
            ></path>
            </g>
        </svg>
        <div class="mt-3 text-sm font-semibold">About Study</div>
        </div>
        </nuxt-link>
        <nuxt-link to="/page4">
        <div
        class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
        >
        <svg
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
            width="1.2em"
            height="1.2em"
            class="h-8 w-8"
        >
            <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 8a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm0 2h18M7 15h.01M11 15h2"
            ></path>
        </svg>
        <div class="mt-3 text-sm font-semibold">Projects related to Major</div>
        </div>
        </nuxt-link>
    </div>
    </section>
</template>