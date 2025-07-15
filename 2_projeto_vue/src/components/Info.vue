<template>
    
    <div>

        <p v-if='esta_estudando'>Estou estudando no momento.</p>

        <p v-else>Estou em busca de novas oportunidades!</p>

        <p>Utilizo as seguintes tecnologias:</p>

        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>

        <p v-if='4 > 2'>Testando</p>

        <p v-show='mostrar_email'>Mande uma mensagem para: {{ email }}</p>

    </div>

</template>

<script>
    export default {
        name: 'Info',
        data() {
            return {
                esta_estudando: false,
                mostrar_email: true,
                email: 'lucas@gmail.com'
            }
        }
    }
</script>