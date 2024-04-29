<template>
    <footer class="mt-28 bg-slate-50 dark:bg-black">
  <div
    class="container mx-auto flex flex-col items-start space-y-12 px-8 pb-8 pt-12 md:flex-row md:space-y-0 md:space-x-12 md:px-12"
  >
    <div
      class="flex w-full flex-col space-y-4 text-center md:w-2/6 md:text-left"
    >
      <div class="w-full text-lg font-extrabold md:w-fit md:text-left">
        <nuxt-link to="/">
            <span class="dark:text-slate-400">My </span>
            <span class="text-blue-700">NU </span>
            <span class="dark:text-slate-400">Life</span>
        </nuxt-link>
      </div>
      <p class="text-sm text-slate-600">
        This web contains records of my exchange student life. Please watch the exchange student's journey with interest.
      </p>
    </div>
    <div class="w-full text-center text-slate-600 md:w-1/6 md:text-left">
      <div class="text-sm font-semibold">
        <nuxt-link to="/">Home</nuxt-link>
      </div>
    </div>
    <div class="w-full text-center text-slate-600 md:w-1/6 md:text-left">
      <div class="text-sm font-semibold">
        <nuxt-link to="/page1">NU Life</nuxt-link>
      </div>
    </div>
    <div class="w-full text-center text-slate-600 md:w-1/6 md:text-left">
      <div class="text-sm font-semibold">
        <nuxt-link to="/page2">Travels</nuxt-link>
      </div>
    </div>
    <div class="w-full text-center text-slate-600 md:w-1/6 md:text-left">
      <div class="text-sm font-semibold text-slate-600">
        <nuxt-link to="/page3">Courses</nuxt-link>
      </div>
    </div>
    <div class="w-full text-center text-slate-600 md:w-1/5 md:text-left">
      <div class="text-sm font-semibold text-slate-600">
        <nuxt-link to="/page4">Projects</nuxt-link>
      </div>
    </div>
  </div>
  <div
    class="container mx-auto border-t border-slate-200 p-8 text-center text-sm text-slate-600 dark:border-slate-900 md:flex-row md:px-12"
  >
    ©2024 MyNULife. All rights reserved.
  </div>
</footer>
</template>

