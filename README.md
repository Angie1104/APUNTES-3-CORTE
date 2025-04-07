# SOLUCION DE ECUACIONES DIFERENCIALES 

## Metodologia de solución:
*Aplicar la transformada de LaPlace a toda la ecuación (Termino a termino), de tal manera que se obtenga una ecuación algebraica en el dominio de S.

*Despejar la variable que representa la salida de la ecuación.

*Aplicar la trasnformada inversa de LaPalce a la expresión obtenida para obtener la solución en el dominio del tiempo.

## 2. Tabla de las derivadas de LaPlace en el tiempo
| En el tiempo | En LaPlace          |
|--------------|---------------------|
| x(t)         | X(s)                |
| x'(t)        | sX(s)-x(0)          |
| x"(t)        | s^2X(s)-sx(0)-x'(0) |

## 3. Ejemplos

### 3.1. 
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= \ddot{x}+3x+2x=0 "><img src="http://www.alciro.org/cgi/tex.cgi? \ddot{x}+3x+2x=0 " title=" \ddot{x}+3x+2x=0 " border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(0)=a "><img src="http://www.alciro.org/cgi/tex.cgi?x(0)=a " title="x(0)=a " border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\dot{x}(0)= b"><img src="http://www.alciro.org/cgi/tex.cgi?\dot{x}(0)= b" title="\dot{x}(0)= b" border="0" /></a>

*Aplicamos la transformada de LaPlace

 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0" title="[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0" border="0" /></a>

 *Reemplazamos condiciones iniciales

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0" title="[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0" border="0" /></a>

  *Despejamos X

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(s^2+3s+2)X(S)= as+b+3a"><img src="http://www.alciro.org/cgi/tex.cgi?(s^2+3s+2)X(S)= as+b+3a" title="(s^2+3s+2)X(S)= as+b+3a" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}"><img src="http://www.alciro.org/cgi/tex.cgi?X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}" title="X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}" border="0" /></a>

  *Transformada inversa

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}'(t)} =sf(s)-f(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}'(t)} =sf(s)-f(0)" title="L{{f}'(t)} =sf(s)-f(0)" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)" title="L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)" title="L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)" border="0" /></a>

   <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]"><img src="http://www.alciro.org/cgi/tex.cgi?x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]" title="x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]" border="0" /></a>

  RESPUESTA:
  
  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(2a+b)e^{-1}-(a+b)e^{-2t}} "><img src="http://www.alciro.org/cgi/tex.cgi?(2a+b)e^{-1}-(a+b)e^{-2t}} " title="(2a+b)e^{-1}-(a+b)e^{-2t}}
 " border="0" /></a>
### 3.2. 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\ddot{x}+2\dot{x}+5x=3"><img src="http://www.alciro.org/cgi/tex.cgi?\ddot{x}+2\dot{x}+5x=3" title="\ddot{x}+2\dot{x}+5x=3" border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(0)=0"><img src="http://www.alciro.org/cgi/tex.cgi?x(0)=0" title="x(0)=0" border="0" /></a> ; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\dot{x}(0)=0"><img src="http://www.alciro.org/cgi/tex.cgi?\dot{x}(0)=0" title="\dot{x}(0)=0" border="0" /></a>

*Aplicamos la transformada de LaPlace

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}" title="[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}" border="0" /></a>


<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}" title="[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}" title="[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)(s^2+2s+5)\frac{3}{5}"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)(s^2+2s+5)\frac{3}{5}" title="x(s)(s^2+2s+5)\frac{3}{5}" border="0" /></a>

