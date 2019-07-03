# Ingeniería de Software III 2019
## Práctica 1 – Calidad de Software (Parte A)
### Parte I: Conceptos generales

#### 1. Describir con sus palabras qué entiende por Calidad.

> Calidad o de calidad puede definir a un producto o servicio que está "bien hecho". Los servicios/productos de calidad suelen ser mas costosos. Yo

>Propiedades que pueden ser juzgadas, término subjetivo, depende del juicio de cada persona que intervenga en la evaluación.

#### 2. Cada uno de los denominados Gurús (o Padres) de la Calidad han creado o instaurado algún programa, término o proceso que los ha colocado en ese lugar. Investigue y explique con sus palabras el aporte realizado por cada uno de los gurús mencionados en la teoría.

##### Walter Shewhart

Ciclo de Shewhart (PDCA):​ Shewhart plantea una estrategia de mejora continua de la calidad basada en cuatro pasos (Plan, Do, Check, Act)

**Planificar** (Plan):​ Establecer las necesidades del proceso necesarias para obtener el resultado esperado.

**Hacer**​ (Do): Realizar los cambios para implementar las mejoras necesarias en el proceso.

**Controlar**​ (Check):Pasado un periodo de tiempo se recopilan los datos de control y se comparan con los requisitos especificados inicialmente para saber si se cumplieron y evaluar si se produjo una mejora.

**Actuar** (Act):​ Utilizar la información recopilada en la etapa anterior y tomar las medidas necesarias. Luego el ciclo vuelve a comenzar teniendo en cuenta los resultados obtenidos.


##### Eduard Deming

Basándose en el trabajo realizado por Walter Shewhart, Deming plantea los 14 puntos y 7 enfermedades de la gerencia, que son cuestiones a tener en cuenta para llevar a cabo la gerencia de una empresa de la mejor forma posible y que cosas evitar para conseguir el propósito de la organización.

##### Joseph Juran

Joseph Juran fue un experto en el campo de la gestión de la calidad, una de las cosas más importantes que definió fue la llamada trilogía de Juran, que involucra la planificación, el control, y la mejora continua.

##### Phillips Crosby

**Concepto de Cero Defectos:** Se enfoca en elevar las expectativas de la administración y a motivar y concientizar a los trabajadores por la calidad. Para eso se necesita: una decisión fuerte de implantación, cambio de cultura o del entorno de trabajo y actitud de apoyo a la dirección.

**Vacuna de calidad:** Consiste en la implementación de ciertos operaciones, Comunicaciones, integridad, sistemas y políticas que deberían combinarse para producir una mejora en la calidad de una organización.

##### Kaoru Ishikawa

**Círculos de control de calidad:** Es una técnica utilizada en la gestión de organizaciones en la que un grupo de trabajo voluntario se reúne para buscar soluciones a problemas detectados en sus áreas de trabajo. Los resultados y conclusiones de esta reunión son entregados a los directivos, quienes evaluarán las propuestas y proveerán los recursos para llevarlas a cabo.

**Diagrama de causa-efecto:** Es la representación de varios elementos (causas) de un sistema que pueden contribuir a un problema (efecto).
- Identificar un problema específico y concreto y todas las causas posibles relevantes
- Considerar cada caso en particular
- Seleccionar las causas más probables o con mayor incidencia sobre el defecto estudiado
- Evaluar las soluciones más aconsejables para la resolución del defecto


##### Shigeo Shingo

**Poka-Yoke:** El principal objetivo era eliminar la posibilidad de realizar un error en el proceso de manufactura. Consiste de 3 reglas básicas:
- No aceptes defectos
- No realizar defectos
- No pasar defectos a otros

**Cero control de la calidad:** Es un enfoque de control de calidad que destaca la aplicación de las Poka Yoke. Se basa en la premisa de que los defectos se dan porque ocurren errores en el proceso. La idea principal de este concepto es la interrupción del proceso cuando ocurre un defecto, la definición de la causa y su corrección. De esta forma no es necesario realizar muestreos y aplicar controles estadísticos de calidad para conseguir la ausencia de defectos.


#### 3. Explique con sus palabras que es la Calidad del Software y cómo se divide.

Se puede dar calidad en el software que se desarrolla, mantiene o da soporte. La calidad en el software se puede dividir en:
- Calidad del proceso de desarrollo
- Calidad de producto obtenido

Esta misma división puede ser mas general no restringiendose solamente a la calidad de software.
Las metas que se definan como calidad del producto impactarán en la calidad del proceso de desarrollo del mismo ya que están directamente relacionada y se podría decir que la calidad del producto es consecuencia de la calidad del proceso.

