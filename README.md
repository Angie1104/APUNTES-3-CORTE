
# SOLUCION DE ECUACIONES DIFERENCIALES 

## Metodologia de solución:
* Aplicar la transformada de LaPlace a toda la ecuación (Termino a termino), de tal manera que se obtenga una ecuación algebraica en el dominio de S.

* Despejar la variable que representa la salida de la ecuación.

* Aplicar la trasnformada inversa de LaPalce a la expresión obtenida para obtener la solución en el dominio del tiempo.

## 2. Tabla de las derivadas de LaPlace en el tiempo
| En el tiempo | En LaPlace          |
|--------------|---------------------|
| x(t)         | X(s)                |
| x'(t)        | sX(s)-x(0)          |
| x"(t)        | s^2X(s)-sx(0)-x'(0) |

## 3. Ejemplos

### 3.1. 
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= \ddot{x}+3x+2x=0 "><img src="http://www.alciro.org/cgi/tex.cgi? \ddot{x}+3x+2x=0 " title=" \ddot{x}+3x+2x=0 " border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(0)=a "><img src="http://www.alciro.org/cgi/tex.cgi?x(0)=a " title="x(0)=a " border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\dot{x}(0)= b"><img src="http://www.alciro.org/cgi/tex.cgi?\dot{x}(0)= b" title="\dot{x}(0)= b" border="0" /></a>

* Aplicamos la transformada de LaPlace

 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0" title="[s^2X(s)-sx(0)-\dot{x}(0)]+3[sx(s)-x(0)]+2x(s)=0" border="0" /></a>

* Reemplazamos condiciones iniciales

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0" title="[s^2X(s)-as-b]+3[sx(s)-a]+2x(s)=0" border="0" /></a>

 * Despejamos X

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(s^2+3s+2)X(S)= as+b+3a"><img src="http://www.alciro.org/cgi/tex.cgi?(s^2+3s+2)X(S)= as+b+3a" title="(s^2+3s+2)X(S)= as+b+3a" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}"><img src="http://www.alciro.org/cgi/tex.cgi?X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}" title="X(S)=\frac{as+b+3a}{s^2+3s+2}=\frac{as+b+3a}{(s+1)(s+2)}=\frac{2a+b}{s+1}-\frac{a+b}{s+2}" border="0" /></a>

 * Transformada inversa

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}'(t)} =sf(s)-f(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}'(t)} =sf(s)-f(0)" title="L{{f}'(t)} =sf(s)-f(0)" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)" title="L{{f}''(t)} =s^2f(s)-sf(0)-f'(0)" border="0" /></a>

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)"><img src="http://www.alciro.org/cgi/tex.cgi?L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)" title="L{{f}'''(t)} =s^3f(s)-s^2f(0)-sf'(0)-f''(0)" border="0" /></a>

   <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]"><img src="http://www.alciro.org/cgi/tex.cgi?x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]" title="x(t)=L^{-1}[x(s)]=L^{-1}[\frac{2a+b}{s+1}]-L^{-1}[\frac{a+b}{s+2}]" border="0" /></a>

  RESPUESTA:
  
  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(2a+b)e^{-1}-(a+b)e^{-2t}} "><img src="http://www.alciro.org/cgi/tex.cgi?(2a+b)e^{-1}-(a+b)e^{-2t}} " title="(2a+b)e^{-1}-(a+b)e^{-2t}}
 " border="0" /></a>
### 3.2. 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\ddot{x}+2\dot{x}+5x=3"><img src="http://www.alciro.org/cgi/tex.cgi?\ddot{x}+2\dot{x}+5x=3" title="\ddot{x}+2\dot{x}+5x=3" border="0" /></a>; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(0)=0"><img src="http://www.alciro.org/cgi/tex.cgi?x(0)=0" title="x(0)=0" border="0" /></a> ; <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\dot{x}(0)=0"><img src="http://www.alciro.org/cgi/tex.cgi?\dot{x}(0)=0" title="\dot{x}(0)=0" border="0" /></a>

* Aplicamos la transformada de LaPlace

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}" title="[s^2x(S)-sx(0)-\dot{x}]+2[s(x)(s)-x(0)]+5x(s)=\frac{3}{s}" border="0" /></a>


