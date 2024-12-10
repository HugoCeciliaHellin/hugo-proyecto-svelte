<script>
  import Header from './lib/components/Header.svelte';
  import LibroTarjeta from './lib/components/LibroTarjeta.svelte';
  import Footer from './lib/components/Footer.svelte';
  import ClasicosEspaoles from './lib/components/ClasicosEspañoles.svelte';
  import PorQueKdl from './lib/components/PorQueKDL.svelte';
  import BarraLateral from './lib/components/BarraLateral.svelte';
  import NavBar from './lib/components/NavBar.svelte';
</script>


<div class="homepage">
  <Header />
  <NavBar></NavBar>
  <section class="books">
    <PorQueKdl></PorQueKdl>
    <div class="book-grid">
      <BarraLateral></BarraLateral>
      <LibroTarjeta titulo="Libro de Terror" descripcion="Este libro te llevará a explorar nuevas ideas y emociones, con citas inspiradoras, anécdotas personales y una breve historia que te hará reflexionar profundamente." />
      <LibroTarjeta titulo="Libro de Fantasia" descripcion="Este libro te llevará a explorar nuevas ideas y emociones, con citas inspiradoras, anécdotas personales y una breve historia que te hará reflexionar profundamente." />
      <LibroTarjeta titulo="Libro de Ciencia" descripcion="Este libro te llevará a explorar nuevas ideas y emociones, con citas inspiradoras, anécdotas personales y una breve historia que te hará reflexionar profundamente." />
    </div>
    <ClasicosEspaoles></ClasicosEspaoles>
  </section>
  <Footer />
</div>
