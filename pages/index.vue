<script setup lang="ts">
const {data} = await useAsyncData('products', () => GqlProducts({first: 3}))
</script>
<template>
    <div>
        {{ data }}
    </div>
</template>