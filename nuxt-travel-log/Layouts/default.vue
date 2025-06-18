<script setup lang="ts">
import { AppNavBar } from '#components';

</script>

<template>
    <div class="flex min-h-screen flex-col">
        <AppNavBarar/>
        <main>
            <slot/>
        </main>
    </div>
</template>