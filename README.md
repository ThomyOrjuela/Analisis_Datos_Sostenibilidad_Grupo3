# Analisis_Datos_Sostenibilidad_Grupo3
En este reposiotorío se comparte el proceso de exploración y recolección de las bases de datos de sostenibilidad ambiental, en los portales abiertos de SIAC, IDEAM y OAB.


# Análisis preliminar de bases de datos - Observatorio Ambiental de Bogotá

## Introducción
El Observatorio Ambiental de Bogotá (OAB) es una plataforma que recopila y organiza
diversos indicadores ambientales, facilitando el análisis del estado y la calidad del entorno
en la ciudad, así como la evaluación de los resultados de la gestión ambiental desarrollada
por el Distrito. El OAB es una herramienta digital de la Secretaría Distrital de Ambiente que
actúa como el portal oficial para la divulgación y reporte de información estadística
ambiental sobre la ciudad, manejando indicadores sobre el aire, agua, biodiversidad, suelo,
ruido ambiental, cambio climático y demás temas relacionados con la sostenibilidad. Su
objetivo principal es promover la gestión y la participación ambiental en Bogotá a través
de la divulgación de información precisa y actualizada, sirviendo como instrumento clave
para la toma de decisiones, la investigación académica, planificación urbana y participación
ciudadana al alcance de todos.

### Alcances y utilidades
- Proporciona información básica e indicadores sobre el estado ambiental de la ciudad
y sobre la respuesta institucional a desafíos (metas) ambientales.  
- Genera las bases para el seguimiento y evaluación de políticas públicas
ambientales.  
- Propicia un escenario mediante al cual la comunidad puede estar más y mejor
informada, y cualificar sus procesos de participación en la gestión ambiental.  
- Permite una interacción con la ciudadanía a fin de que ésta participe proactivamente
en la generación de información ambiental y en proyectos ambientales de Bogotá
D.C.  

### Tipo de información
**Visores dinámicos:** El Observatorio cuenta con una serie de visores geográficos que
funcionan como mapas interactivos, los cuales permiten consultar información
georreferenciada sobre aspectos ambientales de Bogotá. Por otro lado, contiene una serie
de redes de monitoreo y microsensores que aportan datos sobre el comportamiento de la
fauna y calidad de aire. Todo esto facilita la comprensión sobre las características naturales
de la ciudad, además ofrece recorridos en formato 360 que permiten explorar humedales,
parques y diferentes áreas de conservación natural.  

**Indicadores:** El repositorio abarca diferentes indicadores ambientales que hacen
seguimiento periódicamente del estado y la gestión del ambiente, lo que permite evaluar el
estado sostenible de la ciudad. Estos indicadores se encuentran clasificados en diversas
categorías: agua, aire, biodiversidad, suelo, ruido ambiental, residuos, cambio climático y
salud ambiental; dichos indicadores están presentados en forma de gráficas y mapas
comparativos, cada uno contiene su respectiva ficha técnica, diccionario de variables,
unidades de medida, contextualización, periodicidad y fuente de información. Con esta
estructura se facilita la comprensión de la información, convirtiéndose así en una
herramienta clave para la toma de decisiones sostenibles.  

**Bases de datos:** Es posible consultar y descargar bases de datos asociadas a los
indicadores, analizando así de donde nace la información. Estas bases contienen datos en
formatos abiertos (CSV, XLSX o WORLD jgw), lo que permite realizar análisis propios al
alcance de cualquier ciudadano. Entre los conjuntos de información se pueden encontrar
bases históricas sobre: calidad de aire, ruido ambiental, arbolado urbano, manejo de
desechos, calidad de cuerpos de agua, biodiversidad, precipitaciones, entre otros. Muchos
de los datos se encuentran con su propio análisis, ya que manejan gráficas, mapas
explicativos, investigaciones, referencias o reportes, explicando el contexto de la
información.  

---

## Base de datos 1: Cantidad de residuos peligrosos por tipo generados en el sector público distrital (PIGA - RESPEL)

**Fuente:** Observatorio Ambiental de Bogotá – Indicador definido en el marco del *Plan Institucional de Gestión Ambiental (PIGA)*.  
**Frecuencia:** Anual (rezago de 180 días).  
**Unidad de medida:** Toneladas.  

