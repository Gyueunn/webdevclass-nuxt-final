<template>
    <footer class="bg-gray-200 border-t text-center border-gray-300 p-8">
        <div class="mb-6 text-lg">
            <nuxt-link to="/" class="roboto">Site Name</nuxt-link>
        </div>
        <nav class="flex flex-row justify-center gap-4">
            <nuxt-link to="/page1">Page 1</nuxt-link>
            <nuxt-link to="/page2">Page 2</nuxt-link>
            <nuxt-link to="/page3">Page 3</nuxt-link>
            <nuxt-link to="/page4">Page 4</nuxt-link>
        </nav>
        <div>
            <div class="btn">Hi</div>
        </div>
        <div>
            <nuxt-link to="/page4">  
                <button class="bg-sky-600 text-white px-6 py-2">Say Hi</button>
            </nuxt-link>
        </div>
        <div>
            <a href="https://microsoft.com">
                <button class="bg-sky-600 text-white px-6 py-2">Go to Microsoft</button>
            </a>
        </div>
    </footer>
</template>