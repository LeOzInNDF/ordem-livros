<script lang="ts">
    export let livro: any = null;
</script>

{#if livro}
<a href="{livro.link}" target="_blank" class="flex flex-col rounded-md overflow-hidden bg-zingc-800">
    <img src="{livro.imagem}" alt="Imagem do Livro" class="h-96">
    <div class="flex-1 flex flex-col gap-2 p-5">
        <span class="flex-1 font-bold text-center">{livro.titulo}</span>
        <button class="botao azul"> Link do Livro </button>
    </div>
</a>
{/if}