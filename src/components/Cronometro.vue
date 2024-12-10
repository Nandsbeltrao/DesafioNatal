<script setup>

import Presente from "/presentes.png";

</script>

<template>

    <section>
        <h2>Tempo limitado</h2>
        <p>Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</p>
        <h3>10d -24h - 01m - 52s</h3>

        <img :src="Presente" alt="">
    </section>
</template>

<style scoped lang="scss">

    section{
        
    text-align: center;
    margin-top: 5.5rem;

        h2,h3{
            font-family: "Archivo", sans-serif;
            font-weight: 600;
            font-size: 2.2rem;
        }

        p{
            font-family: "Archivo", sans-serif;
            font-weight: 400;
            font-size: 1.2rem;
            margin-top: 1.5rem;
            margin-left: 45rem;
            line-height: 1.5;
            width: 24vw;

        }

        h3{
            color: #CD3C32;
            line-height: 3;
        }
    }
</style>