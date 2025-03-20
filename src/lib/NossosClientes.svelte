<script>
    import logoCopel from './images/logos-clientes/copel.png'
    import logoCuritiba from './images/logos-clientes/curitiba.png'
    import logoMylan from './images/logos-clientes/mylan.png'
    import logoPinhais from './images/logos-clientes/pinhais.png'
    import logoImperatriz from './images/logos-clientes/imperatriz.png'
    import logoCaxias from './images/logos-clientes/caxias.png'
    import logoSantaMaria from './images/logos-clientes/santa-maria.png'
</script>
<section class="nossosClientes fundo-preto" id="nossosClientes">
    <div class="bannerNossosClientes">
        <h2 class="titulo"><strong>Nossos parceiros</strong></h2>        
    </div>
    <div class="tabelaClientes">
        <div class="box"><img src={logoCopel} alt=""></div>
        <div class="box"><img src={logoCuritiba} alt=""></div>
        <div class="box"><img src={logoMylan} alt=""></div>
        <div class="box"><img src={logoPinhais} alt=""></div>
        <div class="box"><img src={logoImperatriz} alt=""></div>
        <div class="box"><img src={logoCaxias} alt=""></div>
        <div class="box"><img src={logoSantaMaria} alt=""></div>
    </div>
</section>
<style>
.nossosClientes {
    height: 98vh;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: row;
    padding: 2rem;
    background-image: linear-gradient(rgba(40, 255, 58, 0.185), rgba(40, 255, 58, 0.322));
}
.bannerNossosClientes {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding-right: 1rem;
}
.tabelaClientes {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    width: 45vw; 
}
.box {
    padding: 1rem;
}
.box img{
    color: transparent;
    padding: 0;
    margin: 0;
    width: 10rem;
}

@media screen and (max-width: 1024px) {
    .nossosClientes {
        display: flex;
        flex-direction: column;
        padding: 1rem;
    }
    .bannerNossosClientes {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        padding-right: 0rem;
    }
    .bannerNossosClientes h2 {
        font-size: calc(1rem + 2.5vw);
        padding-left: 0vw;
        padding-bottom: 4vw;
    }
    .box img{
        color: transparent;
        padding: 0;
        margin: 0;
        width: 5rem;
    }
}
</style>