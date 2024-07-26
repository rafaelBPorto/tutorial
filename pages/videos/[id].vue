<template>
    <div>
        Vídeo específico {{ id }}
    </div>
</template>

<script setup>

    const route  = useRoute()    
    const id = computed(() => route.params.id)

</script>
<style>

</style>