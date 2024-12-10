<script>
import '../styles/LibroTarjeta.css';
import foto1 from '../img/foto1.jpg';
export let titulo;
export let descripcion;
  </script>
  

  <div class="tarjeta">
    <img src={foto1} alt={titulo} /><br><br>
    <h3>{titulo}</h3><br><br>
    <p>{descripcion}</p><br><br>
  </div>
  