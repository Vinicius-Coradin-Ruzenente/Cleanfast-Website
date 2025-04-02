<script lang="ts">
  import BarraNavegacao from './lib/BarraNavegacao.svelte';
  import MissaoVisaoValores from './lib/MissaoVisaoValores.svelte';
  import NossosClientes from './lib/NossosClientes.svelte';
  import NossosServicos from './lib/NossosServicos.svelte';
  import QuemSomos from './lib/QuemSomos.svelte';
  import QuemSomosExpandido from './lib/QuemSomosExpandido.svelte';
  import Rodape from './lib/Rodape.svelte';

</script>
<nav>  
  <BarraNavegacao />
</nav>
<main>
  <QuemSomos />
  <QuemSomosExpandido />
  <br>
  <MissaoVisaoValores />
  <br>  
  <NossosServicos />
  <NossosClientes />
</main>
<footer>
  <Rodape />
</footer>
<style>
</style>
