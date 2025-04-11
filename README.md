27 / 04 / 2025
# Perfil de Movimiento - Parte 2 

Con el objetivo de recordar lo visto en la clase pasada, se propone el siguiente ejemplo.
## 💡Ejemplo 1:

- Dado el perfil de velocidad simétrico de la figura 1, calcule la máxima velocidad y la aceleración máxima.

<img src="Ej_1.png" alt="Ejemplo" width="200">
Figura 1. Perfil de velocidad simétrico 

Solución:

$$S_{B} = {\color{Red}\frac{1}{2}v_{max}\frac{t}{2}} + {\color{Green}\frac{1}{2}v_{max}\frac{t}{2}}$$

Se consideran ambas partes de la curva: la ecuación en rojo corresponde al segmento A, mientras que la ecuación en verde representa el segmento B.

$$S_{B} = \frac{1}{2}v_{max}t$$

En la gráfica de velocidad el tiempo de movimiento es igual a 0.

$$v_{max} = \frac{2_{S_{B}}}{t}$$

$$a = \frac{2v_{max}}{t}$$


# Perfil de velocidad curva en S
La curva en S se utiliza en perfiles de movimiento para suavizar la transición entre las distintas fafes de desplazamiento, reduciendo así las vibraciones mecánicas y los esfuerzos sobre los componentes del sistema. A diferencia de los perfiles lineales, en los que los camibos de aceleración ocurren de forma repentina, la curva en S introduce una transición gradual que mejora significativamente el comportamiento dinámico del sistema.

- Perfil de Posición:
  - En ambos casos, al integrar el perfil de velocidad se obtiene una función de tercer orden para la posición. Sin embargo, en el perfil con curva en S, el crecimiento de a posición es más progresivo y continuo, sin cambios bruscos de pendiente. Esto se traduce en un desplazamiento más fluido y preciso.
  
    <img src="Pos_S.png" alt="Pos" width="500">
Figura 2. Perfil de Posición

- Perfil de Aceleración:
  - Perfil Lineal: La aceleración se presenta en forma de escalones o saltos repentinos. En cada etapa del movimientp (aceleración constante, velocidad constante, desaceleración), la aceleración cambia bruscamente de valor, lo que puede generar impactos al sistema.

  - Perfil Curva en S: La aceleración es continua y suave. Está compuesta por tres fases: Pendiente positiva (incrementa la aceleración), constante, y una pendiente negativa (disminuye la aceleración). Este comportamiento se representa mediante funciones cuadráticas (segund orden), lo que hace que al derivar para obtener el Jeck sea lineal.
  
    <img src="Pos_A.png" alt="Acel" width="500">
Figura 3. Perfil de Aceleración


- Perfil de Jeck: 
  - Perfil Lineal: Se aprecian saltos abruptos, ya que la aceleración cambia de forma instantánea.
  - Perfil Curva en S: Se observa una transición continua con cambios suaves.
    
     <img src="Pos_J.png" alt="Jec" width="500">
Figura 4. Perfil de Jeck


Se encuentra 2 clases de curvas en S:
1. Perfiles S pura: 2 modelos de segundo orden conectados entre ellos; este perfil es mucho más suave.
2. Perfiles en S: Si 2 modelos de segundo orden y un modelo de primer orden en la mitad.

$ Modelo matemático







# Conclusiones
- Implementar un perfil de movimiento con curva en S permite una transición más suave entre etapas, reduciendo las vibraciones, mejorando la precisión del posicionamiento y alargando la vida útil de los componentes mecánicos. Aunque su implementación puede requerir mayor complejidad.