#### 4. ¿Cómo se diferencian los términos Norma y Estándar? Explique.

- Norma: Regla que **se debe** adoptar o ajustar conductas, tareas, procesos a la misma.
- Estándar: Sirve como tipo, sugerencia, recomendación, modelo, patrón o referencia.

El término norma es mas fuerte ya que define reglas a seguir. Un estándar es una sugerencia modelo a seguir.

## Parte II: Calidad de Producto
#### 5. Describa el concepto de Calidad de Producto de software.

Calidad del producto de software
- Modelo de calidad
- Métricas externas
- Métricas internas
- Métricas de calidad de uso

_La calidad de producto de software está relacionado con la calidad de producto._

#### 6. Explique cuáles son los pasos a seguir para realizar una evaluación siguiendo el proceso de evaluación definido en la norma ISO/IEC 14598.

Se describe el proceso de evaluación:
- Establecer los requisitos de evaluación.
    - Establecer propósito de la evaluación (7.1). `Apartado de la 14598`.
    - Identificar los tipos de producto(s) (7.2).
    - Especificar el modelo de la calidad (7.3). `9126-1 Características de Calidad`
- Especificar la evaluación
    - Seleccionar métricas (8.1). `9126-2 Métricas Externas. 9126-3 Métricas internas. 14598-6 Módulos de evaluación`
    - Establecer niveles para las métricas (8.2)
    - Establecer criterios de valoración (8.3)
- Diseñar evaluación
    - Producir plan de evaluación (9.1)
- Ejecutar la evaluación
    - Tomar medidas (10.1)
    - Comparar con criterios (10.2)
    - Valorar resultados (10.3)

La norma ISO/IEC 14598 establece un marco de trabajo para evaluar calidad de producto de software en 6 etapas. También proporciona métricas y requisitos para los procesos de evaluación.
- ISO/IEC 14598-1: `Descripción General`.Provee un panorama general de las otras 5 etapas y relaciona la evaluación del producto de software y modelo de calidad definido en la norma ISO 9126.
- ISO/IEC 14598-2: `Planificación y gestión`. Requerimientos y guías para las funciones de soporte como planeamiento y gestión. (Norma retirada).
- ISO/IEC 14598-3: `Proceso para desarrolladores`. Esta etapa provee requerimientos y recomendaciones para la evaluación del producto de software cuando la evaluación es en paralela con el desarrollo. (La norma fue retirada).
- ISO/IEC 14598-4: `Proceso para compradores`. Provee los requerimientos y recomendaciones para un producto de software comercial personalizado o modificación de un producto existente para garantizar a los compradores que el software cumple con los requerimientos. (La norma fue retirada).
- ISO/IEC 14598-5: `Proceso para evaluadores`. Recomendaciones para el proceso de evaluación del producto de software.
- ISO/IEC 14598-6: `Documentación de los módulos de evaluación`. Guías para documentación de la evaluación. Es la especificación del modelo de calidad de las métricas correspondientes internas y externas. Incluye métodos y técnicas de evaluación más las mediciones actuales resultantes de su aplicación.

#### 7. Describa el Modelo de Calidad de la ISO/IEC 9126.

La ISO/IEC 9126 _fue_ un estándar internacional para la evaluación de la calidad del software. Fue reemplazado en 2005 por la ISO 25000 la cual desarrolla los mismos conceptos.

Se describe el modelo de calidad de producto de software en dos partes.

a) Calidad interna y externa

b) Calidad de uso. 

Esta a su vez está especificada en 6 características para la calidad interna y externa y 4 para calidad de uso.

#### 8. Enumere las características que presenta la ISO/IEC 9126-1.

La ISO 9126-1 clasifica la calidad de software en un conjunto estructurado de características y subcaracterísticas. Cada subcaracterística a su vez está dividida en atributos. Los atributos no están definidos en el estándar ya que varían entre diferentes productos de software.

Las **características** y _subcaracterísticas_ son las siguientes:

##### Calidad interna y externa
- **Funcionalidad**
    - _Adecuacuación_
    - _Exactitud_
    - _Interoperabilidad_
    - _Seguridad_
    - _Cumplimiento funcional_
- **Fiabilidad**
    - _Madurez_
    - _Recuperabilidad_
    - _Tolerancia a fallos_
    - _Cumplimiento de fiabilidad_
- **Usabilidad**
    - _Aprendizaje_
    - _Comprensión_
    - _Operabilidad_
    - _Atractividad_
- **Eficiencia**
    - _Comportamiento en el tiempo_
    - _Comportamiento de recursos_
