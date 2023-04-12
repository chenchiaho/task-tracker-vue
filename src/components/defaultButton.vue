<template>
    <button @click="onClick()" :style="{background: color}" class="btn">{{ text }}
    </button>
</template>

<script>
    export default {
        name: 'default-button',
        props: {
            text: String,
            color: String,
        },
        methods:{
            onClick() {
                
            }
        }
    }
</script> 