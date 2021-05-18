# Instalación de SASS


<p>Lo primero que debes saber es que no puedes insertar directamente un archivo .scss en un archivo .html.</p>
<p>¿Por qué?</p>
<p>Porque SASS al ser un preprocesador de CSS3 y no es soportado en los navegadores web. Por lo tanto, los pasos a seguir son:</p>

<h3>1. Instalación de SASS en tu computador.</h3>

<ul>
  <li>Si usas <strong>npm</strong> debes poner en tu consola: <code>npm install -g sass</code></li>
  <li>Si usas <strong>Chocolatey Package Manager</strong> (Windows) debes poner en tu consola: <code>choco install sass</code></li>
  <li>si eres MAC OS X debes poner en tu consola: <code>brew install sass/sass/sass</code></li>
</ul>

<blockquote>Documentación oficial: <a href="https://sass-lang.com/install">https://sass-lang.com/install</a></blockquote>

<h3>2. Correr el proyecto con SASS</h3>

<p>Para poder visualizar tus proyectos de sass en el navegador, debes escribir en tu consola: <code>sass --watch tu-ruta/sass/styles.scss tu-ruta/styles/index.scss</code></p>

<h3>3. Ver tu proyecto en el navegador</h3>

<p>Al correr el comando anterior, notarás en tu código que se crea un archivo <code>styles.css.map</coda>. Si sí, ya puedes ir a tu navegador y poner la ruta del <code>index.html</code> de tu proyecto.</p>
