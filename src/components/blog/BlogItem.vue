<script setup lang="ts">
defineProps<{
    title: string
    content: string
}>()
</script>

<template>
    <section class="text-gray-600 body-font overflow-hidden">
        <div class="container px-5 py-24 mx-auto">
            <div class="flex flex-wrap -m-12">
                <div class="p-12 md:w-1/2 flex flex-col items-start">
                    <span
                        class="inline-block py-1 px-2 rounded bg-red-50 text-red-500 text-xs font-medium tracking-widest"
                    >CATEGORY</span>
                    <h2
                        class="sm:text-3xl text-2xl title-font font-medium text-gray-900 mt-4 mb-4"
                    >{{ title }}</h2>
                    <p class="leading-relaxed mb-8">{{ content }}</p>
                    <div
                        class="flex items-center flex-wrap pb-4 mb-4 border-b-2 border-gray-100 mt-auto w-full"
                    >
                        <a class="text-red-500 inline-flex items-center">
                            Learn More
                            <svg
                                class="w-4 h-4 ml-2"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                                stroke-width="2"
                                fill="none"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            >
                                <path d="M5 12h14" />
                                <path d="M12 5l7 7-7 7" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
