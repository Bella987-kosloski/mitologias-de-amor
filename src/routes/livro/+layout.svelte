<script>
    let { children } = $props();
</script>
<div class="row">
    <div class="col-4">
        <ul class="list-group list-group-flush">
            <li class="list-group-item">
                <a href="/livro"> Copiright</a>
            </li>
            <li class="list-group-item">
              <a href="/livro/cap01"> Dedicatoria</a>
            </li>
            <li class="list-group-item">
                <a href="/livro/cap02"> Sumário</a>
            </li>
            <li class="list-group-item">
                <a href="/livro/cap03"> Sobre autora e designer</a>
            </li>
            <li class="list-group-item">
                <a href="/livro/cap04"> O Começo</a>
            </li>
            <li class="list-group-item">
             <a href="/livro/cap05"> O Anjo</a>
            </li>
            <li class="list-group-item">
                <a href="/lvro/cap06">Bailarino</a>
            </li>
            <li class="list-group-item">
              <a href="/livro/cap07"> Mãe</a>
            </li>
            <li class="list-group-item">
                <a href="/livro/cap08"> Boneca de Porcelana</a>
            </li>
            <li class="list-group-item">
                <a href="/livro/cap09"> Ilusões</a>
            </li>
            <li class="list-group-item">
             <a href="/livro/cap10"> Morpheus</a>
            </li>
            <li class="list-group-item">
               <a href="/livro/cap11"> Amarras de amor</a>
            </li>
            <li class="list-group-item">
               <a href="/livro/cap12"> Lírios do vale</a>
            </li>
            <li class="list-group-item">
              <a href="/livro/cap13"> nao sei</a>

            </li>
            <li class="list-group-item">
             <a href="/livro/cap14">nao sei</a>
            </li>
            <li class="list-group-item">
              <a href="/livro/cap15">nao sei</a>
            </li>

          </ul>
    </div>
    <div class="col-8">
        {@render children()}
    </div>
</div>

