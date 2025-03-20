<script>
    import cleanfastLogo from '../lib/images/logo.webp'
</script>

<nav class="navInformacoes">
    <header class="logo">
        <button type="button"><a href="/"><img src={cleanfastLogo} alt="Logomarca Cleanfast"></a></button>
    </header>
    <ul class="navItems">            
        <li class="navItemVisao"><a href="#quemSomos"><strong>Ínicio</strong></a></li> <strong>|</strong>
        <li class="navItemValores"><a href="#missaoVisaoValores"><strong>Nossa Identidade</strong></a></li> <strong>|</strong>
        <li class="navItemVisao"><a href="#nossosServicos"><strong>Nossos Serviços</strong></a></li> <strong>|</strong>
        <li class="navItemVisao"><a href="#nossosClientes"><strong>Nossos Parceiros</strong></a></li> <strong>|</strong>
        <li class="navItemContato"><a href="#contato"><strong>Contate-nós</strong></a></li>
    </ul>
</nav>
<style>
.navInformacoes {
    position: fixed;
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: calc(3rem + 1.8vw);
    background-image: linear-gradient(rgba(0, 0, 0, 0.527), rgba(0, 0, 0, 0.014));
    font-size: calc(1rem + 0.01vw);
    color: rgb(56, 173, 43);
    width: 100%;
}
.navItems {
    display: flex;
    flex-direction: row;
    list-style: none;
}
.navItems li {
    margin-left: 1em;
    margin-right: 1em;
}
.navItems li a {
    text-decoration: none;
    color: inherit;
}
a:visited {
    color: inherit
}
.navInformacoes img{    
    margin-left: 0.5em;
    margin-top: 0.3em;
    height: calc(3rem + 1.8vw)
}
.navInformacoes button {
    border-style: none !important;
    background: transparent;
}

@media screen and (max-width: 1024px) {
    .navInformacoes {
        display: none !important;
        padding: 0;
    }
}
@media screen and (min-width: 1920px) {
    .navInformacoes { 
        font-size: calc(1rem + 0.1vw);
        height: calc(1.4rem + 2vw);
    }
    .navInformacoes img{
        height: calc(3rem + 0.7vw)
    }
}
</style>