- **Mantenibilidad**
    - _Estabilidad_
    - _Facilidad de análisis_
    - _Facilidad de cambio_
    - _Facilidad de pruebas_
- **Portabilidad**
    - _Capacidad de instalación_
    - _Capacidad de reemplazamiento_


##### Calidad en uso:
- _Eficacia_
- _Productividad_
- _Seguridad_
- _Satisfacción_

#### 9. Las métricas de la ISO/IEC 9126-2 están definidas en forma de tabla. Explique cuáles son los componentes de esta tabla y qué criterios brinda la norma para la creación de nuevas métricas.

Los componentes de la tabla son:
- Metricname. (Nombre de la métrica). Interna o externa.
- Purpose of the metric. (Propósito de la métrica). Se expresa la aplicación de la métrica.
- Method of application. Proveé un esquema para la aplicación de la métrica.
- Measurement, formula and data element computations: Formulas y elementos para la métrica.
- Interpretation of measured value: Provee un rango para los valores de la métrica.
- Measure type: Tipo de medida. Por ejemplo (Número de cambios, tiempo).
- Input to measurement: De donde se obtienen los datos de la métrica.
- ISO/IEC 12207 SLCP Reference: Identifica el ciclo de vida del software cuando es aplicable.
- Target audience: Para quién va dirigida la métrica.

#### 10. Mencione cuáles son los niveles de puntuación de las métricas.

Depende de cada métrica.

#### 11. Explique de qué forma se deben combinar los niveles de las métricas para establecer los niveles de las características y de evaluación.

Se pueden combinar mediante fórmulas o tablas.

#### 12. Explique cómo se conforma la familia ISO/IEC 25000 (SQuaRE).

Se conforma con una serie de estándares basados en la ISO/IEC 9126 y la ISO/IEC 14598 cuyo principal objetivo es guiar el desarrollo de un producto de software a través de una especificación de requerimientos de calidad y las características de evaluación de la calidad.
- 2500n: División gestión de la calidad
- 2501n: División modelos de calidad
- 2502n: División de medición de calidad
- 2503n: División Requerimientos de calidad
- 2504n: División evaluación de la calidad  

#### 13. ¿Qué norma de la familia ISO/IEC 25000 reemplaza a la ISO/IEC 9126-1? Explique las diferencias.

La reemplaza la ISO/IEC 25010.
En la ISO/IEC 25010 aparecen nuevas características, `8 en total`.
__Calidad del producto de software:__
- Portabilidad -> 9126-1
- Seguridad
- Facilidad de mantenimiento
- Compatibilidad
- Funcionalidad -> 9126-1
- Confiabilidad
- Facilidad de uso
- Eficiencia -> En la 9126-1

#### 14. ¿Qué norma de la familia ISO/IEC 25000 reemplaza a la ISO/IEC 14598? Explique las diferencias.

La ISO/EIC 14598 fue reemplazada por la ISO/IEC 25040. IRAM la adopta como norma nacional en 2006 como **IRAM-ISO/IEC 14598:2001** _Evaluación del producto de software_ y aún está vigente.

La norma ISO/IEC 14598 está dividida en seis partes:
- IRAM - ISO/IEC 14598-1 Descripción General.
- IRAM - ISO/IEC 14598-2 Planificación y Gestión.
- IRAM - ISO/IEC 14598-3 Proceso para desarrolladores.
- IRAM - ISO/IEC 14598-4 Proceso para compradores.
- IRAM - ISO/IEC 14598-5 Proceso para evaluadores.
- IRAM - ISO/IEC 14598-6 Documentación de los módulos de evaluación.

_¿y las diferencias?_

### Parte III: Calidad de datos

#### 15. Describa el concepto de Calidad de Datos ISO/IEC 25012.

La norma entiende por calidad de datos a la capacidad de las características de los datos de satisfacer necesidades explícitas e implícitas bajo determinadas condiciones de uso.

#### 16. Defina la clasificación propuesta por el modelo.

La clasificación propuesta es considerando dos puntos de vista:
- __Inherente:__
    _Capacidad de las características de los datos de tener el potencial intrínseco para satisfacer las necesidades explícitas e implícitas._
    _Este punto de vista está mas relacionado con los aspectos del dominio gestionados por los expertos del negocio._
- __Dependiente del sistema:__
    _Capacidad del sistema informático de alcanzar y preservar la calidad de los datos cuando los datos se utilizan en determinadas condiciones_
    _Este punto de vista suele ser responsabilidad de los técnicos del sistema._

-------

