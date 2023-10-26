**Simulación Computacional de Energía Perdida en un Circuito de Fórmula Uno**

---

**Autores**:
- Diego Iván Morales Gallardo (A01643382)
- Karen Corona Espinoza (A01642461)
- Fernanda Díaz Gutiérrez (A01639572)

---

**Introducción**:
El deporte de la Fórmula Uno es una combinación de velocidad, precisión y estrategia. Además de las carreras emocionantes, la seguridad es una prioridad máxima tanto para los pilotos como para los espectadores. Este proyecto se sumerge en la simulación computacional para garantizar puntos de observación seguros y emocionantes para los espectadores.

**Planteamiento del Problema**:
La determinación de la ubicación de las gradas es fundamental para ofrecer a los espectadores una experiencia única, segura y con una vista inigualable de la carrera. Se llevan a cabo dos simulaciones: un auto que sigue la pista y otro que potencialmente se desvía.

**Características del Circuito Bahrain**:
- **Velocidades**:
  - Mínima: 95 km/h
  - Máxima: 329.6 km/h
  - Promedio: 143 km/h
- **Peralte**:
  - Del carro: Delantero a 2.5 grados y trasero a 1.0 grados.
  - De la pista: 5 grados.
- **Altura**:
  - Punto de mayor elevación: horquilla de la curva 4.
  - Resto del circuito: ubicado bajo el nivel del mar.
- **Coeficiente de fricción (μ)**:
  - Asfalto seco: 1.5
  - Asfalto húmedo: 1.05
- **Tipo de pista**: Asfalto.
- **Dimensiones del circuito**:
  - Distancia total: 308.238 km.
  - Longitud de la pista: 5.412 km.

**Metodología**:
1. **Investigación del Circuito**: Elegimos el circuito de Bahrain y estudiamos sus características distintivas.
2. **Fricción y Neumáticos**: Determinación del coeficiente de fricción según los tipos de neumáticos.
3. **Diseño Preliminar**: Se realiza un esquema del diseño de la pista, considerando las zonas rectas y curvas.
4. **Análisis de Datos**: Los puntos (x, y) son graficados en Excel y se define una línea de tendencia.
5. **Conversión a Metros**: Las coordenadas se convierten a la unidad estándar, metros.
6. **Cálculos Geométricos**: Se determinan aspectos como la hipotenusa de triángulos adyacentes a la curva, el radio de las curvas, velocidades, y otros parámetros relevantes.
7. **Ubicación de Gradas**: Se proponen las zonas más seguras y óptimas para la colocación de las gradas.

**Modelación de la Pista**:
Se realiza un boceto de la pista, y se establecen puntos clave basándose en la cuadrícula original del circuito. Estos puntos son luego modelados en Excel, resultando en la ecuación de la curva: y = 0.0000138 x^3 - 0.0188 x^2 + 7.8 x - 574.

**Validación**:
Nuestro diseño de pista se valida comprobando que la curva diseñada se ajuste a los puntos iniciales y finales deseados.

**Aspectos Relevantes para el Diseño**:
Se consideran diversas variables, desde el consumo de gasolina y la capacidad de los neumáticos, hasta zonas de seguridad y características del vehículo. A partir de estos, se determinan puntos críticos en la pista y zonas de derrape.

**Zonas de Derrape y Gradas**:
Se identifican áreas potenciales de derrape y, basándonos en estos datos, se propone la ubicación de las gradas. MATLAB ayuda en la modelación del comportamiento del coche en estas zonas.

**Conclusiones**:
El estudio profundo de las propiedades de una curva tiene aplicaciones vastas, desde la Fórmula Uno hasta la economía. La seguridad y la experiencia del espectador son primordiales en este deporte, y este proyecto se esfuerza por garantizar ambos aspectos. Las gradas propuestas se sitúan en zonas que minimizan el riesgo y maximizan la visibilidad, ofreciendo una experiencia inigualable para los aficionados.
