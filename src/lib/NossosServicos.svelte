<script>
    import exibicao from './images/exibicao.webp'
</script>
<section class="nossosServicos fundo-branco" id="nossosServicos">
    <div class="bannerNossosServicos">
        <h2 class="titulo"><strong>Nossos serviços</strong></h2>
        <ul>
            <li>
                <p class="texto">
                    <strong>Jardinagem:</strong> cuidamos e cultivamos com excelência em espaços públicos e privados, garantindo sustentabilidade e beleza aos variados ambientes.
                </p>
            </li>
            <br>
            <li>
                <p class="texto">
                    <strong>Paisagismo:</strong> cuidamos e cultivamos com excelência em espaços públicos e privados, garantindo sustentabilidade e beleza aos variados ambientes.
                </p>
            </li>
            <br>
            <li>
                <p class="texto">
                    <strong>Poda:</strong> cuidamos e cultivamos com excelência em espaços públicos e privados, garantindo sustentabilidade e beleza aos variados ambientes.
                </p>
            </li>
            <br>
            <li>
                <p class="texto">
                    <strong>Coleta de Resíduos:</strong> cuidamos e cultivamos com excelência em espaços públicos e privados, garantindo sustentabilidade e beleza aos variados ambientes.
                </p>
            </li>
        </ul>
    </div>
    <div class="foto">
        <img src={exibicao} alt="">
    </div>
</section>
<style>
.nossosServicos {
    height: 98vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    padding: 2rem;
}
.bannerNossosServicos {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.bannerNossosServicos ul {
    list-style: none;
}
.bannerNossosServicos h2 {
    font-size: calc(1rem + 1vw);
    padding-left: 0%;
    padding-bottom: 2vw;
}
.bannerNossosServicos p {
    font-size: calc(0.7rem + 0.3vw);
    padding-left: 2vw;
    padding-right: 2vw;
}

@media screen and (max-width: 1024px) {
    .nossosServicos {
        padding: 1rem;
    }
    .bannerNossosServicos h2 {
        font-size: calc(1rem + 2.5vw);
        padding-left: 0%;
        padding-bottom: 4vw;
    }
    .bannerNossosServicos p {
        font-size: calc(0.7rem + 1.5vw);
        padding-right: 10vw;
        padding-left: 7vw;
    }
    .nossosServicos div img {
        display: none;
    }
}
@media screen and (min-width: 1920px) {
    .bannerNossosServicos h2 {
        font-size: calc(1rem + 2.5vw);
    }
    .bannerNossosServicos p {
        font-size: calc(0.7rem + 1.2vw);
    }
}
</style>