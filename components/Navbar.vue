
<template>
  <nav class="mb-5 sticky top-0 bg-stone-950/80 z-10">
    <div class="relative mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 flex h-16 items-center justify-between">
      <div class="flex items-center justify-center sm:items-stretch sm:justify-start">
        <div class="flex flex-shrink-0 items-center">
          <router-link to="/">
            <img class="h-8 w-auto" src="../assets/img/logo.svg" alt="Pangit" />
          </router-link>
        </div>
      </div>
      <div class="hidden lg:block">
        <div class="flex mx-auto space-x-4">
          <router-link to="/" class="uppercase px-3 py-2 text-sm font-medium text-orange-100 hover:text-yellow-300 flex">Главная</router-link>
          <router-link to="#about" class="uppercase px-3 py-2 text-sm font-medium text-orange-100 hover:text-yellow-300 flex">Об игре</router-link>
          <router-link to="#dev" class="uppercase px-3 py-2 text-sm font-medium text-orange-100 hover:text-yellow-300 flex">Социальные сети</router-link>
        </div>
      </div>
      <div class="flex items-center sm:static sm:ml-6">
        <div class="hidden lg:block relative ml-3">
          <router-link to="#shops" class="relative flex font-bold uppercase bg-yellow-300 text-yellow-900 text-sm px-5 py-2 hover:bg-yellow-400">
            Перейти к игре
          </router-link>
        </div>

        <div class="relative inline-block text-left lg:hidden">
          <button type="button" class="relative inline-flex items-center justify-center p-2 text-stone-50 hover:bg-yellow-400 hover:text-yellow-900 focus:outline-none" id="dropdownDefaultButton" data-dropdown-toggle="dropdown">
            <span class="absolute -inset-0.5"></span>
            <span class="sr-only">Открыть меню</span>

            <svg class="block h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"/>
            </svg>

            <svg class="hidden h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
              <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
            </svg>
          </button>

          <div id="dropdown" class="z-10 hidden border-2 border-stone-600 shadow w-44 bg-zinc-800" >
            <ul class="text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownDefaultButton" >
              <li> 
                <router-link to="/" class="block uppercase px-3 py-2 text-sm font-medium text-yellow-300">Главная</router-link>
              </li>
              <li>
                <router-link to="#about" class="block uppercase px-3 py-2 text-sm font-medium text-orange-100" >Об игре</router-link>
              </li>
              <li>
                <router-link to="#dev" class="block uppercase px-3 py-2 text-sm font-medium text-orange-100">Социальные сети</router-link>
              </li>
              <li>
                <router-link to="#shops" class="block font-bold uppercase bg-yellow-500 text-yellow-900 text-sm px-5 py-2 hover:bg-yellow-400">Перейти к игре</router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>