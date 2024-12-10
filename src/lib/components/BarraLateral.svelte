<script>
    import "../styles/BarraLateral.css"
    let tiposDeLibros = [
      "Libros de Terror",
      "Libros de Fantasía",
      "Libros de Ciencia",
      "Libros de Romance",
      "Libros de Música",
      "Libros de Misterio",
      "Libros divulgativos",
      "Libros religiosos",
      "Libros técnicos",
      "Libros de poesía",
      "Libros dramáticos",
    ];
  
  </script>
  
  
  <div class="sidebar">
    <div class="titulo">Tipos de libros:</div>
    <ul class="lista">
      {#each tiposDeLibros as tipo}
        <li>{tipo}</li><br>
      {/each}
    </ul>
  </div>
  