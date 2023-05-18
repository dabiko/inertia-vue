<script setup>
import { ref } from 'vue'

const count = ref(0)

</script>

<template>
    <div>
        <h1>Hello Dabiko</h1>
        <button @click="count++">+</button>
         You clicked me {{ count }} times.
        <button @click="count--">-</button>
    </div>
</template>
