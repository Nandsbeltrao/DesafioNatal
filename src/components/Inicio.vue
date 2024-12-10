<script setup>
    import PapaiNoel from "/papaiNoel.png";
    import Loja from "/imagem1.png";
</script>

<template>
     <section class="primeira-sessao">
        <div>

             <img :src="PapaiNoel" alt="Ilustração do Papai Noel">
             <h2>Feliz Natal</h2>

        </div>

        <h1>Uma <span>plataforma de doação</span> para espalhar alegria</h1>
        <p>Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</p>
        
        <button type="button" title="Clique para fazer uma doação">FAZER UMA DOAÇÃO</button>

        <img class="loja"  :src="Loja" alt="Imagem de uma loja natalina">

     </section>
</template>

<style scoped lang="scss">
    
    .primeira-sessao{
        background-color: #FFE9E8;
        height: 56vh;
        

        div{
            display: flex;
            margin-left: 17rem;
            position: relative;
            top: 7.5rem;
            left: 11rem;
            
            h2{
                font-size: 1.2rem;
                font-family: "Archivo", sans-serif;
                font-weight: 550;
                margin-left: 0.7rem;
                margin-top: 0.7rem;
            }
        }

        h1{
            position: relative;
            top: 9rem;
            left: 27.8rem;
            font-family: "Archivo", sans-serif;
            font-size: 2.3rem;
            font-weight: 600;
            width: 25vw;

            span{
                color: #CD3C32;
            }

        }

        p{
            position: relative;
            top: 10rem;
            left: 27.8rem;
            font-family: "Archivo", sans-serif;
            font-size: 1.2rem;
            font-weight: 400;
            width: 23.8vw;
            line-height: 1.4;

        }

        button{
            border: none;
            padding: 1rem 1rem;
            border-radius: 3px;
            position: relative;
            left: 27.8rem;
            bottom: 8rem;
            background-color: #CD3C32;
            font-family: "Archivo", sans-serif;
            font-weight: 600;
            color: white;
            cursor: pointer;

            &:hover {
                
                background-color: #a52a25;
            
            }
            
        }

        .loja{
            position: relative;
            bottom: 5rem;
            left: 55rem;

        }
    }
</style>