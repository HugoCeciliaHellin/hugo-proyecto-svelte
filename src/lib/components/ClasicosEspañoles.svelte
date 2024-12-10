<script>
    import "../styles/ClasicosEspañoles.css"
    import Quijote from "../img/Quijote.jpg"
    const libros = [
    {
      titulo: "Don Quijote",
      descripcion:
        "El ingenioso hidalgo don Quijote de la Mancha narra las aventuras de un hidalgo pobre que al leer novelas de caballería acaba enloqueciendo y creyendo ser un caballero andante, nombrándose a sí mismo como don Quijote de la Mancha.",
      imagen: {Quijote}, 
    },
    {
      titulo: "Don Quijote",
      descripcion:
        "El ingenioso hidalgo don Quijote de la Mancha narra las aventuras de un hidalgo pobre que al leer novelas de caballería acaba enloqueciendo y creyendo ser un caballero andante, nombrándose a sí mismo como don Quijote de la Mancha.",
        imagen: {Quijote}, 
    },
    {
      titulo: "Don Quijote",
      descripcion:
        "El ingenioso hidalgo don Quijote de la Mancha narra las aventuras de un hidalgo pobre que al leer novelas de caballería acaba enloqueciendo y creyendo ser un caballero andante, nombrándose a sí mismo como don Quijote de la Mancha.",
        imagen: {Quijote}, 
    },
  ];
    
  </script>

<section class="clasicos">
    <h2 class="clasicos-titulo">Clásicos Españoles</h2>
    <div class="clasicos-container">
      {#each libros as libro}
        <div class="clasicos-item">
          <img src={Quijote} alt={libro.titulo} class="clasicos-imagen" />
          <h3 class="clasicos-titulo-libro">{libro.titulo}:</h3>
          <p class="clasicos-descripcion">{libro.descripcion}</p>
        </div>
      {/each}
    </div>
  </section>