<header class="principal__cabecera">
    <img class="principal__portada" src="assets/img/footer1.jpg" alt="Portada Terminal 2F">
    
    <div class="principal__detalles">
      <span class="principal__tipo">Sencillo</span>
      <h1 class="principal__titulo">Terminal 2F</h1>
      
      <div class="principal__metadatos">
        <span class="principal__artista principal__artista--destacado">GIMS</span>
        <span class="principal__separador">•</span>
        <span class="principal__artista">Dadju</span>
        <span class="principal__separador">•</span>
        <span>2024</span>
        <span class="principal__separador">•</span>
        <span>1 canción, 3 min 7 s</span>
      </div>
    </div>
  </header>

  <!-- Contenedor inferior con fondo degradado a negro -->
  <div class="principal__cuerpo">

    <!-- 2. Barra de acciones -->
    <section class="principal__acciones">
      <div class="principal__acciones-izquierda">
        <button class="principal__boton-reproducir" type="button" aria-label="Reproducir">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M8 5.14v14l11-7-11-7z"/></svg>
        </button>
        <button class="principal__boton principal__boton--atenuado" type="button" aria-label="Aleatorio">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 3h5v5M4 20l17-17M21 16v5h-5M15 15l6 6M4 4l5 5"/></svg>
        </button>
        <button class="principal__boton principal__boton--atenuado" type="button" aria-label="Guardar">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="16"/><line x1="8" y1="12" x2="16" y2="12"/></svg>
        </button>
        <button class="principal__boton principal__boton--atenuado" type="button" aria-label="Descargar">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="m8 12 4 4 4-4"/><line x1="12" y1="8" x2="12" y2="16"/></svg>
        </button>
        <button class="principal__boton principal__boton--atenuado" type="button" aria-label="Más opciones">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><circle cx="5" cy="12" r="2"/><circle cx="12" cy="12" r="2"/><circle cx="19" cy="12" r="2"/></svg>
        </button>
      </div>

      <div class="principal__acciones-derecha">
        <button class="principal__boton-vista" type="button">
          <span>Lista</span>
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="8" y1="6" x2="21" y2="6"/><line x1="8" y1="12" x2="21" y2="12"/><line x1="8" y1="18" x2="21" y2="18"/><line x1="3" y1="6" x2="3.01" y2="6"/><line x1="3" y1="12" x2="3.01" y2="12"/><line x1="3" y1="18" x2="3.01" y2="18"/></svg>
        </button>
      </div>
    </section>

    <!-- 3. Lista / Tabla de canciones -->
    <section class="tabla-pistas">
      <div class="tabla-pistas__encabezado">
        <span class="tabla-pistas__columna-num">#</span>
        <span class="tabla-pistas__columna-titulo">Título</span>
        <span class="tabla-pistas__columna-duracion">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
        </span>
      </div>

      <div class="tabla-pistas__fila tabla-pistas__fila--activa">
        <div class="tabla-pistas__indice">
          <span class="tabla-pistas__num">1</span>
          <button class="tabla-pistas__play-hover" type="button" aria-label="Reproducir">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M8 5v14l11-7z"/></svg>
          </button>
        </div>

        <div class="tabla-pistas__info">
          <span class="tabla-pistas__nombre">Terminal 2F</span>
          <span class="tabla-pistas__artistas">GIMS, Dadju</span>
        </div>

        <span class="tabla-pistas__tiempo">3:07</span>
      </div>
    </section>

    <!-- 4. Créditos / Legal -->
    <section class="principal__creditos">
      <p>16 de agosto de 2024</p>
      <p>© 2024 GÉANTE ROUGE</p>
      <p>℗ 2024 GÉANTE ROUGE</p>
    </section>

    <!-- 5. Más de GIMS (Tarjetas) -->
    <section class="discografia">
      <div class="discografia__cabecera">
        <h2 class="discografia__titulo">Más de GIMS</h2>
        <a class="discografia__enlace" href="#">Ver discografía</a>
      </div>

      <div class="discografia__rejilla">
        <article class="tarjeta-album">
          <div class="tarjeta-album__contenedor-img">
            <img class="tarjeta-album__img" src="assets/img/artista1.jpg" alt="Le Nord Se Souvient">
          </div>
          <h3 class="tarjeta-album__titulo">LE NORD SE SOUVIENT</h3>
          <span class="tarjeta-album__subtitulo">2024 • Álbum</span>
        </article>

        <article class="tarjeta-album">
          <div class="tarjeta-album__contenedor-img">
            <img class="tarjeta-album__img" src="assets/img/artista5.jpeg" alt="Le Nord Se Souvient">
          </div>
          <h3 class="tarjeta-album__titulo">LE NORD SE SOUVIENT</h3>
          <span class="tarjeta-album__subtitulo">2024 • Álbum</span>
        </article>

        <article class="tarjeta-album">
          <div class="tarjeta-album__contenedor-img">
            <img class="tarjeta-album__img" src="assets/img/artista9.jpg" alt="Subliminal">
          </div>
          <h3 class="tarjeta-album__titulo">Subliminal (La face...</h3>
          <span class="tarjeta-album__subtitulo">2013 • Álbum</span>
        </article>

        <article class="tarjeta-album">
          <div class="tarjeta-album__contenedor-img">
            <img class="tarjeta-album__img" src="assets/img/artista7.jpeg" alt="Soleil">
          </div>
          <h3 class="tarjeta-album__titulo">Soleil</h3>
          <span class="tarjeta-album__subtitulo">2024 • Sencillo</span>
        </article>
      </div>
    </section>

  </div>