<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}" title="[s^2x(S)-s(0)-0]+2[sx(s)-0]+5x(s)=\frac{3}{s}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}"><img src="http://www.alciro.org/cgi/tex.cgi?[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}" title="[s^2x(s)+2sx(s)+5x(s)]=\frac{3}{s}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=x(s)(s^2+2s+5)\frac{3}{5}"><img src="http://www.alciro.org/cgi/tex.cgi?x(s)(s^2+2s+5)\frac{3}{5}" title="x(s)(s^2+2s+5)\frac{3}{5}" border="0" /></a>

* Despejamos X y resolvemos

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

## 1. Resortes
Un resorte es un objeto que puede ser deformado por una fuerza y volver a su forma original en la ausencia de esta. Para estos casos se utiliza la Ley de Hooke la cuál nos dice que dentro de ciertos límites, la fuerza requerida para estirar un objeto elástico, como un resorte de metal, es directamente proporcional a la extensión del resorte

![image](https://github.com/user-attachments/assets/faabd921-5d69-4695-9d8a-25eb5a383f60)  ![image](https://github.com/user-attachments/assets/42342f07-5d69-4067-b190-8313033f2fab)



La Ley de Hooke se representa como : <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F=kx => k(x_{1}-x_{2})"><img src="http://www.alciro.org/cgi/tex.cgi?F=kx => k(x_{1}-x_{2})" title="F=kx => k(x_{1}-x_{2})" border="0" /></a>

## 2. Amortiguadores
Un amortiguador es un elemento mecánico que genera una fuerza proporcional a la velocidad relativa entre sus extremos o también son aquellos que trabajan por fricción y se representa como: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F=b\dot{x}= b(\dot{x_{1}}-\dot{x}_{2})"><img src="http://www.alciro.org/cgi/tex.cgi?F=b\dot{x}= b(\dot{x_{1}}-\dot{x}_{2})" title="F=b\dot{x}= b(\dot{x_{1}}-\dot{x}_{2})" border="0" /></a> donde "b" es la constante de fricción viscosa

![image](https://github.com/user-attachments/assets/86f11c8a-0de9-40cc-86e3-30485113d61e)


## 3. Tipos de fricción
> *Fricción en seco:*
Es aquella que se presenta cuando un cuerpo con una superficie no lubricada se desliza sobre otra superficie lubricada.
![image](https://github.com/user-attachments/assets/a8aed297-be9f-4045-a422-78190c1fc11e)

>*Friccion por rodamiento*: Es la fuerza que se opone al movimiento de un cuerpo que rueda sobre una superficie
![image](https://github.com/user-attachments/assets/a92a3e62-eb53-488a-a020-9c7fda001588)

## 4. Sistemas Masa-Resorte-Amortiguador
Para estos modelos utilizamos: 

* Ley de Hooke: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=FR= K_{2}*X"><img src="http://www.alciro.org/cgi/tex.cgi?FR= K_{2}*X" title="FR= K_{2}*X" border="0" /></a>

* Fricción viscosa: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Ff= K_{1}Vm"><img src="http://www.alciro.org/cgi/tex.cgi?Ff= K_{1}Vm" title="Ff= K_{1}Vm" border="0" /></a>

* Leyes de Newton= <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F= m*a"><img src="http://www.alciro.org/cgi/tex.cgi?F= m*a" title="F= m*a" border="0" /></a>

### Ejemplo

![image](https://github.com/user-attachments/assets/36b5a84c-964a-4658-b8ab-84f993f0ce58)

![image](https://github.com/user-attachments/assets/c173a626-9e99-4dac-abba-781a7efd66ee)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U-FR-Ff= m*a"><img src="http://www.alciro.org/cgi/tex.cgi?U-FR-Ff= m*a" title="U-FR-Ff= m*a" border="0" /></a>

*FR podemos reemplazarla en la ecuación por: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=K_{2}*y(t)"><img src="http://www.alciro.org/cgi/tex.cgi?K_{2}*y(t)" title="K_{2}*y(t)" border="0" /></a>*

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U(t)-K_{2}*y(t)-Ff= m*a"><img src="http://www.alciro.org/cgi/tex.cgi?U(t)-K_{2}*y(t)-Ff= m*a" title="U(t)-K_{2}*y(t)-Ff= m*a" border="0" /></a>

*Ff podemos reemplazarla por: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Ff= K_{1}*\frac{dy(t)}{dt}= K_{1}* y'(t)"><img src="http://www.alciro.org/cgi/tex.cgi?Ff= K_{1}*\frac{dy(t)}{dt}= K_{1}* y'(t)" title="Ff= K_{1}*\frac{dy(t)}{dt}= K_{1}* y'(t)" border="0" /></a>*

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U(t)-K_{2}* y(t)-K_{1}*\frac{dy(t)}{dt}= m*a"><img src="http://www.alciro.org/cgi/tex.cgi?U(t)-K_{2}* y(t)-K_{1}*\frac{dy(t)}{dt}= m*a" title="U(t)-K_{2}* y(t)-K_{1}*\frac{dy(t)}{dt}= m*a" border="0" /></a>

*a podemos reemplazarla por: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq={y}\'\'(t)"><img src="http://www.alciro.org/cgi/tex.cgi?{y}\'\'(t)" title="{y}\'\'(t)" border="0" /></a>*

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U(t)-K_{2}*y(t)-K_{1}*\frac{dy(t)}{dt}= m* {y}\'\'(t)"><img src="http://www.alciro.org/cgi/tex.cgi?U(t)-K_{2}*y(t)-K_{1}*\frac{dy(t)}{dt}= m* {y}\'\'(t)" title="U(t)-K_{2}*y(t)-K_{1}*\frac{dy(t)}{dt}= m* {y}\'\'(t)" border="0" /></a>

# SISTEMAS ACOPLADOS
![image](https://github.com/user-attachments/assets/7f725a87-a5f6-47b9-b37a-687dfb7cbc24)

Para este ejemplo hay que tener en cuenta que la distancia de la enlongación del resorte 2 depende del movimiento de ambas masas, para esto tenemos que hacer dos diagramas de cuerpo libre uno para cada masa.

MASA 1:

![image](https://github.com/user-attachments/assets/a5cfa9ca-585a-4fa7-a2ab-a6b10568b360)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U-FR1-FR2-Ff= m1*am1"><img src="http://www.alciro.org/cgi/tex.cgi?U-FR1-FR2-Ff= m1*am1" title="U-FR1-FR2-Ff= m1*am1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U(t)-K1*X_{1}(t)- K2*(X_{1}(t)-X_{2}(t))-\frac{b*d(X_{1}(t)-X_{2}(t))}{dt}= m1*\frac{d^2X_{1}(t)}{dt^2}"><img src="http://www.alciro.org/cgi/tex.cgi?U(t)-K1*X_{1}(t)- K2*(X_{1}(t)-X_{2}(t))-\frac{b*d(X_{1}(t)-X_{2}(t))}{dt}= m1*\frac{d^2X_{1}(t)}{dt^2}" title="U(t)-K1*X_{1}(t)- K2*(X_{1}(t)-X_{2}(t))-\frac{b*d(X_{1}(t)-X_{2}(t))}{dt}= m1*\frac{d^2X_{1}(t)}{dt^2}" border="0" /></a>

MASA 2:

![image](https://github.com/user-attachments/assets/c2b5b66e-e713-4e36-a002-bebd42569344)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=FR2+Ff-FR3= m2*am2"><img src="http://www.alciro.org/cgi/tex.cgi?FR2+Ff-FR3= m2*am2" title="FR2+Ff-FR3= m2*am2" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=K2*(X_{1}(t)-X_{2}(t))+b*\frac{d(X_{1}(t)-X_{2}(t))}{dt}-K3*X_{2}(t)= m2*\frac{d^2X_{2(t)}}{dt^2}"><img src="http://www.alciro.org/cgi/tex.cgi?K2*(X_{1}(t)-X_{2}(t))+b*\frac{d(X_{1}(t)-X_{2}(t))}{dt}-K3*X_{2}(t)= m2*\frac{d^2X_{2(t)}}{dt^2}" title="K2*(X_{1}(t)-X_{2}(t))+b*\frac{d(X_{1}(t)-X_{2}(t))}{dt}-K3*X_{2}(t)= m2*\frac{d^2X_{2(t)}}{dt^2}" border="0" /></a>

# SISTEMA ROTACIONAL
Es un fenomeno mecanico pero la naturalez del movimiento cambia y ahora pasa a ser movimiento angular.

![image](https://github.com/user-attachments/assets/5d9d39ef-18e3-4cfa-8383-7e5518cbb1a0)

Para este tipo de movimientos aplicamos las leyes comparables al movimiento lineal:
* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=FR= K*\varphi "><img src="http://www.alciro.org/cgi/tex.cgi?FR= K*\varphi " title="FR= K*\varphi " border="0" /></a> ( <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\varphi "><img src="http://www.alciro.org/cgi/tex.cgi?\varphi " title="\varphi " border="0" /></a> es el angulo de tensión)

* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\varphi "><img src="http://www.alciro.org/cgi/tex.cgi?\varphi " title="\varphi " border="0" /></a> ( <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= \frac{d\varphi }{dt}"><img src="http://www.alciro.org/cgi/tex.cgi? \frac{d\varphi }{dt}" title=" \frac{d\varphi }{dt}" border="0" /></a> es la velocidad angular)

* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T= J*\frac{d\varphi^{2}}{dt^{2}}"><img src="http://www.alciro.org/cgi/tex.cgi?T= J*\frac{d\varphi^{2}}{dt^{2}}" title="T= J*\frac{d\varphi^{2}}{dt^{2}}" border="0" /></a> ( <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J"><img src="http://www.alciro.org/cgi/tex.cgi?J" title="J" border="0" /></a> es el momento de incercia)

# TRABAJO, ENERGÍA Y POTENCIA
## 1. Trabajo
Es la energía transferida por una fuerza que actúa sobre un objeto mientras este se desplaza y se representa por medio de: 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= w=Fx"><img src="http://www.alciro.org/cgi/tex.cgi? w=Fx" title=" w=Fx" border="0" /></a>
## 2. Energía 
Capacidad para realizar fuerza y trabajo.
### 2.1 Energía  Potencial
En los sistemas mecanicos la energía cambia de acuerdo a su posición, los resortes y las masas alamcenas energía potencial la cuál es equivalente al trabajo realizado por la fuerza exterma.

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=u=\int_{a}^{b}mgdx= mgh"><img src="http://www.alciro.org/cgi/tex.cgi?u=\int_{a}^{b}mgdx= mgh" title="u=\int_{a}^{b}mgdx= mgh" border="0" /></a>

### 2.2 Energía Cinetica
Solamente los elementos de inercia pueden almacenar energía cinetica

* Movimiento lineal: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T= \frac{1}{2} mv^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?T= \frac{1}{2} mv^{2}" title="T= \frac{1}{2} mv^{2}" border="0" /></a>

* Movimiento rotacional: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T=\frac{1}{2}J\theta ^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?T=\frac{1}{2}J\theta ^{2}" title="T=\frac{1}{2}J\theta ^{2}" border="0" /></a>

Un cambio en la energía cinetica es el trabajo realizado sobre una masa por la aplicación de una fuerza que acelera o desacelera

 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= \Delta (T)=\Delta (w)=\int_{x{1}}^{x{2}}Fdx=\int_{x{1}}^{x{2}} F\frac{dx}{dt}dt"><img src="http://www.alciro.org/cgi/tex.cgi? \Delta (T)=\Delta (w)=\int_{x{1}}^{x{2}}Fdx=\int_{x{1}}^{x{2}} F\frac{dx}{dt}dt" title=" \Delta (T)=\Delta (w)=\int_{x{1}}^{x{2}}Fdx=\int_{x{1}}^{x{2}} F\frac{dx}{dt}dt" border="0" /></a>

* Lineal: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq==\frac{1}{2}mv_{2}^{2}-\frac{1}{2}mv_{1}^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?=\frac{1}{2}mv_{2}^{2}-\frac{1}{2}mv_{1}^{2}" title="=\frac{1}{2}mv_{2}^{2}-\frac{1}{2}mv_{1}^{2}" border="0" /></a>

* Rotacional: <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq==\frac{1}{2}J\theta _{2}^{2}-\frac{1}{2}J\theta _{1}^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?=\frac{1}{2}J\theta _{2}^{2}-\frac{1}{2}J\theta _{1}^{2}" title="=\frac{1}{2}J\theta _{2}^{2}-\frac{1}{2}J\theta _{1}^{2}" border="0" /></a> 

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
