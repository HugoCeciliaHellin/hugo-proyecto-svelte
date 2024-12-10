<script>
  import "../styles/Header.css"
  export let titulo = "KDLIBROS";
  import carrito from "../img/carrito.png"
  
</script>
<nav class="margin-bottom">
  <div class="nav-contenedor">
    <div class="nav-titulo">
      <h1>{titulo}</h1>
      <h4>La mejor pagina de intercambios de libros del mundo</h4>
    </div>
    <div class="barra-buscar">
      <input type="text" placeholder="Buscar libros..." />
    </div>
    <img class="nav-carrito" src={carrito} alt="Carrito" />
  </div>
</nav>