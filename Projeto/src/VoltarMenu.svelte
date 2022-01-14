<script>
	import { trocarEstadoDoJogo } from './Estado.js'
</script>

<button on:click={() => trocarEstadoDoJogo('menu')}>
	Voltar ao menu
</button>

<style>
	button{
       color:royalblue;
       cursor: pointer;	
       font: 16px;
       background-color: #09B93E;
       padding: 4px 4px;
       border-radius: 12px;
       animation: moveBanner 1s 0.1s forwards;
       margin: 6px;
       letter-spacing: 0.08rem;
    }
</style>
