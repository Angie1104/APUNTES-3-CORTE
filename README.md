
# FUNCIÓN DE TRANSFERENCIA 
Una función de transferencia es un modelo matemático que, a través de un cociente, relaciona la respuesta de un sistema (modelada o señal de salida) con una señal de entrada o excitación (también modelada). En la teoría de control, a menudo se usan las funciones de transferencia para caracterizar las relaciones de entrada y salida de componentes o de sistemas que se describen mediante ecuaciones diferenciales lineales e invariantes en el tiempo.

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{salida}{entrada}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{salida}{entrada}" title="\frac{salida}{entrada}" border="0" /></a>  =  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)}" title="\frac{Y(s)}{U(s)}" border="0" /></a>


* Todas las condiciones iniciales de la ecuación diferencial son iguales a 0

## CLASIFICACIÓN DE LAS FUNCIONES DE TRANSFERENCIA
* Una función de transferencia se puede expresar como:

  <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{N(s)}{D(s)}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{N(s)}{D(s)}" title="G(s)=\frac{N(s)}{D(s)}" border="0" /></a>
* Donde N(s) y D(s) son polinomios en la variable "S"
* Se tienen 3 casos posibles:
  * n>m impropia
  * m>n estrictamente propia
  * n=m bipropia
### Ejemplos
![image](https://github.com/user-attachments/assets/1b89068c-e393-4f8d-9a47-71dc4a8482d0)
## CEROS DE UNA FUNCIÓN DE TRANSFERENCIA 
* Si se iguala N(s) a 0 se obtienen los valores de "S" que cumplen con la condición
* Si el numerador se hace 0 toda la función de trasnferencia se vuelve cero de ahí el nombre para estos valores de "S"
* Estos valores pueden ser reales o complejos por lo tanto se pueden ubicar en el plano cartesiano 
### Ejemplo
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}"><img src="http://www.alciro.org/cgi/tex.cgi?H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}" title="H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s^{2}+4s+3= 0"><img src="http://www.alciro.org/cgi/tex.cgi?s^{2}+4s+3= 0" title="s^{2}+4s+3= 0" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(s+1)(s+3)=0"><img src="http://www.alciro.org/cgi/tex.cgi?(s+1)(s+3)=0" title="(s+1)(s+3)=0" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s=-1"><img src="http://www.alciro.org/cgi/tex.cgi?s=-1" title="s=-1" border="0" /></a> , <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s=-3"><img src="http://www.alciro.org/cgi/tex.cgi?s=-3" title="s=-3" border="0" /></a>

![image](https://github.com/user-attachments/assets/fd0dfb28-cff7-4edb-a932-f10f6ef27b79)

## POLOS DE UNA FUNCIÓN DE TRANSFERENCIA 
* Si se iguala D(s) a 0 se obtienen los valores de "S" que cumplen con la condición
* Si el denominador se hace 0 toda la función de transferencia se hace infinito de ahí el nombre para estos valores de "S"
* Estos valores pueden ser reales o complejos por lo tanto se pueden ubicar en el plano cartesiano
### Ejemplos
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}"><img src="http://www.alciro.org/cgi/tex.cgi?H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}" title="H(s)= \frac{s^{2}+4s+3}{s^{2}+6s+8}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s^{2}+6s+8=0"><img src="http://www.alciro.org/cgi/tex.cgi?s^{2}+6s+8=0" title="s^{2}+6s+8=0" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=(s+2)(s+4)= 0"><img src="http://www.alciro.org/cgi/tex.cgi?(s+2)(s+4)= 0" title="(s+2)(s+4)= 0" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s=-2"><img src="http://www.alciro.org/cgi/tex.cgi?s=-2" title="s=-2" border="0" /></a> , <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s=-4"><img src="http://www.alciro.org/cgi/tex.cgi?s=-4" title="s=-4" border="0" /></a>

