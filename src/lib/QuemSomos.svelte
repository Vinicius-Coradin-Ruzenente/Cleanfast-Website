<section class="quemSomos" id="quemSomos">
    <h2 class="titulo"><strong>Clean Fast Serviços</strong></h2>
    <p class="texto">
        Muito mais que serviços, soluções para espaços urbanos sustentáveis.
    </p>
    <a href="#quemSomosExpandido"><button type="button" class="fundo-verde"><strong>Saiba Mais</strong></button></a>
</section>

<style>
    .quemSomos {
    width: 98.9vw;
    height: 101vh;
    overflow: auto;
    display: flex;
    flex-direction: column;
    color: rgb(255, 255, 255);
}
.quemSomos .titulo {
    padding-top: 20vw;    
}
.quemSomos .texto {
    padding-top: 1vw;
    width: 60vw;
}
.quemSomos button {
    width: 7vw;
    height: 5vh;
    border-radius: 20px;
    margin-left: 10vw;
    margin-top: 1rem;
    border: none;
}
@keyframes transicaoVerde {
    from {background-color:rgb(35, 109, 27);}
    to {background-color: rgb(56, 173, 43);}
}
.quemSomos button:hover {
    background-color: rgb(56, 173, 43);
    cursor: pointer;
    animation-name: transicaoVerde;
    animation-duration: 0.5s;
}
.quemSomos a {    
    text-decoration: none;
    color: inherit;
    width: 7vw;
}

@media screen and (max-width: 1024px) {
    .quemSomos button {
        width: 15vw;
        height: 10vh;
    }
}
</style>