*Despejamos X y resolvemos

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=xs=\frac{3}{s(s^2+2s+5)}=\frac{A}{S}+\frac{Bs+C}{s^2+2s+5}"><img src="http://www.alciro.org/cgi/tex.cgi?xs=\frac{3}{s(s^2+2s+5)}=\frac{A}{S}+\frac{Bs+C}{s^2+2s+5}" title="xs=\frac{3}{s(s^2+2s+5)}=\frac{A}{S}+\frac{Bs+C}{s^2+2s+5}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s= -1 \pm  2i"><img src="http://www.alciro.org/cgi/tex.cgi?s= -1 \pm  2i" title="s= -1 \pm  2i" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=A=\frac{3s}{s(s^2+2s+5)}\mid _{s=0}"><img src="http://www.alciro.org/cgi/tex.cgi?A=\frac{3s}{s(s^2+2s+5)}\mid _{s=0}" title="A=\frac{3s}{s(s^2+2s+5)}\mid _{s=0}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=A=\frac{3}{5}"><img src="http://www.alciro.org/cgi/tex.cgi?A=\frac{3}{5}" title="A=\frac{3}{5}" border="0" /></a> = 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{3}{5}\mid _{s=1+2i}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{3}{5}\mid _{s=1+2i}" title="\frac{3}{5}\mid _{s=1+2i}" border="0" /></a>
= <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Bs+c\mid _{s=1+2i}"><img src="http://www.alciro.org/cgi/tex.cgi?Bs+c\mid _{s=1+2i}" title="Bs+c\mid _{s=1+2i}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{3}{-1+2i}=-B+2Bi+C"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{3}{-1+2i}=-B+2Bi+C" title="\frac{3}{-1+2i}=-B+2Bi+C" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{3}{-1+2i}*\frac{(-1+2i)}{(-1+2i)}=-B+2Bi+C"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{3}{-1+2i}*\frac{(-1+2i)}{(-1+2i)}=-B+2Bi+C" title="\frac{3}{-1+2i}*\frac{(-1+2i)}{(-1+2i)}=-B+2Bi+C" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{-3-6i}{5}= -B+2B+C"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{-3-6i}{5}= -B+2B+C" title="\frac{-3-6i}{5}= -B+2B+C" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{-6}{5}= 2B => B= \frac{-6}{10}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{-6}{5}= 2B => B= \frac{-6}{10}" title="\frac{-6}{5}= 2B => B= \frac{-6}{10}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=C= \frac{-3}{5}\frac{-3}{5}= \frac{-6}{5}"><img src="http://www.alciro.org/cgi/tex.cgi?C= \frac{-3}{5}\frac{-3}{5}= \frac{-6}{5}" title="C= \frac{-3}{5}\frac{-3}{5}= \frac{-6}{5}" border="0" /></a>

RESPUESTA:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L^{-1}[x(s)]=\frac{3}{5}-\frac{3}{5}e^-tcos(2t)-\frac{-3}{10}e^-tsen(2t)"><img src="http://www.alciro.org/cgi/tex.cgi?L^{-1}[x(s)]=\frac{3}{5}-\frac{3}{5}e^-tcos(2t)-\frac{-3}{10}e^-tsen(2t)" title="L^{-1}[x(s)]=\frac{3}{5}-\frac{3}{5}e^-tcos(2t)-\frac{-3}{10}e^-tsen(2t)" border="0" /></a>

# SISTEMAS MECANICOS 
Son un conjunto de elementos que transforman y transmiten movimiento y fuerza. Están compuestos por componentes físicos como motores, engranes, y mecanismos.

![image](https://github.com/user-attachments/assets/ad06efb5-f9b2-4016-aa4f-6b34a2611a47)

## Resortes
Un resorte es un objeto que puede ser deformado por una fuerza y volver a su forma original en la ausencia de esta.

## 5. Ecuaciones
Para la edición de ecuaciones debe utilizar la etiqueta '$$' al comienzo y final de la ecuación para que la ecuación quede centrada ocupando una línea. Si se quiere que la ecuación quede integrada en el texto debe utilizar la etiqueta '$' al comienzo y final de la ecuación. Las ecuaciones pueden ser editadas utilizando el código LATEX, en el siguiente enlace encuentran un editor de ecuaciones que les genera el código. http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp . Sin embargo hay muchas otras herramientas que pueden utilizar para esto.

💡**Ejemplo 1:** si se va a representar la ecuación de la ley de Ohm se puede mostrar así $R=\frac{V}{I}$ o también,

$$R=\frac{V}{I}$$

## 6. Figuras
Todas las figuras que incluya deben ser generadas por ustedes, **no utilizar las figuras de las presentaciones**. Para incluir figuras puede seguir los siguientes pasos:
* Primero escribimos ![]().
* Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
* Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.

💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## Rúbrica
| 0-1                                                                                   | 1-2                                                                                  | 2-3                                                                                                                                                                               | 3-4                                                                                                                                                                       | 4-5                                                                                                                                                                               |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Presenta menos del 10% de los temas o no presenta por  el medio y formato  solicitado | Presenta menos del 40% de los temas solicitados, y  cumple parcialmente la plantilla | Presenta menos del 60% de los temas solicitados (con descripciones, gráficos tablas, etc), y cumple  parcialmente la plantilla. No presenta la totalidad  de ejercicios resueltos | Presenta menos del 80% de los temas solicitados (con descripciones, gráficos, tablas, etc) y cumple con  la plantilla. No presenta  la totalidad de ejercicios  resueltos | Presenta el 100% de los temas vistos en clase (con descripciones, gráficos, tablas, etc), siguiendo totalmente la plantilla. presenta la  totalidad de los ejercicios solicitados |

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
