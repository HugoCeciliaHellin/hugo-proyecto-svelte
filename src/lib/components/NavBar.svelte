<script>
    import "../styles/NavBar.css";
    let menuItems = [
      "Productos",
      "Biblioteca",
      "Intercambio",
      "Tienda",
      "Valoraciones",
      "Audiolibro"
    ];
  </script>
  
  
  
  <div class="navbar margin-top">
    <div class="menu">
      {#each menuItems as item}
        <a href="#" class="menu-item">{item}</a>
      {/each}
    </div>
    <div class="right-buttons">
      <button class="button inicio">Inicio</button>
      <button class="button registro">Registro</button>
    </div>
  </div>