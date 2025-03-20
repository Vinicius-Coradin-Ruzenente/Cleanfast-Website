<script lang=ts>
    import { fade } from 'svelte/transition'
    import { inview } from 'svelte-inview'

    let isInView: any;
</script>
<section class="missaoVisaoValores fundo-preto" id="missaoVisaoValores" 
        use:inview={{ unobserveOnEnter: true, rootMargin: '-20%'}}
        on:change={({detail}) => {
            isInView = detail.inView}}>
    {#if isInView}
    <div in:fade={{duration: 1000}} class="bloco" id="f1">
        <h3>Missão</h3>
        <p id="p1"><strong>Realizar serviços na área de paisagismo e manutenção urbana, mantendo a cidade organizada e limpa para benefício de moradores e visitantes</strong></p>
    </div>    
    <div in:fade={{duration: 1000, delay: 600}} class="bloco" id="f2">
        <h3>Visão</h3>
        <p id="p2"><strong>Ser referência na área de prestação de serviços para órgãos públicos e privados</strong></p>
    </div>
    <div in:fade={{duration: 1000, delay: 1200}} class="bloco" id="f3">
        <h3>Valores</h3>
        <p id="p3"><strong>Ser uma empresa ética, cumprindo suas obrigações junto aos contratantes criando um ambiente seguro e participativo para colaboradores e munícipes</strong></p>
    </div>
    {/if}
</section>
<style>
    .missaoVisaoValores {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    align-items: center;
    height: 72.7vh;
    width: 100vw;
    color:white;
    }
.bloco {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 23vh;
    width: 99vw;
}
.bloco p {
    padding: 0;
    width: 70vw;
}
#p1, #p2, #p3 {
    background-image: linear-gradient(rgba(40, 255, 58, 0.281), rgba(40, 255, 58, 0.021));
    padding: 1rem;
  }

@media screen and (max-width: 1024px) {
    .missaoVisaoValores .bloco {
        width: 100vw;
        flex-wrap: nowrap;
        justify-content: center;
        align-items: center;
    }
    .missaoVisaoValores p {
        width: 80vw;
    }
}
</style>