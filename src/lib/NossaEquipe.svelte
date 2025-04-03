<script>
    import equipe from "./images/foto-equipe.webp"
</script>
<section class="nossaEquipe fundo-preto" id="nossaEquipe">
    <div class="bannerNossaEquipe">
        <h2 class="titulo"><strong>Conheça nossa equipe</strong></h2>
        <p class="texto">
                Somos compostos por uma equipe de profissionais competentes e em constante evolução, lidando com cada
                situação de forma dinâmica e ética, sempre se esforçando para entregar resultados coerentes e satisfatórios
                sempre evoluíndo e se adaptando.
        </p>
    </div>
    <div class="equipe">
        <img src={equipe} alt='' class="foto-equipe">
    </div>
</section>
<style>
.nossaEquipe {
    display: flex;
    flex-direction: row;    
    flex-wrap: wrap;
    justify-content: space-evenly;
    width: 100vw;    
}
.nossaEquipe h2 {
      font-size: calc(1rem + 2vw);
}
.bannerNossaEquipe {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;    
    width: 40vw;
    height: auto;
}
.bannerNossaEquipe .titulo {    
    padding-left: 5vw;
}
.bannerNossaEquipe .texto {
    padding-left: 5vw;
    padding-right: 2vw;
}
.equipe {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1rem;
    margin: 0px;
    position:relative;
}
.equipe .foto-equipe {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40vw;
}

@media screen and (max-width: 1024px) {
    .bannerNossaEquipe {
        padding-top: 2vh;
        margin: 0;
        width: 100vw;
        flex-wrap: wrap;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .bannerNossaEquipe .titulo {
        padding-left: 0;
        font-size: calc(1rem + 2.5vw);
    }
    .bannerNossaEquipe .texto {
        width: 80vw;
    }
    .equipe img {
        width: 80vw;
        padding-bottom: 2vh;
    }
    .equipe span {
    display: none;
}
}
</style>