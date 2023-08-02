<script setup>
import {useHelloStore} from '@/store/useHelloStore';
const hello = useHelloStore()
</script>

<template>
  <main>
    <h1 class="title is-1">{{hello.hello}}</h1>
  </main>
</template>
