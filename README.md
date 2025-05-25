
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

<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2}{s+7}*\frac{5}{s+9}*1"<imgsrc="http://www.alciro.org/cgi/tex.cgi?P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2{s+7}*\frac{5}{s+9}*1" title="P_{1}= 1*\frac{1}{s+1}*\frac{1}{s^{2}+8}*\frac{2}{s+7}*\frac{5{s+9}*1" border="0" /></a>

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

```clc;
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

## Amplificador no inverso

Se utilizan leyes de Kirchof y el modelo simplificado del amplificador operacional 

![image](https://github.com/user-attachments/assets/7911912f-005b-4f22-884b-c04ad39c9e9b)

* La tension em ambas entradas del amplificado son iguales
* La corriente a las entradas del amplificador es igual a 0
* La impedancia de entrada es muy grande
* La impedancia de salida es pequeña

## Conclusiones
* Utilidad de la Transformada de Laplace

La Transformada de Laplace es una herramienta clave para resolver ecuaciones diferenciales, ya que permite analizar sistemas en el dominio de la frecuencia, facilitando su estudio y solución.

* Análisis y comportamiento del sistema

Trabajar en el dominio de Laplace permite entender mejor la respuesta de un sistema ante diferentes entradas, identificando características como estabilidad y comportamiento en estado estacionario

*Apoyo de herramientas computacionales

El uso de MATLAB y Simulink complementa el análisis teórico, permitiendo simular sistemas dinámicos de forma visual y confirmar resultados analíticos.
## Referencias
* Ogata, K. (2010). Ingeniería de Control Moderna (5ª ed.). Pearson Educación.
* Dorf, R. C., & Bishop, R. H. (2011). Modern Control Systems (12th ed.). Prentice Hall.
* MathWorks. (2023). MATLAB & Simulink Documentation. Recuperado de: https://www.mathworks.com/help/
* Franklin, G. F., Powell, J. D., & Emami-Naeini, A. (2015). Feedback Control of Dynamic Systems (7th ed.). Pearson.