### Contexto
Las entidades del Distrito Capital reportan semestralmente el tipo de residuo peligroso que generan, la actividad que lo origina, la cantidad (en toneladas) y la disposición final realizada, de acuerdo con la normatividad de la autoridad ambiental.  
El objetivo principal de este indicador es cuantificar y clasificar los residuos peligrosos generados en el sector público, para mejorar la gestión ambiental y reducir impactos negativos asociados a su manejo inadecuado.  

### Variables incluidas
- **Periodo**  
- **Tipos de residuos peligrosos:** metales, otrosqui, otrosRAEES, lodos, pilas, aceites, luminarias, pinturas, plaguicidas, cortopunzantes, animales, productos de aseo, solventes, balastros, tóneres, baterías, biosanitarios, anatómicos, electro, citotóxicos, equipos, fármacos.  
- **Valor (Toneladas)**  

### Posibles usos de la base de datos
- **Huella ambiental del sector público en Bogotá:** Relacionar la generación de residuos peligrosos con el consumo energético y de agua de las entidades distritales.  
- **Relación con la salud pública:** Cruzar este indicador con datos de la Secretaría de Salud sobre enfermedades respiratorias, intoxicaciones u hospitalizaciones, considerando también la ubicación de rellenos sanitarios y zonas pobladas aledañas.  

### Observaciones de calidad de datos
- El rezago en la publicación (180 días) puede limitar análisis en tiempo real.  
- La calidad de la información depende del reporte de cada entidad, por lo que puede existir subregistro o variabilidad en la clasificación de los residuos.  

---

## Base de datos 2: Emisiones totales de Gases de Efecto Invernadero (INGEI)

**Fuente:** Observatorio Ambiental de Bogotá – Inventario Distrital de GEI (INGEI).  
**Frecuencia:** Anual (rezago de 760 días).  
**Unidad de medida:** Toneladas de CO₂ equivalente (Ton CO₂ eq).  

### Contexto
Este indicador evalúa el impacto de las actividades de los distintos sectores sobre las emisiones de gases de efecto invernadero (GEI) en Bogotá.  
Su análisis es clave para:  
- Medir el avance de la ciudad frente al reto del cambio climático.  
- Hacer seguimiento a las medidas de mitigación implementadas.  
- Evaluar la efectividad de políticas públicas ambientales y de sostenibilidad.  

El indicador también conecta con los compromisos nacionales e internacionales en el marco del **Acuerdo de París**, permitiendo analizar qué tan alineada está Bogotá con las metas de reducción de emisiones de Colombia y las metas globales.  

### Objetivo del indicador
Evaluar el impacto de las actividades de los distintos sectores en el aporte de GEI a nivel distrital y realizar un seguimiento sistemático a las medidas de mitigación del cambio climático. Busca orientar la toma de decisiones y fortalecer la gestión ambiental hacia un desarrollo urbano sostenible.  

### Variables incluidas
- **Periodo**  
- **GEI-T**: Emisiones por transporte  
- **GEI-E**: Emisiones por energía de edificaciones  
- **GEI-RS**: Emisiones por residuos sólidos  
- **GEI-AR**: Emisiones por aguas residuales  
- **Valor (Ton CO₂ eq)**  

### Posibles usos de la base de datos
- **Evolución de emisiones de GEI en Bogotá:** Analizar tendencias y compararlas con las metas climáticas nacionales e internacionales (hacia 2030).  
- **Relación con indicadores sectoriales:** Identificar qué sectores (transporte, energía, residuos sólidos, aguas residuales) aportan más a las emisiones y cómo han variado en el tiempo.  

### Observaciones de calidad de datos
- El rezago en la publicación (760 días) dificulta el análisis actualizado.  
- La estimación de emisiones depende de metodologías y supuestos internacionales, por lo que puede haber cambios en las series cuando se actualizan lineamientos.  

---

## Próximos pasos
- Incluir análisis exploratorio de las dos bases de datos.  
- Generar visualizaciones descriptivas en Python/R o Power BI.  
- Identificar relaciones con indicadores externos (energía, salud, transporte).  
- Evaluar calidad de datos y proponer mejoras para su aprovechamiento en investigación.  
