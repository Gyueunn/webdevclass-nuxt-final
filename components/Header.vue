<template>
    <header class="bg-dodger-blue-200 py-4">
        <main class="container mx-auto items-center flex flex-col md:flex-row justify-between gap-4 text-center">
            <div class="flex flex-row items-center text-lg font-bold md:text-left gap-3">
                <img class="h-10" src="https://www.northwestu.edu/assets/svgs/nu-shield-color.svg">
                <nuxt-link to="/">
                    <span class="dark:text-slate-400">My </span>
                    <span class="text-blue-700">NU </span>
                    <span class="dark:text-slate-400">Life</span>
                </nuxt-link>
            </div>
            <nav class="flex flex-col md:flex-row font-bold justify-end gap-6 md:text-right">
                <a href="/">Home</a>
                <a href="/page1">NU Life</a>
                <a href="/page2">Travels</a>
                <a href="/page3">Courses</a>
                <a href="/page4">Projects</a>
            </nav>
        </main>
    </header>
</template>