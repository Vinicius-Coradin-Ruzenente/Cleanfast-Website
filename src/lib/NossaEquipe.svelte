<script>
    import equipe from "./images/foto-equipe.webp"
    import { fade } from 'svelte/transition'
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
        <span in:fade><img src="" alt="" class="xuao"></span>
        
    </div>
</section>
<style>
.equipe span {
    width: 1em;
    height: 2rem;
    position: absolute;
    top: 6.6vw;
    left: 16vw;
    opacity: 0;
    -webkit-transition: .7s ease-in-out opacity;
    -moz-transition: .7s ease-in-out opacity;
    -o-transition: .7s ease-in-out opacity;
    transition: .7s ease-in-out opacity;
}
.equipe span:hover {
    background-image: url("./images/logos-clientes/xuan.webp");
    background-repeat: no-repeat;
    opacity: 1;
    width: 50vw;
    height: 150vh;
    display: flex;
    justify-content: center;
    align-items: center;
    top: -40vh;
    left: -10vw;
}
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
.bannerNossaEquipe .texto{
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
.equipe .foto-equipe{
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
    .bannerNossaEquipe .texto{
        width: 80vw;
    }
    .equipe img {
        width: 80vw;
        padding-bottom: 2vh;
    }
}
</style>