<footer class="rodape fundo-branco" id="contato">
    <p class="endereco"><strong>Rua Sete de Setembro, 42 | Colombo, PR</strong></p>
    <ul class="contato">
        <li><p class="email"><strong>contato@cleanfast.com.br</strong></p></li>
        <li><p><strong>+55 (41) 99758-9604</strong></p></li>
        <li><p><strong>+55 (41) 3206-5700</strong></p></li>
    </ul>
</footer>
<style>
.rodape {
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    height: 20vh;
}
.rodape ul {
    list-style: none;
}
.rodape .endereco {
    width: 55vw;
}
.rodape .contato {
    width: 45vw;
}
.rodape p {
    font-size: calc(0.8rem + 0.1vw);
}

@media screen and (min-width: 1920px) {
    .rodape {
        font-size: calc(1rem + 0.3vw);
    }
}

@media screen and (max-width: 1024px) {
    .rodape .endereco {
        width: 30vw;
        font-size: calc(0.8rem + 0.3vw);
    }
    .rodape .contato .email {
        width: 30vw;
        font-size: calc(0.6rem + 0.1vw);
    }
}
</style>