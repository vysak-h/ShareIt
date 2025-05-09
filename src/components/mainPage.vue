<script setup>
import Heading from './heading.vue'
import IndexPage  from './IndexPage.vue';
</script>

<template>
    <header>
        <div class="mx-auto flex max-w-sm items-center">
            <Heading />
        </div>
    </header>

    <!-- <div>
        <div class="mx-auto flex max-w-sm items-center gap-x-4 rounded-xl bg-white p-6 shadow-lg outline outline-black/5 dark:bg-slate-800 dark:shadow-none dark:-outline-offset-1 dark:outline-white/10">
        <img class="size-12 shrink-0" src="" alt="ChitChat Logo" />
            <div>
                <div class="text-xl font-medium text-black dark:text-white">ChitChat</div>
                <p class="text-gray-500 dark:text-gray-400">You have a new message!</p>
            </div>
        </div>
    </div> -->
    <div>
        <IndexPage />
    </div>
    

</template>