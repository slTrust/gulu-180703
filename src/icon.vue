<template>
    <svg class="g-icon" aria-hidden="true">
        <use :xlink:href="`#i-${name}`"></use>
    </svg>
</template>

<script>
    export default {
        props:['name']
    }
</script>

<style lang="less">
    .g-icon {height: 1em;width: 1em;}
</style>