<script setup lang="ts">
import { AppNavBar } from '#components';

</script>

<template>
    <div class="flex min-h-screen flex-col">
        <AppNavBar />
        <main>
            <slot />
        </main>
    </div>
</template>