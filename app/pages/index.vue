<template>
    <h1>This is a test page</h1>
    <p v-if="isLogged">You are logged in!</p>
    <p v-else>You are not logged in.</p>
</template>

<script lang="ts" setup>
const { isLogged } = useBeditaAuth();
</script>