<template>
  <div class="bg-white">
    <div class="mx-auto max-w-7xl py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
      <div class="text-center">
        <h2 class="text-lg font-semibold text-indigo-600">Deutsche Sprache für alle</h2>
        <p class="mt-1 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl lg:text-6xl">Der Die Das</p>
        <p class="mx-auto mt-5 max-w-xl text-xl text-gray-500">Geben Sie die Substantive ein und wir sagen die Artikel</p>
      </div>
    </div>
  </div>



  <div class="bg-gray-50 pt-12 sm:pt-16">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
      <div class="mx-auto max-w-4xl text-center">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Trusted by developers from over 80 planets</h2>
        <p class="mt-3 text-xl text-gray-500 sm:mt-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellendus repellat laudantium.</p>
      </div>
    </div>
    <div class="mt-10 bg-white pb-12 sm:pb-16">
      <div class="relative">
        <div class="absolute inset-0 h-1/2 bg-gray-50" />
        <div class="relative mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
          <div class="mx-auto max-w-4xl">
            <dl class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-3">
              <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
                <dt class="order-2 mt-2 text-lg font-medium leading-6 text-gray-500">
                  <span class="material-symbols-outlined">male</span>
                </dt>
                <dd class="order-1 text-5xl font-bold tracking-tight text-indigo-600">Der</dd>
              </div>
              <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                <dt class="order-2 mt-2 text-lg font-medium leading-6 text-gray-500">
                  <span class="material-symbols-outlined">female</span>
                </dt>
                <dd class="order-1 text-5xl font-bold tracking-tight text-indigo-600">Die</dd>
              </div>
              <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                <dt class="order-2 mt-2 text-lg font-medium leading-6 text-gray-500">
                  <span class="material-symbols-outlined">
                    agender
                  </span>
                </dt>
                <dd class="order-1 text-5xl font-bold tracking-tight text-indigo-600">
                  Das
                </dd>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>


  <Input />









</template>


<script setup>
import { CheckIcon } from '@heroicons/vue/20/solid'
import Input from './Input.vue'



</script>