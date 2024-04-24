# Curso de Visualización de Datos con Matplotlib y Seaborn

En este repositorio se encuentran todos los notebooks y archivos necesarios para los principios de Visualización de Datos con Matplotlib y Seaborn.
<details>
  <summary><strong>📉Matplotlib</strong></summary>
  <a href="https://matplotlib.org/stable/plot_types/basic/plot.html#sphx-glr-plot-types-basic-plot-py">Documentación de Matplotlib</a>
  <details>
    <summary>🟢Pyplot básico</summary>
    Pyplot es una herramienta que tiene Matplotlib para ejecutar gráficas de manera sencilla. <a href="">Véamos cómo puedes lograrlo</a>.
    <br><br>
    Cambiemos el color de la gráfica
    <table>
      <tr>
        <th>Character</th>
        <th>Color</th>
      </tr>
      <tr>
        <td>'b'</td>
        <td>blue</td>
      </tr>
      <tr>
        <td>'g'</td>
        <td>green</td>
      </tr>
      <tr>
        <td>'m'</td>
        <td>magenta</td>
      </tr>
    </table>
    <br>
    Cambiemos el tipo de marcador
    <table>
      <tr>
        <th>Character</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>'.'</td>
        <td>point marker</td>
      </tr>
      <tr>
        <td>','</td>
        <td>pixel marker</td>
      </tr>
      <tr>
        <td>'o'</td>
        <td>circle marker</td>
      </tr>
      <tr>
        <td>'v'</td>
        <td>triangle_down marker</td>
      </tr>
      <tr>
        <td>'^'</td>
        <td>triangle_up marker</td>
      </tr>
      <tr>
        <td>'&lt;'</td>
        <td>triangle_left marker</td>
      </tr>
      <tr>
        <td>'&gt;'</td>
        <td>triangle_right marker</td>
      </tr>
    </table>
    <br>
    Cambiemos el tipo de línea
    <table>
      <tr>
        <th>Character</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>'-'</td>
        <td>solid line style</td>
      </tr>
      <tr>
        <td>'--'</td>
        <td>dashed line style</td>
      </tr>
      <tr>
        <td>'-.'</td>
        <td>dash-dot line style</td>
      </tr>
      <tr>
        <td>':'</td>
        <td>dotted line style</td>
      </tr>
    </table>
  </details>
  <details>
    <summary>🟢Subplot</summary>
    Subplot permite crear gráficos dentro de una gráfica. Esto lo hace a través de una matriz de gráficos y se puede acceder a ellos a través de índices, <a href="https://matplotlib.org/stable/gallery/lines_bars_and_markers/barh.html#sphx-glr-gallery-lines-bars-and-markers-barh-py">Notebook</a>.
    <br>Los parámetros de subplot funcionan:
    <ul>
      <li>Filas</li>
      <li>Columnas</li>
      <li>Index(No. de gráfico)</li>
    </ul>
  </details>
  <details>
    <summary>🟢Método orientado a objetos</summary>
    <a href="/">Notebook</a>.
    <br>
    Hay distintas maneras de hacer gráficas dentro de Matplotlib, ya vimos pyplot; sin embargo, es muy complicado personalizarla y entrar a ciertos parámetros. Por ello, existe el método orientado a objetos.
    <br>
    Un objeto define una figura, esa figura es un lienzo en el cual podemos introducir diferentes grá ficas(axes), de las cuales cada una posee sus propios ejes(axis).
    <br>
    La figura representa el todo, dentro de ella vamos a configurar gráficas las cuales contienen diferentes ejes.
    <br>Es un poco más complicado, pero en el mismo gráfico podemos personalizarlo mucho mejor.
    <br></br>
    Parámetros de axes:
    <ul>
      <li>Pos. Eje x</li>
      <li>Pos. Eje y</li>
      <li>Size graph eje x</li>
      <li>Size graph eje y</li>
    </ul>
    <strong>Diferencias entre Pyplot y Object Oriented </strong>
    <table>
      <tr>
        <th>Pyplot</th>
        <th>Object Oriented</th>
      </tr>
      <tr>
        <td>Rápido</td>
        <td>Mayor personalización</td>
      </tr>
      <tr>
        <td>Fácil</td>
        <td>Más código</td>
      </tr>
      <tr>
        <td>Una sola figura</td>
        <td>Más amigable a múltiples diagramas</td>
      </tr>
    </table>
  </details>
  <details>
    <summary>🟢Subplots</summary>
    <a href="/">Notebook</a>.
    <p>Con subplots se puede trabajar en un arreglo de gráficas a las cuales se accede a través de los índices.</p>
  </details>
  <details>
    <summary>🟢Leyendas, etiquetas, títulos, tamaño</summary>
    <a href="/">Notebook</a>.
    <p>Para dar contexto a nuestros gráficos necesitamos usar títulos, leyendas, tamaño o etiquetas, para que nuestra gráfica tenga un contexto más amplio.</p>
  </details>
  <details>
    <summary>🟢Colores y estilos</summary>
    <a href="/">Notebook</a>.
    <p>Podemos personalizar mejor nuestros gráficos con diferentes colores y estilos, así, se entenderá mucho mejor nuestras gráficas.</p>
  </details>
  <details>
    <summary>🟢Bar Plot</summary>
    <a href="/">Notebook</a>.
    <p>El gráfico de barras nos permite graficar variables categóricas, es decir, variables de texto, lo que es muy importante en el mundo de la ciencia de datos y Matplotlib ofrece ciertas características que nos facilita la vida en cuanto a graficar este tipo de variables..</p>
  </details>  
</details>

<br>
<details>
  <summary><strong>📈Seaborn</strong></summary>
  <a href="/"> Documentación de Seaborn</a>
</details>
