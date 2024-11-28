<script setup>

import { useRouter } from 'vue-router';

const router = useRouter();

const goToAbout = () => {
    router.push('/about');
};

</script>

<template>

    <div>
        <button @click="goToAbout">Go to About</button>
    </div>
</template>