<script setup>
    import { defineProps } from 'vue';

    defineProps({
        bg:{
            type: String,
            default: 'bg-gray-100'
        }
    })
</script>

<template>
    <div :class="`${bg} p-8 rounded-lg shadow-md`">
        <slot>

        </slot>
    </div>
</template>