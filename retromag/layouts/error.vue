<template>
    
        <div class="error-page">
            <h1 class="text-center error-code" v-if="error.statusCode === 404">404</h1>
        </div>
    
</template>

<script>
export default {
    props: ['error'],
    head: {
    title: 'ERROR'
    }
}
</script>

