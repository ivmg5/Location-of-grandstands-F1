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

<img width="380" alt="Screenshot 2023-10-26 at 12 45 37 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/a50d5769-3b8f-45e8-ac4d-baaa3a7bcc27">
<img width="403" alt="Screenshot 2023-10-26 at 12 46 36 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/ac7e033b-ab1f-4650-8fb4-b678dbe84a92">
<img width="556" alt="Screenshot 2023-10-26 at 12 47 33 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/e73aac86-0594-45e4-992d-ac342b6647a4">
<img width="377" alt="Screenshot 2023-10-26 at 12 48 00 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/ce6e2710-717b-4811-93d1-afd25b4c8653">
<img width="974" alt="Screenshot 2023-10-26 at 12 48 46 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/132b251b-256b-4eb8-9275-29a37758f18b">
<img width="824" alt="Screenshot 2023-10-26 at 12 49 30 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/a12627de-68cb-4ae0-b77a-722d0c8b37b4">
<img width="625" alt="Screenshot 2023-10-26 at 12 49 49 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/00f1446c-cb3e-4c8e-8e4e-b025000b0088">
<img width="398" alt="Screenshot 2023-10-26 at 12 50 15 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/892094cb-a91d-41ac-b37c-4742bc62d4b3">
<img width="465" alt="Screenshot 2023-10-26 at 12 50 58 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/cdee6f3c-4c7f-4d53-aa5f-f423ede9019d">
<img width="517" alt="Screenshot 2023-10-26 at 12 51 15 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/120cda11-c319-4833-841e-0c7b39db29a2">
<img width="538" alt="Screenshot 2023-10-26 at 12 51 39 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/86b36d65-8208-4b04-aa6a-1e4365ab1fd2">
<img width="403" alt="Screenshot 2023-10-26 at 12 52 07 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/92a4937f-bd24-4c0c-80d3-ce617a192e93">
<img width="594" alt="Screenshot 2023-10-26 at 12 52 55 a m" src="https://github.com/ivmg5/Location-of-grandstands-F1/assets/102205596/76db03ad-25a8-4272-ad36-f838dd79a59c">

