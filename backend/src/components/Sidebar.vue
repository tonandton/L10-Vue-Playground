<template>

    <div class="w-[200px] bg-blue-700 text-gray-300 py-4 px-2">
        <router-link :to="{ name: 'app.dashboard' }"
            class="flex items-center py-1 px-3 rounded transition-colors  hover:bg-black/30">
            <span class="mr-4">
                <HomeIcon class="w-4" />
            </span>
            <span>
                Dashboard
            </span>
        </router-link>
    </div>

</template>

<script setup>
import { HomeIcon } from "@heroicons/vue/24/outline"
</script>

<style scoped></style>

<!-- 9.44 -->
