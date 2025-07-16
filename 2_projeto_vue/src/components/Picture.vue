<template>
    
    <img :src="avatar" :alt="descricao">

</template>

<script>
    export default {
        name: 'Picure',
        data() {
            return {
                avatar: '/img/avatar.png',
                descricao: 'Lucas Gabriel'
            }
        }
    }
</script>