## Práctica 1 – Calidad de Software (Parte B)
### Parte IV: Calidad de servicio

#### 17. Describa el concepto de Calidad de Servicio ISO/IEC 20000.

La ISO/IEC 20000 es un estándar reconocido desde el 2005 para la certificación de Gestión de Servicios de TI para las empresas.
La serie 20000 proviene de la adopción de la serie BS 15000 desarrollada por la entidad de normalización y certificación británica BSI.

>Una entrega efectiva de los servicios de TI es crucial para las empresas. Esto es especialmente importante tanto si se proporciona servicios internamente a clientes como si se está subcontratando proveedores. Una manera de demostrar que los servicios de TI están cumpliendo con las necesidades del negocio es implantar un Sistema de Gestión de Servicios de TI (SGSTI) basado en los requisitos de la norma ISO/IEC 20000. La certificación en esta norma internacional permite demostrar de manera independiente que los servicios ofrecidos cumplen con las mejores prácticas. _Wikipedia_

#### 18. Explique cómo se organiza el estándar.

El estándar comprende dos partes principales:
- Parte 1: ISO/IEC 20000 - 1 : 2011 - Especificación.
- Parte 2: ISO/IEC 20000 - 2 : 2012 - Código de prácticas.

Informes técnicos de apoyo
- Parte 3: ISO/IEC 20000 - 3 : 2012 - Guía en la definición del alcance y su aplicabilidad (informe técnico)
- Parte 4: ISO/IEC 20000 - 4 : 2010 - Modelo de referencia de procesos (informe técnico)
- Parte 5: ISO/IEC 20000 - 5 : 2010 - Ejemplo de implementación (informe técnico)

### Parte V: Calidad de procesos de software

#### 19. Explique con sus palabras qué es un proceso.

Un proceso es un conjunto de actividades, pasos a seguir, métodos, prácticas y transformaciones que se usa para mantener y desarrollar software.

> Un proceso se define como un conjunto de actividades interrelacionadas que transforman entradas en salidas.

> Define quién está haciendo qué, cuando y cómo para alcanzar un determinado objetivo.

La ISO lo define como:
> __Proceso o conjunto de procesos usados por una organización o proyecto para planificar, gestionar, ejecutar, monitorizar, controlar y mejorar sus actividades de software relacionadas.__


#### 20. ¿A qué se considera “Proceso de Software”?

Hay que diferenciar entre procesos organizativos, proceso de software y ciclo de vida.

- Ciclo de vida de software es un marco de referencia que contiene los procesos, las actividades y las tareas involucradas en el desarrollo, explotación y mantenimiento de un producto de software, abarcando la vida del sistema.

- El **proceso de software** es un concepto mas amplio _basado en el ciclo de vida_ y cubre todos los elementos necesarios como tecnología, personal, artefactos, etc.

- Procesos organizativos incluye al contexto en el que funciona la organización el proceso de software.

#### 21. Describa el Modelo de Calidad de Procesos de Software ISO/IEC 12207.

La ISO/IEC 12207 establece un modelo de procesos para el _ciclo de vida del software_.

La **estructura** del estándar ha sido concebida de manera que pueda ser adaptada a las necesidades de cualquiera que lo use. Para eso, el estándar se basa en dos principios fundamentales: _Modularidad_ y _responsabilidad_.

Con la modularidad se pretende conseguir procesos con un mínimo _acoplamiento_ y máxima _cohesión_.
Con la responsabilidad se busca establecer un responsable para cada proceso.

En cuanto a los **procesos** del estándar se clasifican en tres tipos:
- Procesos principales
- Procesos de soporte
- Procesos de organización

__Procesos de ciclo de vida del software ISO/IEC 12207:2017__
- Agreement processes (Procesos de acuerdo)
- Organizational Project‐Enabling Processes (Proyecto organizacional - Procesos habilitadores)
- Technical Management Processes (Procesos de gestión técnica)
- Technical Processes (Procesos técnicos)

#### 22. Describa el Modelo de Capacidad de Mejora de Procesos de Software ISO/IEC 15504. ¿Qué nueva familia de normas lo reemplaza? Explique las diferencias.


La ISO/IEC 15504 se compone en 7 partes:
- Parte 1: Conceptos y vocabulario (normativa)
- Parte 2: Realización de la evaluación (normativa) -> Esta
- Parte 3: Guía para la realización de la evaluación
- Parte 4: Guía sobre el uso para la mejora del proceso y determinación de la capacidad del proceso.
- Parte 5: Un ejemplo de modelo de evaluación de procesos.
- Parte 6: Un ejemplo de evaluación del ciclo de vida de sistema
- Parte 7: Evaluación de la madurez de una organización (normativa) -> y esta definen:

