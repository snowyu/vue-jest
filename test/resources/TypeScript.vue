<template>
    <div></div>
</template>

<script lang="ts">
import TypeScriptChild from './TypeScriptChild.vue'

export default {
    computed: {
        exclamationMarks(): string {
            return  'string'
        }
    },
    components: {
      TypeScriptChild
    }
};
</script>
