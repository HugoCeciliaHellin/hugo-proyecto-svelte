<script>
    import "../styles/PorQueKDL.css";
    import social from "../img/social.png";
    import economico from "../img/dinero.png";
    import facil from "../img/garrapata.png";
    import seguro from "../img/teatro.png";
  
    const razones = [
      { icono: social, texto: "Social" },
      { icono: economico, texto: "Económico" },
      { icono: facil, texto: "Fácil" },
      { icono: seguro, texto: "Seguro" },
    ];
  </script>
  
  <section class="por-que-kdl">
    <h2 class="titulo">¿Por qué KDLibros?</h2>
    <div class="razones-container">
      {#each razones as razon}
        <div class="razon">
          <div class="icono-container">
            <img src={razon.icono} alt={razon.texto} class="icono" />
          </div>
          <p class="texto">{razon.texto}</p>
        </div>
      {/each}
    </div>
  </section>
  