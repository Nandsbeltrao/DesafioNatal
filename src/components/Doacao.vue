<script setup>
    import Bola from "/bolaDeNatal.png";
</script>

<template>
    <section>
        <img :src="Bola" alt="">

        <h2>Conectando generosidade ao redor do mundos</h2>
        <p>Celebre a magia do Natal de uma maneira especial! Descubra a plataforma que permite a doação de presentes significativos para aqueles que mais precisam. Faça parte do movimento e compartilhe o verdadeiro espírito da generosidade.</p>

        <button>FAZER UMA DOAÇÃO</button>
    </section>
</template>

<style scoped lang="scss">

    section{

        margin-top: 2.2rem;
        img{
            margin-top: 20rem;
            margin-left: 31rem;
            width: 18.8vw;
        }

        h2{
            position: relative;
            left: 60rem;
            bottom: 22rem;
            width: 22vw;
            font-family: "Archivo", sans-serif;
            font-size: 2rem;
            font-weight: 600;
            line-height: 1.3; 
        }

        p{
            position: relative;
            left: 60rem;
            bottom: 20.5rem;
            width: 23vw;
            font-family: "Archivo", sans-serif;
            font-weight: 400;
            font-size: 1.2rem;
            line-height: 1.4;

        }

        button{
            border: none;
            padding: 1rem 2.5rem;
            border-radius: 4px;
            position: relative;
            left: 60rem;
            bottom: 18rem;
            background-color: #CD3C32;
            font-family: "Archivo", sans-serif;
            font-size: 1rem;
            font-weight: 600;
            color: white;
            cursor: pointer;

            &:hover {
                
                background-color: #a52a25;
            
            }
            
        }
    }
</style>