Definen **Capacidad y madurez** en 6 niveles.

| Niveles de capacidad | Niveles de madurez   |
|----------------------|----------------------|
| Nivel 5: Optimizando | Nivel 5: Optimizando |
| Nivel 4: Predecible  | Nivel 4: Predecible  |
| Nivel 3: Establecido | Nivel 3: Establecida |
| Nivel 2: Gestionado  | Nivel 2: Gestionada  |
| Nivel 1: Realizado   | Nivel 1: Básica      |
| Nivel 0: Incompleto  | Nivel 0: Inmadura    |

La reemplaza la familia de normas **ISO/IEC 33000** la cual establece los siguientes pilares:

- __Modelos de procesos:__ Definen procesos entidades de evaluación.
- __Marcos de medición de procesos:__ Proporcionan escalas para evaluar características de calidad de procesos especificadas (capacidad) de las entidades (procesos).
- __Procesos de evaluación documentados:__ Proporcionan una especificación del proceso a seguir durante la evaluación.

#### 23. Explique qué significa realizar una certificación bajo la norma IRAM-ISO 9001:2015.

La IRAM-ISO 9001:2015 _(Requisitos de Sistema de Gestión de Calidad - SGC)_ determina los requisitos mínimos para un sistema de gestión de la calidad orientado a asegurar:
- Conformidad del producto
- Aumentar la satisfacción del cliente
- Mejora de la eficacia del sistema

Certificar bajo la norma ISO 9001 significa que determinado proceso (o conjunto de procesos) de nuestra organización cumplirán las normas establecidas por el SGC de la IRAM-ISO 9001.

#### 24. Indique para qué se utiliza la norma ISO 90003. ¿Es posible certificar bajo esta norma?

La ISO 90003 está basada en ISO 9001:2001. Son directrices para la interpretación en el proceso de software. _Proporciona una guía para identificar las evidencias dentro del proceso de software para satisfacer los requisitos de la ISO 9001_.

No es posible certificar ISO 90003.


#### 25. ¿Qué beneficios trae aplicar un Sistema de Gestión de la Calidad (SGC)?

- ISO 9001 asegura que una empresa cumpla los requisitos legales y del cliente.
- Aumenta el rendimiento de la organización. La SGC de la norma ISO 9001 ayuda a implementar procesos simplificados y mejora la eficiencia operacional.
- Mejora la imágen de la empresa al estar certificada con una norma de calidad internacional.
- Al estar basado en un sistema de mejora contínua, mejora los procesos.

#### 26. El “Alcance” del SGC es una descripción resumida del mismo y su naturaleza. Indique qué características debe tener.

Es la descripción del alcance, de los productos y servicios principales, de los supuestos y de las restricciones del SGC.

El enunciado del alcance del SGC documenta el alcance en su totalidad, incluyendo la aplicabilidad de los requisitos de la norma.
El enunciado detallado y documentado del alcance del SGC, ya sea directamente o por referencia de otros documentos debería incluir los siguientes:
- Productor y servicios
- No aplicaciones de la norma
- Ubicaciones física
- Los procesos dentro del SGC


#### 27. Los “Objetivos” del SGC establecen las metas a las que se desea llegar con la certificación y deben suponer un avance, buscando la “mejora continua”. Indique qué características deben tener.

La SGC describe a la mejora contínua realizando los siguientes pasos una y otra vez.
- Planear
- Hacer
- Verificar
- Actuar


### Parte VI: Resumen

#### 30.Indique para cada uno de los siguientes ítems, que estándares/normas son las que más se adaptan para realizar su evaluación. Justifique su respuesta.

**a. Aplicar un SGC a un proceso de mi empresa de desarrollo de software.**

La norma IRAM - ISO 9001 está diseñada y con los pasos necesarios para aplicar un Sistema de Gestión de Calidad (SGC)

**b. Funcionamiento del área contable de la Facultad de Informática.**

Se necesita alguna para certificar la _calidad del proceso_ contable. Normas de Calidad de proceso son las ISO/IEC 15504 y su reemplazo, la familia de ISO/IEC 33000.

**c. Manejo de los datos de una empresa.**

ISO/IEC 25012 Data quality

**d. Desarrollar un software de reserva de aulas para la facultad.**

ISO/IEC 25010. _Modelo de calidad detallado que incluye características de calidad_ __internas__ _y externas._ La evaluación de calidad internas son útiles para el proceso de desarrollo del software.
¿? -> vo' decí? mmm
