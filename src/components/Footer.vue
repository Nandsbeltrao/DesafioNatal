<script setup>
    import PapaiNoel from "/papaiNoel.png";
    import redesSociais from "/redesSociais.png";
</script>

<template>
    <footer>
        <div>
            <img :src="PapaiNoel" alt="Ilustração do Papai Noel">
            <h2>Feliz Natal</h2>
        </div>

        <img class="redes" :src="redesSociais" alt="">
    </footer>
</template>

<style scoped lang="scss">
    footer{
        background-color: #FFE9E8;
        display: flex;
        justify-content: space-around;
        height: 8vh;

        div{

            img{
                margin-top: 1.2rem;
            }
            h2{
                margin-left: 3rem;
                margin-top: -2rem;
                font-family: "Archivo", sans-serif;
                font-size: 1.2rem;
                font-weight: 500;
            }
        }

        .redes{
            width: 15vw;
            height: 3.8vh;
            margin-top: 1rem;
        }
    }
</style>