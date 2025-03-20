<script>
    import horto from "./images/horto.webp"
</script>
<section class="quemSomosExpandido fundo-branco" id="quemSomosExpandido">
    <div class="bannerQuemSomosExpandido">
        <h2 class="titulo"><strong>QUEM SOMOS</strong></h2>
        <p class="texto">
            <strong>A empresa Clean Fast vem construindo sua história desde 2003, atuando no ramo de limpeza, jardinagem, 
                paisagismo, roçada, coleta de resíduos vegetais e até serviços de hotelaria em todo o Brasil. Atualmente 
                temos diversos contratos no estado do Paraná, com mais de 500 colaboradores diretos e indiretos, a Clean Fast 
                vem contribuindo para que espaços urbanos sejam a cada dia mais limpos e sustentáveis.</strong>
        </p>
    </div>
    <div class="folhaBg">
        <img src={horto} alt=''>
    </div>
</section>
<style>
.quemSomosExpandido {
    display: flex;
    flex-direction: row;    
    flex-wrap: wrap;
    width: 100vw;
    height: 110vh;    
}
.bannerQuemSomosExpandido {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;    
    width: 45vw;
    height: auto;
}
.bannerQuemSomosExpandido .titulo {    
    padding-left: 5vw;
}
.bannerQuemSomosExpandido .texto{
    padding-left: 5vw;
    padding-right: 2vw;
}
.folhaBg img{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 55vw;
    height: 110vh;
}

@media screen and (max-width: 1024px) {
    .bannerQuemSomosExpandido {
        width: 90vw;
        flex-wrap: wrap;
    }
    .bannerQuemSomosExpandido p{
        width: 80vw;
        padding-left: 2rem;
        padding-right: 2rem;
    }
    .folhaBg img {
        display: none;
    }
}
</style>