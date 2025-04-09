
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

## 3. Potencia 
La potencia es la realización de trabajo que varia con respecto al tiempo

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= \frac{dw}{dt}"><img src="http://www.alciro.org/cgi/tex.cgi?P= \frac{dw}{dt}" title="P= \frac{dw}{dt}" border="0" /></a>
### 3.1 Potencia en un resorte
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= kx\dot{x}"><img src="http://www.alciro.org/cgi/tex.cgi?P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= kx\dot{x}" title="P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= kx\dot{x}" border="0" /></a>

* Sabemos que <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=U= \frac{1}{2}kx^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?U= \frac{1}{2}kx^{2}" title="U= \frac{1}{2}kx^{2}" border="0" /></a>  podemos reemplazarla

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= Kx\dot{x}=\dot{U}"><img src="http://www.alciro.org/cgi/tex.cgi?P= Kx\dot{x}=\dot{U}" title="P= Kx\dot{x}=\dot{U}" border="0" /></a>
### 3.2 Potencia en una masa
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= m\bar{x}\dot{x}"><img src="http://www.alciro.org/cgi/tex.cgi?P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= m\bar{x}\dot{x}" title="P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{x}= m\bar{x}\dot{x}" border="0" /></a>
* Sabemos que <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T= \frac{1}{2}mv^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?T= \frac{1}{2}mv^{2}" title="T= \frac{1}{2}mv^{2}" border="0" /></a> podemos reemplazar

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= m\bar{x}\dot{x}= m\dot{v}v= T"><img src="http://www.alciro.org/cgi/tex.cgi?P= m\bar{x}\dot{x}= m\dot{v}v= T" title="P= m\bar{x}\dot{x}= m\dot{v}v= T" border="0" /></a>  

### 3.3 Potencia disipada en un amortiguador
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{X}"><img src="http://www.alciro.org/cgi/tex.cgi?P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{X}" title="P= \frac{dw}{dt}= \frac{Fdx}{dt}= F\dot{X}" border="0" /></a>
* Sabemos que <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=F= b\dot{X}"><img src="http://www.alciro.org/cgi/tex.cgi?F= b\dot{X}" title="F= b\dot{X}" border="0" /></a> podemos reemplazar

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P= b\dot{x}^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?P= b\dot{x}^{2}" title="P= b\dot{x}^{2}" border="0" /></a>

