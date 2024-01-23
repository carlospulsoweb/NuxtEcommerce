
import TheHeader from '../components/TheHeader.vue';

import TheFooter from '../components/TheFooter.vue';
<template>
    <div class="px-20">
        <TheHeader />
        <slot />
        <TheFooter />
    </div>
</template>