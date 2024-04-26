# Curso de Visualización de Datos con Matplotlib y Seaborn

>💡En este repositorio se encuentran todos los notebooks y archivos necesarios para los principios de Visualización de Datos con Matplotlib y Seaborn.

Visualizar los datos te da respuestas a preguntas que ni siquiera tenías. Entonces, ¿por qué es importante para el mundo de las ciencias de datos? Veamos a detalle.

**¿Cuál es la importancia de la visualización de datos?**

La visualización de datos es importante porque te permite entender a profundidad tendencias, valores o patrones de datos representados a través de representación gráfica de la información.

**Permite mayor contexto**

Supón que tienes los datos y sabes hacer análisis estadísticos como desviación estándar o correlación, pero esto no da el total de los datos. Por ejemplo, al visualizarlos de manera gráfica, usando un dataset como Datasaurus, puedes ver representaciones diferentes a pesar de tener la misma información.

**Permite hallazgos en nuestros datos**

La visualización de datos te permite encontrar hallazgos directamente y de manera muy sencilla, como por ejemplo:

- Hallar tendencias
- Comportamientos
- Detectar Outliers

**Permite mayor claridad en el código**

También se utiliza en la ciencia de datos orientada hacia el machine learning o inteligencia artificial, como las líneas de entrenamiento. Esto hace parte de un entrenamiento de cualquier algoritmo pues siempre vas a estar analizando esto y la manera más fácil de entenderlo a través de visualizaciones.
<details>
  <summary><strong>📉Matplotlib</strong></summary>
  <a href="https://matplotlib.org/stable/plot_types/basic/plot.html#sphx-glr-plot-types-basic-plot-py">Documentación de Matplotlib</a>
  <p>Esta librería esta escrita sobre Python, emula los comandos de Matlab y usa Numpy.</p>
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
    <p>El gráfico de barras nos permite graficar variables categóricas, es decir, variables de texto, lo que es muy importante en el mundo de la ciencia de datos y Matplotlib ofrece ciertas características que nos facilita la vida en cuanto a graficar este tipo de variables.</p>
  </details> 
  <details>
    <summary>🟢Crear otro tipo de gráficas </summary>
    <a href="/">Notebook</a>.
    <p>Existen otros tipos de gráficos que Matplotlib nos proporciona para ser mucho más certeros en nuestros análisis.</p>
  </details> 
</details>

<br>
<details>
  <summary><strong>📈Seaborn</strong></summary>
  <a href="https://seaborn.pydata.org/tutorial/function_overview.html"> Documentación de Seaborn</a>
  <p>Seaborn es una librería construida sobre Matplotlib, por lo que hereda todas las bondades de la misma. Fue escrita por Michael Waskom y está integrada para estructuras de Pandas por lo que está optimizada para funcionar con DataFrames.</p>
  <h3>Ventajas de Seaborn</h3>
  <p>Seaborn tiene diferentes ventajas y entre ellas encuentras principalmente:</p>
  <ul>
    <li>Tiene una gran velocidad</li>
    <li>Facilidad para escribir código</li>
    <li>Altamente customizable entre gráficas y visualizaciones</li>
  </ul>
  <strong>Estructura Básica de Seaborn</strong>
  <pre><code>sns.Tipo de Grafica(
      data='Dataset',
      x='Data en el eje x',
      y='Data en el eje y',
      hue='Variable de agrupamiento')
  </code></pre>
  <h3>Tipos de Gráficas que tiene Seaborn</h3>
  <p>Seaborn ofrece ciertas características principales para problemas específicos de visualización de datos:</p>
  <ul>
    <li>Diagramas o gráficas relacionables</li>
    <li>Distribución de datos</li>
    <li>Graficar variables categóricas</li>
  </ul>

  Por ejemplo:

    Relplot (relacional): scatterplot, lineplot.
    Displot (distribuciones): histplot, kdeplot, ecdfplot, rugplot.
    Catplot (categorica): stripplot, swamplot, boxplot, violinplot, pointplot, barplot.
  <details>
    <summary>🟢Set </summary>
    <a href="/">Notebook</a>.
    <p>Set es un método de Seaborn que permite configurar el estilo, fuente y color de las gráficas.</p>
    <strong>¿Qué necesitas saber al usar Set?</strong>
    <ul>
      <li>Este parámetro afecta a todas las gráficas que creamos, incluidas las que no usan Seaborn.</li>
      <li>Podemos resetear los valores utilizando el método reset_orig.</li>
      <li>Este parámetro es un atajo de set_theme, que es el recomendado según la documentación.</li>
    </ul>
  </details>
  <details>
    <summary>Parámetros más usados con Seaborn</summary>
    <a href="/">Notebook</a>.
    <p>Seaborn tiene una gran variedad de gráficos, pero también tiene ciertos parámetros para cada gráfico, vamos a ver cuáles son los más comunes:</p>
  </details>
  <details>
    <summary>Distribuciones</summary>
    <p>Seaborn ofrece algunas gráficas u opciones que te permiten trabajar con distribuciones orientadas a tipos de datos numéricos. Veamos como puedes lograrlo utilizando <a href="/">código</a>.</p>
  </details>
  <details>
    <summary>Categóricos</summary>
    <p>Seaborn ofrece diferentes gráficos para graficar datos categóricos o variables de texto. A continuación verás el <a>código</a> que podrás usar para gráficar este tipo de datos.</p>
  </details>
  <details>
    <summary>Relation</summary>
    <a href="/">Notebook</a>.
    <p>Seaborn maneja los gráficos de relación entre distintas variables numéricas para hacer visualizaciones. Veamos los distintos gráficos que tiene Seaborn para trabajar este tipo de relaciones.</p>
  </details>
  <details>
    <summary>Jointplot y Pairplot</summary>
    <a href="/">Notebook</a>.
    <p>Jointplot y Pairplot son funcionalidades de Seaborn, porque con un solo comando se puede generar varios tipos de gráficos.</p>
  </details>
  <details>
    <summary>Heatmap</summary>
    <a href="/">Notebook</a>.
    <p>Heatmap es un tipo de gráfico enfocado a una estructura matricial. Heatmap correlaciona todas las variables numéricas del dataset.</p>
  </details>


</details>