## 4. Sistema Conservativo
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta(T+U)= \Delta (w)"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta(T+U)= \Delta (w)" title="\Delta(T+U)= \Delta (w)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta(T+U)= 0"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta(T+U)= 0" title="\Delta(T+U)= 0" border="0" /></a> (T+U seran constantes)
### Ejemplo
![image](https://github.com/user-attachments/assets/3a612bcf-1f06-4e32-950d-06d0a4fe81c9)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T+U= \frac{1}{2}m\dot{x}+\frac{1}{2}Kx^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?T+U= \frac{1}{2}m\dot{x}+\frac{1}{2}Kx^{2}" title="T+U= \frac{1}{2}m\dot{x}+\frac{1}{2}Kx^{2}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{d}{d(t)}(T+U)=m\dot{x}\bar{x}+kx\dot{x}=(m\bar{x}+kx)\dot{x}=0"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{d}{d(t)}(T+U)=m\dot{x}\bar{x}+kx\dot{x}=(m\bar{x}+kx)\dot{x}=0" title="\frac{d}{d(t)}(T+U)=m\dot{x}\bar{x}+kx\dot{x}=(m\bar{x}+kx)\dot{x}=0" border="0" /></a>

## 5. Conversión movimiento traslacional-rotacional 
### Casos Frecuentes

* Tornillo sinfin

![image](https://github.com/user-attachments/assets/c52b7a11-93b2-44d8-b4f4-1ae3222e9552)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J= \frac{w}{g}(\frac{L}{2\pi })^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?J= \frac{w}{g}(\frac{L}{2\pi })^{2}" title="J= \frac{w}{g}(\frac{L}{2\pi })^{2}" border="0" /></a>

* Banda de poleas

![image](https://github.com/user-attachments/assets/d9a315d5-1209-40c6-90c2-bf5d4ae4d7bc)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J= Mr^{2}=\frac{w}{g}*r^{2}"><img src="http://www.alciro.org/cgi/tex.cgi?J= Mr^{2}=\frac{w}{g}*r^{2}" title="J= Mr^{2}=\frac{w}{g}*r^{2}" border="0" /></a>

# SISTEMAS ELECTRICOS
## Circuitos RLC
Es el fenomeno fisico que modela este comportamiento en las Leyes de Kirchoff y está compuesto por:

![image](https://github.com/user-attachments/assets/e841f9a3-2e95-41f6-ab77-7f8817d7ad2c)

* Ley de Ohm <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=R=\frac{v(t)}{i(t)}"><img src="http://www.alciro.org/cgi/tex.cgi?R=\frac{v(t)}{i(t)}" title="R=\frac{v(t)}{i(t)}" border="0" /></a>

* Carga de un condensador <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=i(t)= C*\frac{dv(t)}{dt}"><img src="http://www.alciro.org/cgi/tex.cgi?i(t)= C*\frac{dv(t)}{dt}" title="i(t)= C*\frac{dv(t)}{dt}" border="0" /></a>

* Carga de un inductor <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=V(t)= L*\frac{di(t)}{dt}"><img src="http://www.alciro.org/cgi/tex.cgi?V(t)= L*\frac{di(t)}{dt}" title="V(t)= L*\frac{di(t)}{dt}" border="0" /></a>
### Ejemplos
### 1.1

![image](https://github.com/user-attachments/assets/60515aa8-0c26-4ea5-860c-043bebec86fc)

* Aplicamos Ley de Kirchoff

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=-U+VR+VL+VC=O"><img src="http://www.alciro.org/cgi/tex.cgi?-U+VR+VL+VC=O" title="-U+VR+VL+VC=O" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=-U(t)+i(t)*R+L\frac{di(t)}{dt}+y(t)=O"><img src="http://www.alciro.org/cgi/tex.cgi?-U(t)+i(t)*R+L\frac{di(t)}{dt}+y(t)=O" title="-U(t)+i(t)*R+L\frac{di(t)}{dt}+y(t)=O" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=-U(t)+C\frac{dy(t)}{dt}*R+L\frac{d)}{dt}(C\frac{dy(t)}{dt}+y(t)=O"><img src="http://www.alciro.org/cgi/tex.cgi?-U(t)+C\frac{dy(t)}{dt}*R+L\frac{d)}{dt}(C\frac{dy(t)}{dt}+y(t)=O" title="-U(t)+C\frac{dy(t)}{dt}*R+L\frac{d)}{dt}(C\frac{dy(t)}{dt}+y(t)=O" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=-U(t)+RC\frac{dy(t)}{dt}+LC\frac{d^{2}y(t)}{dt^{2}}+y(t)=O"><img src="http://www.alciro.org/cgi/tex.cgi?-U(t)+RC\frac{dy(t)}{dt}+LC\frac{d^{2}y(t)}{dt^{2}}+y(t)=O" title="-U(t)+RC\frac{dy(t)}{dt}+LC\frac{d^{2}y(t)}{dt^{2}}+y(t)=O" border="0" /></a>

### 1.2

R1: 50 Ohm; R2: 20 Ohm; C: 100 microFaradios; Señal cuadrada 5Hz; 5 V

![image](https://github.com/user-attachments/assets/4691aa32-3fca-4f71-bd2b-def03907550f)

* Forma Manual

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=u(t)=R_{1}(t)+R_{2}i(t)+vc(t)=0"><img src="http://www.alciro.org/cgi/tex.cgi?u(t)=R_{1}(t)+R_{2}i(t)+vc(t)=0" title="u(t)=R_{1}(t)+R_{2}i(t)+vc(t)=0" border="0" /></a>

Como <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=vc(t)= y(t) =i(t) =C\frac{dy}{dt}"><img src="http://www.alciro.org/cgi/tex.cgi?vc(t)= y(t) =i(t) =C\frac{dy}{dt}" title="vc(t)= y(t) =i(t) =C\frac{dy}{dt}" border="0" /></a> reemplazamos 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=u(t)=(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)"><img src="http://www.alciro.org/cgi/tex.cgi?u(t)=(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)" title="u(t)=(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)" border="0" /></a>

* Organizamos y sustituimos valores

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)=u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)=u(t)" title="(R_{1}+R_{2}) C\frac{dy}{dt}+ y(t)=u(t)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(50+20)(100x10^{-6}) \frac{dy}{dt}+ y(t)=u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?(50+20)(100x10^{-6}) \frac{dy}{dt}+ y(t)=u(t)" title="(50+20)(100x10^{-6}) \frac{dy}{dt}+ y(t)=u(t)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=0.007 \frac{dy}{dt}+ y(t)=u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?0.007 \frac{dy}{dt}+ y(t)=u(t)" title="0.007 \frac{dy}{dt}+ y(t)=u(t)" border="0" /></a>

* ODE45

```
clc;
clear;
close all;

% Parámetros
R1 = 50;
R2 = 20;
C = 100e-6;
RC_total = (R1 + R2) * C;  % 0.007

% Entrada: señal cuadrada de 5 Hz y 5V
u = @(t) 5 * double(mod(floor(2*5*t),2) == 0);

% Ecuación diferencial
odefun = @(t, y) (1/RC_total)*(u(t) - y);

% Simulación
tspan = [0 1];   
y0 = 0;
[t, y] = ode45(odefun, tspan, y0);

% Graficar respuesta
plot(t, y, 'b', 'LineWidth', 2);
xlabel('Tiempo [s]');
ylabel('Voltaje en el capacitor y(t)');
title('Respuesta a señal cuadrada de 5 Hz y 5V');
grid on;

```
![image](https://github.com/user-attachments/assets/3189e7d4-5785-416b-a65a-52c8b0eb2379)

* SIMULINK

![image](https://github.com/user-attachments/assets/4a0ca3aa-064b-484b-8195-fd756d3d7641)

![image](https://github.com/user-attachments/assets/b60e2e3c-1d83-481f-93fd-f2ec4d589c43)


## Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