![image](https://github.com/user-attachments/assets/6eca7eb0-d3f2-461b-8f83-de6072fbaadc)

## GRADO DE UNA FUNCIÓN DE TRANSFERENCIA
* Otras forma de clasificar las funciones de transferencia es por su orden o grado
* Esto lo define el polinomio caracteristico

![image](https://github.com/user-attachments/assets/7fe0ee9f-e153-4f74-abc0-42a9d9735cc7)

# TEOREMA DEL VALOR FINAL 
* El error en estado estacionario corresponde al error medido en <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=t=\infty "><img src="http://www.alciro.org/cgi/tex.cgi?t=\infty " title="t=\infty " border="0" /></a>
* Es posible aprovechar el teorema del valor final para saber el valor final del error

 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\displaystyle \lim_{t \to \infty } f(t) = \displaystyle \lim_{s \to 0 } sF(s)"><img src="http://www.alciro.org/cgi/tex.cgi?\displaystyle \lim_{t \to \infty } f(t) = \displaystyle \lim_{s \to 0 } sF(s)" title="\displaystyle \lim_{t \to \infty } f(t) = \displaystyle \lim_{s \to 0 } sF(s)" border="0" /></a>
### Ejemplo
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{Y(s)}{U(s)}=\frac{4}{5s+1}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{Y(s)}{U(s)}=\frac{4}{5s+1}" title="G(s)=\frac{Y(s)}{U(s)}=\frac{4}{5s+1}" border="0" /></a>
* Si la entrada es un escalon

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= \frac{\frac{4}{s}}{5s+1}"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= \frac{\frac{4}{s}}{5s+1}" title="Y(s)= \frac{\frac{4}{s}}{5s+1}" border="0" /></a>

* El valor final de Y(s) se puede calcular aplicando el teorema del valor final:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\lim_{ s\to 0}sY(s)=\lim_{s \to 0}S * \frac{\frac{4}{s}}{5s+1}"><img src="http://www.alciro.org/cgi/tex.cgi?\lim_{ s\to 0}sY(s)=\lim_{s \to 0}S * \frac{\frac{4}{s}}{5s+1}" title="\lim_{ s\to 0}sY(s)=\lim_{s \to 0}S * \frac{\frac{4}{s}}{5s+1}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\lim_{ s\to 0}\frac{4}{5s+1}=4"><img src="http://www.alciro.org/cgi/tex.cgi?\lim_{ s\to 0}\frac{4}{5s+1}=4" title="\lim_{ s\to 0}\frac{4}{5s+1}=4" border="0" /></a>

* Código en Matlab

```
clc;
clc;
clear;
close all;

% Parámetros
t = 0:0.1:45;        % Tiempo de simulación
y = zeros(size(t));  % Inicializar salida
dt = t(2) - t(1);     % Paso de tiempo
u = ones(size(t));   % Entrada escalón

% Simulación por método de Euler
for k = 1:length(t)-1
    dy = (4*u(k) - y(k)) / 5;     % Derivada según la ecuación
    y(k+1) = y(k) + dy * dt;      % Integración por pasos
end

% Graficar resultado
plot(t, y, 'b', 'LineWidth', 2);
grid on;
title('Respuesta al Escalón ');
xlabel('Tiempo (s)');
ylabel('Salida y(t)');
```
![image](https://github.com/user-attachments/assets/1287853d-8748-4ea5-adca-8282ecb9a8b0)

# MODELAMIENTO DE SISTEMAS CON DIAGRAMAS DE BLOQUES
## MODELOS DE SISTEMAS COMPLEJOS
* Se podrían modelar sistemas como un todo hallando las funciones de transferencia de cada componente
* Otro enfoque es utilizar modelos ya desarrollados ampliamente para construir modelos más complejos
* Aún usando este enfoque hay muchos tipos de procesos y dispositivos
### SOLENOIDE
* Un solenoide está formado por un circuito eléctrico, un acoplamiento electromecánico (transductor) y un sistema mecánico de traslación.

![image](https://github.com/user-attachments/assets/64f79d15-c074-4988-a816-6dc7368d0f7a)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L\frac{di}{dt}+Ri= v(t)"><img src="http://www.alciro.org/cgi/tex.cgi?L\frac{di}{dt}+Ri= v(t)" title="L\frac{di}{dt}+Ri= v(t)" border="0" /></a> 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=I(s)= V(s)\frac{1}{Ls+R}"><img src="http://www.alciro.org/cgi/tex.cgi?I(s)= V(s)\frac{1}{Ls+R}" title="I(s)= V(s)\frac{1}{Ls+R}" border="0" /></a>
*  El electroimán produce una fuerza mecánica proporcional a la corriente en el embobinado
*  El electroimán atrae una masa acoplada por medio de un resorte y se considera el mortiguamiento dado por la envolvente de la bobina

![image](https://github.com/user-attachments/assets/de946117-cc73-4c50-b833-a55cbf1ebf9b)  


## REPRESENTACION EN BLOQUES

![image](https://github.com/user-attachments/assets/fbf900ff-0474-401d-9b52-a7ee01e7f00d)  ![image](https://github.com/user-attachments/assets/b45777f7-c923-4d4f-a848-a3bba604e7f7)

# MOTOR DC
El motor de corriente continua, denominado también motor de corriente directa, motor CC o motor DC es una máquina que convierte energía eléctrica en energía mecánica, provocando un movimiento rotatorio, gracias a la acción de un campo magnético.

![image](https://github.com/user-attachments/assets/f5270690-cc30-4f2b-81e9-93fc3eef2641)

## MOTOR DC CORRIENTE DE CAMPO  
  
* Circuito electromagnetico:

![image](https://github.com/user-attachments/assets/b40b39c8-53da-4957-a476-2f1c556095a6)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{c}\frac{di_{c}}{dt}+ R_{c}i_{c}=v_{c}(t)"><img src="http://www.alciro.org/cgi/tex.cgi?L_{c}\frac{di_{c}}{dt}+ R_{c}i_{c}=v_{c}(t)" title="L_{c}\frac{di_{c}}{dt}+ R_{c}i_{c}=v_{c}(t)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=I_{c}(s)=V_{c}\frac{1}{(sL_{c}+R_{c})}"><img src="http://www.alciro.org/cgi/tex.cgi?I_{c}(s)=V_{c}\frac{1}{(sL_{c}+R_{c})}" title="I_{c}(s)=V_{c}\frac{1}{(sL_{c}+R_{c})}" border="0" /></a>
* El flujo Φ en el entrehierro es proporcional a la corriente de campo

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\phi = K_{c}i_{c}"><img src="http://www.alciro.org/cgi/tex.cgi?\phi = K_{c}i_{c}" title="\phi = K_{c}i_{c}" border="0" /></a>

* El torque desarrollado es proporcional al Φ y a la corriente de armadura

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T_{m}=K_{a}i_{a}(t)K_{c}i_{c}(t)"><img src="http://www.alciro.org/cgi/tex.cgi?T_{m}=K_{a}i_{a}(t)K_{c}i_{c}(t)" title="T_{m}=K_{a}i_{a}(t)K_{c}i_{c}(t)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)" title="T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)" border="0" /></a>

* El torque aplicado a la carga es el desarrollado por el motor menos la inercia de la carga

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T_{c}(s)=T_{m}(s)-T_{p}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?T_{c}(s)=T_{m}(s)-T_{p}(s)" title="T_{c}(s)=T_{m}(s)-T_{p}(s)" border="0" /></a>

* El torque aplicado (parte mecánica) a la carga se comporta como un Sistema rotacional clásico que considera la inercia y la fricción mecánica

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=J\frac{d^{2}\theta }{dt^{2}}+b\frac{d\theta }{dt}+k\theta=\tau (t)"><img src="http://www.alciro.org/cgi/tex.cgi?J\frac{d^{2}\theta }{dt^{2}}+b\frac{d\theta }{dt}+k\theta=\tau (t)" title="J\frac{d^{2}\theta }{dt^{2}}+b\frac{d\theta }{dt}+k\theta=\tau (t)" border="0" /></a>

* La conexión de los modelos se realiza de la siguiente manera:

![image](https://github.com/user-attachments/assets/bd4cadca-7f76-43a7-8214-4a804307deb5)  ![image](https://github.com/user-attachments/assets/c8df3a23-5b0c-4606-b911-bedd2cf11353)

![image](https://github.com/user-attachments/assets/19e24615-ce9b-4ffc-b6a6-7c43ae3ebbf1)

## MOTOR DC CORRIENTE DE ARMADURA

![image](https://github.com/user-attachments/assets/6de8dd96-6f93-4b72-94e3-17fccd2fd55a)

* La corriente de campo se asume constate por lo tanto el Torque es:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)" title="T_{m}(s)=(K_{a}K_{c}I_{a})I_{c}(s)= K_{m}I_{c}(s)" border="0" /></a>

* La corriente de armadura se relaciona con el voltaje aplicado a la armadura por:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=V_{a}(s)=(sL_{a}+R_{a})I_{a}(s)+V_{b}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?V_{a}(s)=(sL_{a}+R_{a})I_{a}(s)+V_{b}(s)" title="V_{a}(s)=(sL_{a}+R_{a})I_{a}(s)+V_{b}(s)" border="0" /></a>

* El voltaje inducido en la armadura es proporcional a la velocidad angular del eje:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=V_{a}(s)=(sL_{a} R_{a})I_{a}(s) V_{b}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?V_{a}(s)=(sL_{a} R_{a})I_{a}(s) V_{b}(s)" title="V_{a}(s)=(sL_{a} R_{a})I_{a}(s) V_{b}(s)" border="0" /></a>
 
 <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=V_{b}(s)=K_{b}\omega(s)"><img src="http://www.alciro.org/cgi/tex.cgi?V_{b}(s)=K_{b}\omega(s)" title="V_{b}(s)=K_{b}\omega(s)" border="0" /></a>

* Combinando estas ecuaciones se obtiene

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=I_{a}(s)=\frac{V_{a}(s)-K_{b}\omega (s)}{sL_{a}+R_{a}}"><img src="http://www.alciro.org/cgi/tex.cgi?I_{a}(s)=\frac{V_{a}(s)-K_{b}\omega (s)}{sL_{a}+R_{a}}" title="I_{a}(s)=\frac{V_{a}(s)-K_{b}\omega (s)}{sL_{a}+R_{a}}" border="0" /></a>

* La parte mecánica se comporta de la misma manera que en el caso anterior:

![image](https://github.com/user-attachments/assets/3fd3a3d7-6562-497b-a695-6127fbd3c03a)

![image](https://github.com/user-attachments/assets/ff8eeff5-24dc-4335-9c41-456ca3f64a9a)

# ALGEBRA DE BLOQUES
* Una herramienta que puede ayudar a entender un poco la interacción entre varios sistemas son los diagramas de bloques
* Primer sistema de control J. Watt
* Para explicar su sistema empezó a desarrollar los diagramas de bloques

![image](https://github.com/user-attachments/assets/dc86bae0-46f3-4bb2-a1b9-f1de15879eef)
![image](https://github.com/user-attachments/assets/a503f567-d57a-4547-87f3-adcdae624989)

## ELEMENTOS DE UN DIAGRAMA DE BLOQUE
* Bloque Funcional: es un símbolo para representar la operación matemática que sobre la señal de entrada hace el bloque para producir la salida

![image](https://github.com/user-attachments/assets/a282aa75-e8c9-4820-b986-c6d916080e57)

* Las flechas en un diagrama de bloques representan señales y su dirección de flujo. Estas indican que la señal solo puede moverse en un sentido (propiedad unilateral): hacia el bloque como entrada y desde el bloque como salida.

![image](https://github.com/user-attachments/assets/d38ef71d-23fd-4942-a8ab-75a226546956)

* Punto Suma: Realiza operaciones (suma o resta) entre señales únicamente. El signo más o el signo menos en
cada punta de flecha indica si la señal debe sumarse o restarse. Es importante que las cantidades que se sumen o resten tengan las mismas dimensiones y las mismas unidades.

![image](https://github.com/user-attachments/assets/0bb7e3d6-3ffe-4d46-a2ef-6b6518855010)

* Un punto de ramificación es aquel a partir del cual la señal de un bloque va de modo concurrente a otros bloques o puntos de suma

![image](https://github.com/user-attachments/assets/60736fe0-7afd-480c-8f5e-9b96dc6bc5f3)

## INTERPRETACIÓN DEL DIAGRAMA 
La salida de un bloque funcional corresponde a la señal de entrada (Dominio s) multiplicada por por la función de transferencia del bloque.

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= U(s)*G(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= U(s)*G(s)" title="Y(s)= U(s)*G(s)" border="0" /></a>
## BLOQUES EN CASCADA

* Si se tienen 2 sistemas interconectados

![image](https://github.com/user-attachments/assets/3bb5a26b-71a3-47b3-81f0-9c812e5fc7da)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y_{1}(s)= U_{1}(s)*G_{1}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y_{1}(s)= U_{1}(s)*G_{1}(s)" title="Y_{1}(s)= U_{1}(s)*G_{1}(s)" border="0" /></a> , <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y_{2}(s)= U_{1}(s)*G_{2}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y_{2}(s)= U_{1}(s)*G_{2}(s)" title="Y_{2}(s)= U_{1}(s)*G_{2}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y_{2}(s)= U_{2}(s)*G_{2}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y_{2}(s)= U_{2}(s)*G_{2}(s)" title="Y_{2}(s)= U_{2}(s)*G_{2}(s)" border="0" /></a> , <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y_{2}(s)= U_{1}Y_{1}(s)*G_{2}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y_{2}(s)= U_{1}Y_{1}(s)*G_{2}(s)" title="Y_{2}(s)= U_{1}Y_{1}(s)*G_{2}(s)" border="0" /></a>

![image](https://github.com/user-attachments/assets/3bdbf49e-16e1-4c14-a2f0-addcfdda75b2)

## TABLA DE BLOQUES 

![image](https://github.com/user-attachments/assets/44aa3959-323d-4810-94de-cc312a7db907)

## LAZO DE REALIMENTACIÓN DE POSITIVO
![image](https://github.com/user-attachments/assets/95bcac4f-06b2-41a4-b1f7-7e45a46b7a94)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=E(s)=X(s)+Y_{1}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?E(s)=X(s)+Y_{1}(s)" title="E(s)=X(s)+Y_{1}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= E(s)G_{1}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= E(s)G_{1}(s)" title="Y(s)= E(s)G_{1}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y_{1}(s)= Y(s)G_{2}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y_{1}(s)= Y(s)G_{2}(s)" title="Y_{1}(s)= Y(s)G_{2}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= (X(s)+ Y{_{1}(s))G_{1}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= (X(s)+ Y{_{1}(s))G_{1}(s)" title="Y(s)= (X(s)+ Y{_{1}(s))G_{1}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= (X(s)+ Y(s)G_{2}(s))G_{1}(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= (X(s)+ Y(s)G_{2}(s))G_{1}(s)" title="Y(s)= (X(s)+ Y(s)G_{2}(s))G_{1}(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)= (X(s)G_{1}(s)+Y(s)G_{2}(s)G_{1}(s))"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)= (X(s)G_{1}(s)+Y(s)G_{2}(s)G_{1}(s))" title="Y(s)= (X(s)G_{1}(s)+Y(s)G_{2}(s)G_{1}(s))" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s) - Y(s) G_2(s) G_1(s) = X(s)  G_1(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s) - Y(s) G_2(s) G_1(s) = X(s)  G_1(s)" title="Y(s) - Y(s) G_2(s) G_1(s) = X(s)  G_1(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)(1 - G_2(s)G_1(s)) = X(s)G_1(s)"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)(1 - G_2(s)G_1(s)) = X(s)G_1(s)" title="Y(s)(1 - G_2(s)G_1(s)) = X(s)G_1(s)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{X(s)} = \frac{G_1(s)}{1 - G_2(s)G_1(s)}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{X(s)} = \frac{G_1(s)}{1G_2(s)G_1(s)}" title="\frac{Y(s)}{X(s)} = \frac{G_1(s)}{1 - G_2(s)G_1(s)}" border="0" /></a>

## REDUCCIÓN DE DIAGRAMAS
* Hallar la función de transferencia 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{x_{1}(s)} y \frac{Y(s)}{x_{2}(s)}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{x_{1}(s)} y \frac{Y(s)}{x_{2}(s)}" title="\frac{Y(s)}{x_{1}(s)} y \frac{Y(s)}{x_{2}(s)}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= Y_1(s): \\Y_1(s) = G_1(s)X_1(s) - G_2(s)X_1(s) \\Y_1(s) = \left(G_1(s) - G_2(s)\right)X_1(s) \\Y_1(s) \text{ por } G_3(s): \\Y_3(s) = G_3(s) \cdot Y_1(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\Y(s) = Y_3(s) + Y_2(s), \text{ y aquí } X_2(s) = 0 \\Y(s) = Y_3(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\\Rightarrow {\frac{Y(s)}{X_1(s)} = G_3(s)\left(G_1(s) - G_2(s)\right)}"><img src="http://www.alciro.org/cgi/tex.cgi? Y_1(s): \\Y_1(s) = G_1(s)X_1(s) - G_2(s)X_1(s) \\Y_1(s) = \left(G_1(s) - G_2(s)\right)X_1(s) \ Y_1(s) \text{ por } G_3(s): \\Y_3(s) = G_3(s) \cdot Y_1(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\Y(s) = Y_3(s) + Y_2(s), \text{ y aquí } X_2(s) = 0 \\Y(s) = Y_3(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\\Rightarrow {\frac{Y(s)}{X_1(s)} = G_3(s)\left(G_1(s) - G_2(s)\right)}" title=" Y_1(s): \\Y_1(s) = G_1(s)X_1(s) - G_2(s)X_1(s) \\Y_1(s) = \left(G_1(s) - G_2(s)\right)X_1(s) \\Y_1(s) \text{ por } G_3(s): \\Y_3(s) = G_3(s) \cdot Y_1(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\Y(s) = Y_3(s) + Y_2(s), \text{ y aquí } X_2(s) = 0 \\Y(s) = Y_3(s) = G_3(s)\left(G_1(s) - G_2(s)\right)X_1(s) \\\Rightarrow {\frac{Y(s)}{X_1(s)} = G_3(s)\left(G_1(s) - G_2(s)\right)}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq= X_2(s): \\
Y_2(s) = \frac{G_4(s)X_2(s)}{1 + G_4(s)} \\Y(s) = Y_3(s) + Y_2(s),  X_1(s) = 0 \Rightarrow Y_3(s) = 0 \\Y(s) = Y_2(s) = \frac{G_4(s)}{1 + G_4(s)}X_2(s) \\\Rightarrow \frac{Y(s)}{X_2(s)} = \frac{G_4(s)}{1 + G_4(s)}}"><img src="http://www.alciro.org/cgi/tex.cgi? X_2(s): \\Y_2(s) = \frac{G_4(s)X_2(s)}{1 + G_4(s)} \\Y(s) = Y_3(s) + Y_2(s),  X_1(s) = 0 \Rightarrow Y_3(s) = 0 \\Y(s) = Y_2(s) = \frac{G_4(s)}{1 + G_4(s)}X_2(s) \\\Rightarrow \frac{Y(s)}{X_2(s)} = \frac{G_4(s)}{1 + G_4(s)}}" title=" X_2(s): \\Y_2(s) = \frac{G_4(s)X_2(s)}{1 + G_4(s)} \\Y(s) = Y_3(s) + Y_2(s),  X_1(s) = 0 \Rightarrow Y_3(s) = 0 \\Y(s) = Y_2(s) = \frac{G_4(s)}{1 + G_4(s)}X_2(s) \\\Rightarrow \frac{Y(s)}{X_2(s)} =\frac{G_4(s)}{1 + G_4(s)}}" border="0" /></a>

![image](https://github.com/user-attachments/assets/a5137ec7-5d78-47ca-8d7c-fc6d45fc3568)

# DIAGRAMA DE FLUJO DE SEÑALES
* Este tipo de diagramas permite otra forma de representación de los sistemas más complejos
* Se utilizan para obtener de una manera más sencilla la función de transferencia total del Sistema
* La formula de Mason permite calcular la función detrasferencia de sistemas muy complejos

![image](https://github.com/user-attachments/assets/157285f7-2712-40c5-9af6-daafa464b308)

## ELEMENTOS DE LOS DIAGRAMAS DE FLUJOS DE SEÑALES
* Nodo: Representan las señales de entrada o salida del Sistema
* Se representa por medio de un círculo con una etiqueta que indique el nombre de la señal

![image](https://github.com/user-attachments/assets/bf26e0cf-a7f1-46aa-8d6a-0f514c630376)

* Flecha: Representa la relación entre las variables delsistema
 * Se representa por medio de flechas que indicando el sentido de la relación
 * La fleche sale de la señal (Nodo) de entrada y llega a la señal de salida (Nodo)
 * Se agrega una etiqueta a la flecha para indicar la función de transferencia que relaciona entrada y la salida

![image](https://github.com/user-attachments/assets/ebec1346-2bae-4e3a-9f8f-32f080a2dc7a)

## COMPARACION DIAGRAMAAS DE BLOQUES Y FLUJOS DE SEÑALES
![image](https://github.com/user-attachments/assets/fe997527-70cb-411f-8976-b6253d99d977)
### DEFINICIONES
* Camino o trayectoria: Camino o trayecto es un recorrido de ramas conectadas en el sentido de las flechas de las ramas.
* Si no se cruza ningún nodo más de una vez, el camino o trayecto es abierto
* Si el camino o trayecto finaliza en el mismo nodo del cual partió, y no cruza ningún otro más de una vez, es un camino o trayecto cerrado
* Ganancia de lazo: La ganancia de lazo es el producto de las ganancias de ramas de un lazo.
* Trayecto o camino directo: Trayecto directo es el camino o trayecto de un nodo de entrada a un nodo de salida, sin cruzar ningún nodo más de una vez.
* Ganancia de trayecto directo: La ganancia de trayecto directo es el producto de las ganancias de rama de un camino o trayecto directo.
* Lazo: Un lazo es un camino o trayecto cerrado.
* Ganancia de lazo: La ganancia de lazo es el producto de las ganancias de ramas de un lazo.

## FORMULA DE MASON
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P = \frac{1}{\Delta} \sum_k P_k \Delta_k"><img src="http://www.alciro.org/cgi/tex.cgi?P = \frac{1}{\Delta} \sum_k P_k \Delta_k" title="P = \frac{1}{\Delta} \sum_k P_k \Delta_k" border="0" /></a>

* Pk= ganancia de caminos directos
* Δ = 1 − (suma ganancias de los lazos) + (suma producto de 2 lazos que no se tocan) – (suma producto de 3 lazos que no setocan)
* Δ𝑘 = 1 −(suma ganancias lazos que no toquen la trayectoria 𝑃𝑘)+(suma ganancias 2 lazos que no toquen la trayectoria 𝑃𝑘 y no se toquen entre sí)-(suma ganancias 3 lazos que no toquen la trayectoria 𝑃𝑘 y no se toquen entre sí)
### Ejemplos
* ![image](https://github.com/user-attachments/assets/8cf2d1d7-1d50-4855-bba8-19bd5381cb53)

Ganancias de trayectorias directas: 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{1}=G_{1}G_{2}G_{3}G_{4}G_{5}"><img src="http://www.alciro.org/cgi/tex.cgi?P_{1}= G_{1}G_{2}G_{3}G_{4}G_{5}" title="P_{1}= G_{1}G_{2}G_{3}G_{4}G_{5}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{2}= G_{1}G_{6}G_{4}G_{5}"><img src="http://www.alciro.org/cgi/tex.cgi?P_{2}= G_{1}G_{6}G_{4}G_{5}" title="P_{2}= G_{1}G_{6}G_{4}G_{5}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{3}= G_{1}G_{2}G_{7}
"><img src="http://www.alciro.org/cgi/tex.cgi?P_{3}= G_{1}G_{2}G_{7}" title="P_{3}= G_{1}G_{2}G_{7}" border="0" /></a>

Ganancias de lazos:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{1} = -G_{4}H_{1} \\
L_{2}= -G_{2}G_{7}H_{2}\\L_{3}= -G_{6}G_{4}G_{5}H_{2}\\L_{4}= -G_{2}G_{3}G_{4}G_{5}H_{2}\\"><img src="http://www.alciro.org/cgi/tex.cgi?L_{1} = G_{4}H_{1} \\L_{2}= -G_{2}G_{7}H_{2}\\L_{3}= -G_{6}G_{4}G_{5}H_{2}\\L_{4}= -G_{2}G_{3}G_{4}G_{5}H_{2}\\" title="L_{1} = -G_{4}H_{1} \\L_{2}= -G_{2}G_{7}H_{2}\\L_{3}= -G_{6}G_{4}G_{5}H_{2}\\L_{4}= -G_{2}G_{3}G_{4}G_{5}H_{2}\\" border="0" /></a>

Determinante:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta = 1 - (L_{1} + L_{2} + L_{3} + L_{4}) + L_{1} L_{2}"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta = 1 - (L_{1} + L_{2} + L_{3} + L_{4})L_{1} L_{2}" title="\Delta = 1 - (L_{1} + L_{2} + L_{3} + L_{4}) + L_{1} L_{2}" border="0" /></a>

Cofactores: 

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{1}= 1"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{1}= 1" title="\Delta_{1}= 1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{2}= 1
"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{2}= 1" title="\Delta_{2}= 1" border="0"/></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{3}= 1-L_{1}"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{3}= 1-L_{1}" title="\Delta_{3}= 1-L_{1}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{1} "><img src="http://www.alciro.org/cgi/tex.cgi?L_{1} " title="L_{1} " border="0" /></a> No toca la trayectoria

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{C(s){R(s)}=\frac{1}{\Delta }(P_{1}\Delta _{1}+P_{2}\Delta _{2}+P_{3}\Delta _{3})"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{C(s)}{R(s)}=\frac{1}{\Delta }(P_{1}\Delta_{1}+P_{2}\Delta _{2}+P_{3}\Delta _{3})" title="\frac{C(s)}{R(s)}=\frac{1}{\Delta }(P_{1}\Delta _{1}+P_{2}\Delta _{2}+P_{3}\Delta _{3})" border="0" /></a>

![image](https://github.com/user-attachments/assets/102e0071-1b9b-4424-b4f2-325b1f099bd2)

* ![image](https://github.com/user-attachments/assets/8dfd37aa-bb5b-4034-a9db-8c9f06b1d3fd)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2}{s+7}*\frac{5}{s+9}*1"><img src="http://www.alciro.org/cgi/tex.cgi?P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2}{s+7}*\frac{5}{s+9}*1" title="P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2}{s+7}*\frac{5}{s+9}*1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{2}= 1*\frac{1}{s+1}*\frac{0.5}{s+6}*\frac{1}{s^{2}+5}*\frac{1}{s}*1"><img src="http://www.alciro.org/cgi/tex.cgi?P_{2}= 1*\frac{1}{s+1}*\frac{0.5}{s+6}*\frac{1}{s^{2}+5}*\frac{1}{s}*1" title="P_{2}= 1*\frac{1}{s+1}*\frac{0.5}{s+6}*\frac{1}{s^{2}+5}*\frac{1}{s}*1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{3}= 1*\frac{1}{s+5}*25*\frac{1}{s}*1"><img src="http://www.alciro.org/cgi/tex.cgi?P_{3}= 1*\frac{1}{s+5}*25*\frac{1}{s}*1" title="P_{3}= 1*\frac{1}{s+5}*25*\frac{1}{s}*1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{1}= -10*\frac{1}{s^{2}+8}= \frac{-10}{s^{2}+8}"><img src="http://www.alciro.org/cgi/tex.cgi?L_{1}= -10*\frac{1}{s^{2}+8}= \frac{-10}{s^{2}+8}" title="L_{1}= -10*\frac{1}{s^{2}+8}= \frac{-10}{s^{2}+8}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{2}= -3"><img src="http://www.alciro.org/cgi/tex.cgi?L_{2}= -3" title="L_{2}= -3" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L_{3}=\frac{0.5}{s+6}*-12= \frac{-6}{s+6} "><img src="http://www.alciro.org/cgi/tex.cgi?L_{3}=\frac{0.5}{s+6}*-12= \frac{-6}{s+6} " title="L_{3}=\frac{0.5}{s+6}*-12= \frac{-6}{s+6} " border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta={1-(L_{1}+L_{2}+L_{3}+L_{4})(L_{1}L_{2})+(L_{1}L_{3})+(L_{1}L_{4})+(L_{2}L_{3})+(L_{2}L_{4})-(L_{1}L_{2}L_{3})-(L_{1}L_{2}L_{4})}"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta={1-(L_{1}+L_{2}+L_{3}+L_{4})(L_{1}L_{2})+(L_{1}L_{3})+(L_{1}L_{4})+(L_{2}L_{3})+(L_{2}L_{4})-(L_{1}L_{2}L_{3})-(L_{1}L_{2}L_{4})}" title="\Delta={1-(L_{1}+L_{2}+L_{3}+L_{4})(L_{1}L_{2})+(L_{1}L_{3})+(L_{1}L_{4})+(L_{2}L_{3})+(L_{2}L_{4})-(L_{1}L_{2}L_{3})-(L_{1}L_{2}L_{4})}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{1}= 1-(L_{3}+L_{4})"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{1}= 1-(L_{3}+L_{4})" title="\Delta_{1}= 1-(L_{3}+L_{4})" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{2}= 1-(L_{2}+L_{3})+(L_{2}L_{3})"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{2}= 1-(L_{2}+L_{3})+(L_{2}L_{3})" title="\Delta_{2}= 1-(L_{2}+L_{3})+(L_{2}L_{3})" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\Delta_{3}= 1-(L_{1}+L_{2})+(L_{1}L_{2})"><img src="http://www.alciro.org/cgi/tex.cgi?\Delta_{3}= 1-(L_{1}+L_{2})+(L_{1}L_{2})" title="\Delta_{3}= 1-(L_{1}+L_{2})+(L_{1}L_{2})" border="0" /></a>
# SISTEMAS DE PRIMER ORDEN
## ECUACIONES DE PRIMER ORDEN 
La estructura general de una ecuación de primer orden
es:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=a\dot{y}(t) + b y(t) = c u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?a\dot{y}(t) + b y(t) = c u(t)" title="a\dot{y}(t) + b y(t) = c u(t)" border="0" /></a>

Hallando la función de transferencia tenemos:

Aplicando transformada de LaPlace:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=a s Y(s) + b Y(s)= c U(s)"><img src="http://www.alciro.org/cgi/tex.cgi?a s Y(s) + b Y(s) = c U(s)" title="a s Y(s) + b Y(s) = c U(s)" border="0" /></a>

Despejando salida / Entrada

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{c}{a s + b}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" title="\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" border="0" /></a>

* Las funciones de transferencia de primer orden provienen de una ecuación diferencial de primer orden

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)}=\frac{c}{as+b}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)}=\frac{c}{as+b}" title="\frac{Y(s)}{U(s)}=\frac{c}{as+b}" border="0" /></a>

* Los parámetros a, b y c son los parámetros físicos del sistema que definen la dinámica del sistema

### Ejemplo
![image](https://github.com/user-attachments/assets/cc192f58-f36d-4158-ad66-32085a92add8)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=
a\dot{y}(t) + b y(t) = c u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?a\dot{y}(t) + b y(t) = c u(t)" title="a\dot{y}(t) + b y(t) = c u(t)" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{c}{a s + b}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" title="\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=R_1 A_1 \frac{dh_{1}}{d t} = R_{1}q_{i}{ - h_{1}"><img src="http://www.alciro.org/cgi/tex.cgi?R_1 A_1 \frac{dh_{1}}{d t} = R_{1}q_{i}{ - h_{1}" title="R_1 A_1 \frac{dh_{1}}{d t} = R_{1}q_{i}{ - h_{1}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{H_1(s)}{Q_i(s)} = \frac{R_1}{R_1 A_1 s + 1}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{H_1(s)}{Q_i(s)} = \frac{R_1}{R_1 A_1 s + 1}" title="\frac{H_1(s)}{Q_i(s)} = \frac{R_1}{R_1 A_1 s + 1}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=a = R_{1} A_{1},\\
b = 1\\c = R_{1}"><img src="http://www.alciro.org/cgi/tex.cgi?a = R_{1} A_{1},\\b = 1\\c = R_{1}" title="a = R_{1} A_{1},\\b = 1\\c = R_{1}" border="0" /></a>

## FORMA CANONICA DE LOS SISTEMAS DE PRIMER ORDEN 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{c}{a s + b}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" title="\frac{Y(s)}{U(s)} = \frac{c}{a s + b}" border="0" /></a>

* Esta forma no permite identificar directamente los parámetros temporales del sistema
* Para esto en control se prefiere la forma canónica

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{c}{as + b} = \frac{\frac{c}{b}}{\frac{a}{b}s + 1}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{c}{as + b} = \frac{\frac{c}{b}}{\frac{a}{b}s + 1}" title="\frac{Y(s)}{U(s)} = \frac{c}{as + b} = \frac{\frac{c}{b}}{\frac{a}{b}s + 1}" border="0" /></a>

* La forma canónica considera:
* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\tau= \frac{a}{b}"><img src="http://www.alciro.org/cgi/tex.cgi?\tau= \frac{a}{b}" title="\tau= \frac{a}{b}" border="0" /></a> Constante de tiempo <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=K= \frac{c}{b}"><img src="http://www.alciro.org/cgi/tex.cgi?K= \frac{c}{b}" title="K= \frac{c}{b}" border="0" /></a>  Ganancia Estática

* Por lo tanto:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{K}{\tau s + 1}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{K}{\tau s + 1}" title="\frac{Y(s)}{U(s)} = \frac{K}{\tau s + 1}" border="0" /></a>

### Ejemplo
* Identificar constante de tiempo y ganancia estática

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{5}{2s + 16}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{5}{2s + 16}" title="\frac{Y(s)}{U(s)} = \frac{5}{2s + 16}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{5}{2(s + 8)}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{5}{2(s + 8)}" title="\frac{5}{2(s + 8)}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{\frac{5}{16}}{\frac{2}{16}s + 1}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{\frac{5}{16}}{\frac{2}{16}s + 1}" title="\frac{\frac{5}{16}}{\frac{2}{16}s + 1}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\tau = 0.125,\quad K = 0.3125"><img src="http://www.alciro.org/cgi/tex.cgi?\tau = 0.125,\quad K = 0.3" title="\tau = 0.125,\quad K = 0.3125" border="0" /></a>
## RESPUESTA TEMPORAL DE UN SISTEMA DE PRIMER ORDEN ANTE UNA ENTRADA ESCALÓN
*  Despejando la salida para averiguar la respuesta se tiene:

![image](https://github.com/user-attachments/assets/3928e396-0f70-47c0-bf18-126ab464941c)

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s) = \frac{AK}{s(\tau s + 1)}"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s) = \frac{AK}{s(\tau s + 1)}" title="Y(s) = \frac{AK}{s(\tau s + 1)}" border="0" /></a>

* Aplicando fracciones parciales

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s) = \frac{C_1}{s} + \frac{C_2}{s + \frac{1}{\tau}} = \frac{AK}{s} - \frac{AK}{s + \frac{1}{\tau}}"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s) = \frac{C_1}{s} + \frac{C_2}{s + \frac{1}{\tau}} = \frac{AK}{s} - \frac{AK}{s + \frac{1}{\tau}}" title="Y(s) = \frac{C_1}{s} + \frac{C_2}{s + \frac{1}{\tau}} = \frac{AK}{s} - \frac{AK}{s + \frac{1}{\tau}}" border="0" /></a>

* Al aplicar transformada inversa de LaPlace
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L^{-1}{Y(s)}"><img src="http://www.alciro.org/cgi/tex.cgi?L^{-1}{Y(s)}" title="L^{-1}{Y(s)}" border="0" /></a> se tiene:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\mathcal{L}^{-1}\{Y(s)\} = y(t) = AK \left(1 - e^{-\frac{t}{\tau}}\right)"><img src="http://www.alciro.org/cgi/tex.cgi?\mathcal{L}^{-1}\{Y(s)\} = y(t) = AK \left(1 - e^{-\frac{t}{\tau}}\right)" title="\mathcal{L}^{-1}\{Y(s)\} = y(t) = AK \left(1 - e^{-\frac{t}{\tau}}\right)" border="0" /></a>

## RESPUESTA TEMPORAL SISTEMA DE PRIMER ORDEN
![image](https://github.com/user-attachments/assets/b68a7a9b-b121-426f-b596-75ff01555f10)

## RESPUESTA GRÁFICA DE UN SISTEMA DE PRIMER ORDEN
```
% Parámetros
AK = 1;
tau = 1;

% Tiempo
t = linspace(0, 5, 500);

% Respuesta al escalón unitario
y = AK * (1 - exp(-t / tau));

% También graficamos -exp(-t)
y_neg_exp = -exp(-t);

% Gráfica
figure;
plot(t, y, 'b', 'LineWidth', 2); hold on;
plot(t, y_neg_exp, '--k', 'LineWidth', 1.5);
grid on;
xlabel('tiempo (segundos)');
ylabel('Amplitud');
title('Respuesta al escalón unitario de un sistema de primer orden');
legend('y = 1 - exp(-t)', '-exp(-t)');
```

![image](https://github.com/user-attachments/assets/b28bab5c-e180-4079-9836-e126d27e196e)

## RESPUESTA NATURAL Y FORZADA DE UN SISTEMA DE PRIMER ORDEN
```
% Tiempo de simulación
t = 0:0.01:10; % desde 0 hasta 10 segundos con paso de 0.01

% Entrada escalón unitario
r = ones(size(t));

% Respuesta del sistema: y(t) = 1 - exp(-t)
y = 1 - exp(-t);

% Crear figura
figure;
plot(t, r, 'k', 'LineWidth', 1.5); % Entrada escalón (r(t))
hold on;
plot(t, y, 'k', 'LineWidth', 1.5); % Respuesta del sistema (y(t))

% Línea vertical en t = 5
xline(5, 'k--');

% Anotaciones
text(1, 0.5, 'y(t) = 1 - exp(-t)', 'FontSize', 10);
text(6.2, 1.02, 'r(t) = 1', 'FontSize', 10);

% Etiquetas y títulos
xlabel('tiempo (segundos)');
ylabel('Amplitud');
title('Régimen transitorio (natural) y de estado estable (forzado)');

% Ajuste de ejes
axis([0 10 0 1.2]);
grid on;

% Anotaciones adicionales
text(1.5, -0.1, 'Régimen transitorio', 'FontSize', 10);
text(6.5, -0.1, 'Régimen de estado estable', 'FontSize', 10);

% Opcional: eliminar borde superior para estilo similar
box off;

```
![image](https://github.com/user-attachments/assets/599cb855-5b80-4019-86f8-50f459d0ea40)

## CONSTANTE DE TIEMPO DEL SISTEMA
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=y(t)= AK(1-e^{\frac{-t}{\tau }}"><img src="http://www.alciro.org/cgi/tex.cgi?y(t)= AK(1-e^{\frac{-t}{\tau }}" title="y(t)= AK(1-e^{\frac{-t}{\tau }}" border="0" /></a>

| t  | Y(t)     |
|----|----------|
| T  | 0.632*AK |
| 2T | 0.864*AK |
| 3T | 0.950*AK |
| 4T | 0.981*AK |
| 5T | 0.993*AK |
| 6T | 0.997*AK |
```

A = 1;      % Amplitud del escalón
K = 1;      % Ganancia
tau = 1;    % Constante de tiempo

t = 0:0.01:6*tau;
y = A*K*(1 - exp(-t/tau));


figure;
plot(t, y, 'k', 'LineWidth', 1.5);
hold on;

% Marcar los puntos en t = n*tau (n=1..6)
tau_vals = tau*(1:6);
y_vals = A*K*(1 - exp(-tau_vals/tau));
plot(tau_vals, y_vals, 'ko', 'MarkerFaceColor', 'r');


y_percent = [0.632, 0.865, 0.950, 0.982, 0.993, 0.9975]*A*K;
for i = 1:6
    plot([0 tau_vals(i)], [y_vals(i) y_vals(i)], 'k--');
    plot([tau_vals(i) tau_vals(i)], [0 y_vals(i)], 'k--');
end


for i = 1:6
    text(tau_vals(i), y_vals(i) + 0.03, ...
        sprintf('%.1f%%', y_percent(i)*100), ...
        'FontSize', 9, 'HorizontalAlignment', 'left');
end

xlabel('t (segundos)');
ylabel('y(t)');
title('Respuesta de sistema de primer orden a entrada escalón');
grid on;
axis([0 6*tau 0 1.1*A*K]);

% Tabla en consola
T = tau*(1:6)';
Y = y_vals';
tabla = table(T, Y, 'VariableNames', {'t', 'Y(t)'});
disp(tabla);
```

![image](https://github.com/user-attachments/assets/36c2287c-d4b0-4f1f-9de2-4e7fcd1f0459)

## RESPUESTA A UNA ENTRADA RAMPA 
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)=\frac{AK}{s^{2}(\tau s+1)}"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)=\frac{AK}{s^{2}(\tau s+1)}" title="Y(s)=\frac{AK}{s^{2}(\tau s+1)}" border="0" /></a>

* Al desarrollar las fracciones parciales:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s)=AK(\frac{1}{s^{2}}+\frac{1\tau }{s}+\frac{\tau ^{2}}{\tau s+1})"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s)=AK(\frac{1}{s^{2}}+\frac{1\tau }{s}+\frac{\tau ^{2}}{\tau s+1})" title="Y(s)=AK(\frac{1}{s^{2}}+\frac{1\tau }{s}+\frac{\tau ^{2}}{\tau s+1})" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=L^{-1}{Y(s)}=y(t)=AK(t-\tau +\tau e^{-\frac{t}{\tau }})"><img src="http://www.alciro.org/cgi/tex.cgi?L^{-1}{Y(s)}=y(t)=AK(t-\tau +\tau e^{-\frac{t}{\tau }})" title="L^{-1}{Y(s)}=y(t)=AK(t-\tau +\tau e^{-\frac{t}{\tau }})" border="0" /></a>

## RESPUESTA A LA RAMPA UNITARIA
![image](https://github.com/user-attachments/assets/894b2a6b-d0ab-4bb4-8303-0297ef596d9e)

## ANALISIS DINAMICO DE LA RESPUESTA A LA RAMPA

| t  | Y(t)      |
|----|-----------|
| T  | 1.3679*AK |
| 2T | 2.1353*AK |
| 3T | 3.0498*AK |
| 4T | 4.0183*AK |
| 5T | 5.0067*AK |
| 6T | 6.0025*AK |

```
% Parámetros
A = 1;
K = 1;
tau = 1;

% Vector de tiempo para graficar
t = 0:0.01:6*tau;

% Entrada rampa
r = t;

% Respuesta del sistema a entrada rampa
c = A*K*(t - tau + tau*exp(-t/tau));

% Gráfica
figure;
plot(t, r, 'k--', 'LineWidth', 1.5); hold on;
plot(t, c, 'k', 'LineWidth', 1.5);
xlabel('t');
ylabel('r(t), c(t)');
title('Respuesta de un sistema de primer orden a una entrada rampa');
legend('Entrada rampa r(t) = t', 'Salida c(t)');
grid on;

% Evaluar en múltiplos de tau
T = tau * (1:6)';
Y = (T + tau * exp(-T/tau)) * A * K;

% Mostrar tabla en consola
tabla = table(T, Y, 'VariableNames', {'t', 'Y(t)'});
disp(tabla);

% Dibujar puntos y etiquetas
plot(T, Y, 'ro', 'MarkerFaceColor', 'r');
for i = 1:length(T)
    text(T(i), Y(i)+0.2, sprintf('%.2f', Y(i)), 'FontSize', 9, ...
        'HorizontalAlignment', 'center');
end

% Cálculo de pendiente en zona lineal
m = (4*tau + tau*exp(-4)) * A * K - (3*tau + tau*exp(-3)) * A * K;
m = m / (tau); % ya que (5t - 4t) = t
fprintf('Pendiente en la zona lineal: m = %.4f\n', m);
```

![image](https://github.com/user-attachments/assets/4b1bc9fa-ea50-479b-8e41-966bf9787a78)
# SISTEMAS DE SEGUNDO ORDEN
* La estructura general de una ecuación de segundo orden es

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\ddot{y}(t) + a_1 \dot{y}(t) + a_0 y(t) = b_0 u(t)"><img src="http://www.alciro.org/cgi/tex.cgi?\ddot{y}(t) + a_1 \dot{y}(t) + a_0 y(t) = b_0 u(t)" title="\ddot{y}(t) + a_1 \dot{y}(t) + a_0 y(t) = b_0 u(t)" border="0" /></a>

* Hallando la función de transferencia tenemos:
* Aplicando transformada de LaPlace:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=s^2 Y(s) + a_1 s Y(s) + a_0 Y(s) = b_0 U(s)"><img src="http://www.alciro.org/cgi/tex.cgi?s^2 Y(s) + a_1 s Y(s) + a_0 Y(s) = b_0 U(s)" title="s^2 Y(s) + a_1 s Y(s) + a_0 Y(s) = b_0 U(s)" border="0" /></a>

* Despejando salida / Entrada
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}" title="\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}" border="0" /></a>

## FORMA CANONICA DE LOS SISTEMAS DE SEGUNDO ORDEN

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}" title="\frac{Y(s)}{U(s)} = \frac{b_0}{s^2 + a_1 s + a_0}" border="0" /></a>

* Esta forma no permite identificar directamente los parámetros temporales del sistema
* Para esto en control se prefiere la forma canónica
*  La forma canónica considera lo siguiente:

![image](https://github.com/user-attachments/assets/544e8f57-4860-4e86-9423-0a450de07504)

* Por lo tanto:

![image](https://github.com/user-attachments/assets/47cba194-b006-4b34-9d3d-41ec9a9d1ed9)
### EJEMPLO
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s)=\frac{36}{s^{2}+4.2s+36}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s)=\frac{36}{s^{2}+4.2s+36}" title="G(s)=\frac{36}{s^{2}+4.2s+36}" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\omega n^{2}= 36 \\
\omega  n=\sqrt{36} \\ \omega n= 6"><img src="http://www.alciro.org/cgi/tex.cgi?\omega n^{2}= 36 \\\omega  n=\sqrt{36} \\ \omega n= 6" title="\omega n^{2}= 36 \\\omega  n=\sqrt{36} \\ \omega n= 6" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=36K=36 \\ 
K=1"><img src="http://www.alciro.org/cgi/tex.cgi?36K=36 \\ K=1" title="36K=36 \\ K=1" border="0" /></a>

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=32\zeta 6 = 4.2\\ 
\zeta = 4.2 = 0.35"><img src="http://www.alciro.org/cgi/tex.cgi?32\zeta 6 = 4.2\\ 
\zeta = 4.2 = 0.35" title="32\zeta 6 = 4.2\\ \zeta = 4.2 = 0.35" border="0" /></a>
## RESPUESTA DE UN SISTEMA DE SEGUNDO ORDEN A UN ESCALON

*Factorizando:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G(s) = \frac{K \cdot \omega_n^2}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^2 - 1})(s + \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1})}"><img src="http://www.alciro.org/cgi/tex.cgi?G(s) = \frac{K \cdot \omega_n^2}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^2 - 1})(s + \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1})}" title="G(s) = \frac{K \cdot \omega_n^2}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^2 - 1})(s+ \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1})}" border="0" /></a>

* Aplicando escalón:

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Y(s) = \frac{K \cdot \omega_n^2 \cdot A}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^2 - 1})(s + \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1}) \cdot s}"><img src="http://www.alciro.org/cgi/tex.cgi?Y(s) = \frac{K \cdot \omega_n^2 \cdot A}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^2 - 1})(s + \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1}) \cdot s}" title="Y(s) = \frac{K \cdot \omega_n^2 \cdot A}{(s + \zeta \omega_n + \omega_n \sqrt{\zeta^- 1})(s + \zeta \omega_n - \omega_n \sqrt{\zeta^2 - 1}) \cdot s}" border="0" /></a>

* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Si \zeta = 1"><img src="http://www.alciro.org/cgi/tex.cgi?Si \zeta = 1" title="Si \zeta = 1" border="0" /></a>

![image](https://github.com/user-attachments/assets/99bca48d-26c6-4451-9dec-ab55e4dca381)

![image](https://github.com/user-attachments/assets/8e1aa657-7a86-4cda-afce-db9237ad3eb6)

* <a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=Si \zeta >  1"><img src="http://www.alciro.org/cgi/tex.cgi?Si \zeta >  1" title="Si \zeta >  1" border="0" /></a>

![image](https://github.com/user-attachments/assets/0d6dd1ef-9176-43de-8258-942157f32499)

![image](https://github.com/user-attachments/assets/21fedee8-3bc4-4f16-ac9c-8d49c9d8bcfa)

## Conclusiones
* Modelado de Sistemas Dinámicos:
  La ecuación diferencial de segundo orden con coeficientes constantes permite modelar muchos sistemas físicos (mecánicos, eléctricos, térmicos, etc.).
Su representación en el dominio de Laplace facilita el análisis algebraico y la obtención de la función de transferencia, herramienta fundamental para estudiar la respuesta del sistema.
* Respuesta al Escalón y a la Rampa:
Para sistemas de primer orden, la respuesta al escalón se caracteriza por un crecimiento exponencial hacia un valor final.
La respuesta a una rampa muestra una zona transitoria seguida de una zona lineal, cuya pendiente se iguala al producto, facilitando la estimación de la ganancia del sistema.
## Referencias
* Ogata, K. (2010). Ingeniería de Control Moderna (5ª ed.). Pearson Educación.
* Dorf, R. C., & Bishop, R. H. (2011). Modern Control Systems (12th ed.). Prentice Hall.
* MathWorks. (2023). MATLAB & Simulink Documentation. Recuperado de: https://www.mathworks.com/help/
* Franklin, G. F., Powell, J. D., & Emami-Naeini, A. (2015). Feedback Control of Dynamic Systems (7th ed.). Pearson.
