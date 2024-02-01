<template>
    <div>
        admin clients id= {{ route.params.id }}
    </div>
</template>

<script setup>
const route = useRoute();
console.log(route);
</script>