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
Las metas que se definan como calidad del producto impactarán en la calidad del proceso de desarrollo del mismo ya que están directamente relacionada y se podría decir que _la calidad del producto es consecuencia de la calidad del proceso_.

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

**La ISO/IEC 9126 está dividida en 4 partes:**
- 9126-1 Modelo de calidad
- 9126-2 Métricas externas
- 9126-3 Métricas internas
- 9126-4 Métricas de calidad de uso

#### 8. Enumere las características que presenta la ISO/IEC 9126-1.

La ISO 9126-1 clasifica la calidad de software en un conjunto estructurado de características y subcaracterísticas. Cada subcaracterística a su vez está dividida en atributos. Los atributos no están definidos en el estándar ya que varían entre diferentes productos de software.

Las **características** y _subcaracterísticas_ son las siguientes:

##### Atributos de calidad externa e interna
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


##### Atributos de la Calidad en uso:
- _Eficacia_
- _Productividad_
- _Seguridad_
- _Satisfacción_

#### 9. Las métricas de la ISO/IEC 9126-2 están definidas en forma de tabla. Explique cuáles son los componentes de esta tabla y qué criterios brinda la norma para la creación de nuevas métricas.

Los componentes de la tabla son:
- Metricname. (Nombre de la métrica). Interna o externa.
- Purpose of the metric. (Propósito de la métrica). Se expresa la aplicación de la métrica.
- Method of application. Proveé un esquema para la aplicación de la métrica.
- Measurement, formula and data element computations: Formulas y elementos para la métrica. Ej.: `X=A/B` A= Número de veces que una acción se hace correctamente. B= Cantidad de intentos.
- Interpretation of measured value: Provee un rango para los valores de la métrica. (Ej, `0<=X<=1`)
- Measure type: Tipo de medida. Por ejemplo (Número de cambios, tiempo, cantidad).
- Input to measurement: De donde se obtienen los datos de la métrica.
- ISO/IEC 12207 SLCP Reference: Identifica el ciclo de vida del software cuando es aplicable.
- Target audience: Para quién va dirigida la métrica.

#### 10. Mencione cuáles son los niveles de puntuación de las métricas.

Depende de cada métrica.

Primero se debe establecer la métrica, su método de aplicación, su fórmula, y luego su interpretación, en la interpretación se establecen los valores de puntuación.

Ej: Para una métrica de suficiencia de pruebas:

Metodo: Contar las pruebas planeadas y comparar con el número de pruebas requeridas para obtener una cobertura adecuada.

Fórmula: X = A/B

A = número de casos de prueba en el plan

B = número de casos de prueba requeridos

Interpretación: 0 <= X

Entre X se mayor, mejor la suficiencia.

Si X es igual a B, se obtiene la mejor puntuación para esta métrica.


#### 11. Explique de qué forma se deben combinar los niveles de las métricas para establecer los niveles de las características y de evaluación.

Se pueden combinar mediante fórmulas o tablas.

Se debe ponderar cada métrica y luego combinarlas para establecer el nivel de la característica.

Ej: Atractividad * 0.3 + Facilidad de uso * 0.6 + Operabilidad + 0.1

Valor de la característica USABILIDAD:
- Inaceptable:  0 < x <= 0.2
- Aceptable: 0.2 < x <= 0.4
- Rang Objetivo: 0.4 < x <= 0.6
- Exc. los req: 0.6 < x <= 1


#### 12. Explique cómo se conforma la familia ISO/IEC 25000 (SQuaRE).

Se conforma con una serie de estándares basados en la ISO/IEC 9126 y la ISO/IEC 14598 cuyo principal objetivo es guiar el desarrollo de un producto de software a través de una especificación de requerimientos de calidad y las características de evaluación de la calidad.
- 2500n: División gestión de la calidad
- 2501n: División modelos de calidad
- 2502n: División de medición de calidad
- 2503n: División Requerimientos de calidad
- 2504n: División evaluación de la calidad  

#### 13. ¿Qué norma de la familia ISO/IEC 25000 reemplaza a la ISO/IEC 9126-1? Explique las diferencias.

La ISO/IEC 9126-1 es reemplazada por la ISO/IEC 25010.

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

- ISO/IEC 2504n - División Evaluación de la calidad
- ISO/IEC 25040 - Evaluation reference model and guide
- ISO/IEC 25041 - Evaluation guide for developers, acquirers and independent evaluators
- ISO/IEC 25042 - Evaluation modules.
- ISO/IEC 25045 - Evaluation module for recoverability


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


Hay caracteristicas que comparten los dos puntos de vista y serían **Inherentes y dependientes**.

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

_Deben ser medibles, realizables y alineados con la política._

#### 28. Dados los siguientes objetivos, indicar si están bien escritos y por qué. Reescribir los que no considere correctos de modo que cumplan con las características.

**a. No tener solicitudes de cambios en los requerimientos funcionales**
- De ser realizable, no se puede asegurar que no vayan a haber solicitudes.
- Reducir la tasa de solicitudes de cambios en los requerimientos funcionales en un n%.

**b. Tener pocos errores en los requerimientos funcionales implementados**
- No es medible.
- Reducir en un n% los errores de requerimientos funcionales implementados.

**c. Tener un desvío promedio (por tarea) entre el tiempo insumido en desarrollo y el tiempo estimado menor al 25%**
- No es mejorable.
- Mejorar el tiempo de desvío promedio (por tarea) entre el tiempo insumido ne el desarrollo y el tiempo estimado blabla


#### 29. El “Mapa de Procesos” busca mantener una estructura coherente de la información documentada del sistema.

**a. Indique cuáles son los tipos de procesos que debe contener y qué representan cada uno de ellos.**
 
ENTRADA: Necesidades del cliente

- **Procesos estratégicos:** Procesos que definen y verifican las políticas, estrategias, objetivos y metas de la organización. Ej.: Comunicación interna/externa. Planificación. Proceso de calidad total.
- **Procesos operativos:** Procesos de producción de bienes y servicios que se entregan al cliente. -> (SATISFACCIÓN DEL CLIENTE). Ej.: Desarrollo del producto, atención al cliente.
- **Procesos de soporte:** Procesos que realizan actividades de apoyo necesarias para el buen funcionamiento de los procesos operativos. Ej.: Control de calidad, selección de personal, compras, etc.

SALIDA: Satisfacción del cliente

**b. Indique qué significan los clientes en el Mapa de Procesos y qué representan.**

Son quienes tienen un requerimiento a satisfacer. En el mapa de procesos aparecen en la salida.

**c. Ubique en el siguiente Mapa de Procesos cada una de las regiones y presente un ejemplo:**

```
(Esto va con recuadritos y eso)

                            Procesos estratégicos
                                ↓       ↓
Necesidades del cliente     Procesos operativos   ->     Satisfacción del cliente
                                ↑       ↑
                            Procesos de soporte
```



### Parte VI: Resumen

#### 30.Indique para cada uno de los siguientes ítems, que estándares/normas son las que más se adaptan para realizar su evaluación. Justifique su respuesta.

**a. Aplicar un SGC a un proceso de mi empresa de desarrollo de software.**

La norma **IRAM - ISO 9001** está diseñada y con los pasos necesarios para aplicar un Sistema de Gestión de Calidad (SGC) y aplicando las directrices de la norma **ISO 90003** para satisfacer los requisitos de un SGC dentro de un proceso de software.

**b. Funcionamiento del área contable de la Facultad de Informática.**

Se necesita alguna para certificar la _calidad del proceso_ contable. Normas de Calidad de proceso son las **ISO/IEC 15504** y su reemplazo, la familia de **ISO/IEC 33000**.

**c. Manejo de los datos de una empresa.**

**ISO/IEC 25012** Data quality: Esta norma establece las características de Calidad de Datos que se deben tener en cuenta a la hora de evaluar las propiedades de datos determinados.

**d. Desarrollar un software de reserva de aulas para la facultad.**

**ISO/IEC 25010**. _Modelo de calidad detallado que incluye características de calidad_ __internas__ _y externas._ La evaluación de calidad internas son útiles para el proceso de desarrollo del software.

O puede ser, la **ISO/IEC 12207** que establece un modelo de procesos para el ciclo de vida del software. ¿?


----
## Mi resumen
[Ayuda de memoria - Grafico](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Calidad.drawio#R7V3bcqO4Fv0aV53z4BR3w2PiJD1dZ1KdSs70TD%2FKINvqxkBjnNvXjwQIEAjMHSdxpmraCCRAWtp77YvETF7uXr74wNveuRa0Z5Jgvczk65kkLWQV%2F58UvEYFmrGICjY%2BsqIiMS14RG8wLhTi0gOy4J65MHBdO0AeW2i6jgPNgCkDvu8%2Bs5etXZu9qwc2sFDwaAK7WPo3soJtVKpLi7T8D4g2W3pnUTOiMztAL47fZL8FlvucKZJvZvLSd90g%2BrV7WUKb9B3tl6jebcnZ5MF86AR1KrzNf%2F38%2F9vmFn7%2Fn36%2F%2B7427fndPH6NJ2Af4heeSZqN27s64LrahvyiJTaiJbcHx0SuA2xkAYuexndOr%2BDUQWCFmlS4d%2F2gYZU74ATQQc0q%2FbVveJebNTIRxD0AKivgwmwfhhAIXimuAvhCyveB7%2F6CS9d2fVzuuA4%2BfbVGtp0r2gY7Gx%2BJ%2BOfzFgXw0QMmaekZTzpc9gT9AGHQXtpo4%2BDiHbIscqcrF59Z2yHstrgMOsmzkCrwpRRLYoJQPLOhu4OB%2F4oviSuouhJViWe1qMeof07niKTEwN9m54cQF4J4Xm6StlPo4h8xevlIvrkS%2FrwHbyt7d%2Bl4wW7%2FsPk6n2tCoY%2BhhadyfIjBtHU3BLM3aemVefCfoBV3rOnukBn%2F%2FnnYebQqnrg%2B6eS0iT9d16MXwiB4jcUWOAQuO1a4O%2F3Xf%2FCBcKHSwx%2FZc9ekQ4Xk6DU%2BYmExk2Qh%2FCPYcJ3gFuyQTS5dhk8sCY%2FA2eN%2F7h6T0S0MJe4Y9%2BCbsKIHqXgF%2FgYGFddJ0XWkdyux4kMbBOiJFaRdxp0rwagkbj%2FuvntwrPBIyKGgxYjvcfcFl0TxpJM3LLtF5L3isbboFaYN9ntyP1IYXxKC4wUFGdzgox%2B0Mv6dooYcUNBwh6U3KHA7XzSmHHpZPqmhTya7mJ3qmZlfOtkHhIx4apCR9CkhoyinCZmcfhDGgcwEwx%2FZAyMMf9VTcujuigGF9vtAaHmobef7cPQu8QWS5L2kJ%2FOEj1zcphVhDUy2wh%2FQfoKE0BVvtqSkW4gMrb27Dp7xeGVYZ%2FQcBTK6KuWiKaTL%2BGUGsllyiomJBaC%2BNnmURTN1uFonZ6j1JOVJzHfoW8ABcXE8VSR6GZ2ZBNE2WEEbTzML%2Bjl6vPGBhSl5cI18bARi04TQNvdAbpicyzzaOvwj58jEoHOK2mdZLpgKSc6kKFDoUr4sU3M25suKoRT4ssjjy7o0kCAUtRMVhIPqzviKVAr2rASlohS04fzHYXf9z7fD9V%2FfFrau%2FC3%2FmOuT8ibxtCjzxx17vgacdOj189BPN%2FSiMNLYVz0ln%2Fy0ozKiwSNEeY7i%2Ba51MPHYd%2BAo%2BP2Qt4fN%2BYkKdUvh8RNdWsmadoQgJKSgLyIgsURAkoUiEZB4RKAHvxlXFUmdicBENhBDIlPGXOU8OyYSGLGSGk1ZySJW4SArKLidTTXv6frYKh%2B7SnRkJz0z56Njjp1SPtlj5zjjVstbF%2BFfcb6vVfIfLgexK9zEgwTxyXIfOU%2BglGs5ArvM%2FaK%2FfoSDaLDCIbEIssJB4AgHdTDh0JkpTiQcjs%2F0Wg52VqwMLRz0mtYDnY6nIh30UulQFUQMQ8WJfDAbBRPvZkt5dmkEPh4aEvnA8gL6DvnZqjpyOlVnXyA6POzdytZaRAcJm9FWmsqTeuu1ZJqzfuOErAzkukrywrGKSpVOLNbN04MYVVkpqhaFqMFjWNpA84PGRtt6HUWFR7K%2FPn7DT%2FP1Zpm05dNToqIaerG4L9VrLYxVJCrzIIRaCMK%2BVG%2FeEcd46CgeqU6OVYio9KOLFZ3VxRyebqhFECk9aGK%2B6cjBUG7ocPd45CfWv%2FbrlQ%2FMX0SLHLOX2O4u6aZmuQG5%2BScWeo5n4CyMgXqu3Oyt0k43WK%2BvbGhi%2FBI9%2BvuA9ihwE2kPSXPAREQTXMlO3cyRvQdNtMZTwW%2FdxjXCVjCpIXZo5OYnNA9B4wY%2BdkpLDrbFCc%2FNaOnDMOfito2njlXZ3fh2wyh2eHQPfYTfngj9AjdoE59mTInpnH7lftwaTj9tJG5e9ZCjUQ9DJP6kz848OgmiPPMQZTJjJiUfyjsiH7nExKnZh9qKfZBpRCif0MVIDhshN%2B9oLYftyJx2GprNYTsKp52R7Od3REVyIBZqZtcOxkW0dyQAWBonCRwex%2Bk6YzDDTW3B40bJOOuD4J0YJ6Ok%2FXgkVpmSldHHHI2WSSpxbp95WSdelovOyFKRWozrEirPZqziFgQLToSjL3AfpIZ%2FpHht0Jho4BbFuMWIrxSVet12JNoOtJCZf7TGrclxaw%2Fw94EILuKa7vBwStzcTd5lUr%2B9z0RbJLrUb5RFQfwpwnP%2BvQ%2FiIgv1LJfhiEu576DvtYGPcHPwh10aeIvnK2Ng7KK1gpFMqNnI0nXWTZcx1lwtWPGkx0yhNs%2F3meSQzJNDssiRQ%2FJgc%2Bn9elAUkdN7XCEuD9R53TPUplzhN7jJY9Q0eTKLzqcweSqD4ENln5L%2FgZDyfYTM007zWhNZoSgXp%2FVgiacVeBzXCBalYvHZCG6AIinnXeNESUe1gakebUhSvzpbSF4Z1vVdX0MPS3AUV6Fr79A%2BgLu6vO5yt3Krb%2FeRSZlIaUSyY0TNtKzhjEOJZ%2BCcJikTJVZ6SzWNQ22osJZ8ouuoh116PzSXkzgZwPwLJ10%2FKJUn%2FA7L5fbQf8LW9AdZSNRNIixYb3Ritk3G5%2BSi9DwJkfAhA11SXatP7ro0IKyKXwu8Zi7wXOQE%2B0zL96Qg60RgwRkr%2FxReUYMp2JIn6yCVxk6zloRzUK2zGMtJsYU2rT0hlxullTE1AoUwYSdN8W2akxu1QW6%2BjCpaaJNk%2Fnh%2BmDMjmkGUM9OgRZK58%2BUQVr8G0eCQf4BtAseEjZoiyTsPcE1Mp9CfnSz1M%2BH%2BiG2Tb0olffUT7rw0uwnhA7jDwDlnI0uadMFa2oomFRn%2FuME06jJ%2FB%2FbSotB9C073jRlNU041DehdG0x0d9njNGjaXcdOK4Lx2QZfmXSDSuW8286kgz%2FpfjvqaQ3%2BpPsGdhtHddLwpVyexz%2Bsyysm17PybTQ%2BqwdMyuVjLtRiLEpUx2XIvDz5BjshxKZZGFwykZmaRk8YErOKLR8rdytwrYMNovSqKLcSkZRFYLqeDaL0pwtSCl7IXd0t3Dc0XB%2Fg3nOddBf1OOUyLrRDFGM0ZLBcL8mLmpVhe56PsM3pAZvE35bpdMAtBzBT4vob4KA3QHLQPq31mM%2FhUTlTY%2BQMKJm3hdBpGo%2BF3ltwem%2FUDCi5MuAyxA4S%2BAUXZ9dmx3WcBgsjY2rfZrmDvEo7LQHu3ZiSkNfbAevgwzeip4gewS8lOJh%2FEcFMwFZLtn918Kh4NgywVrtFTthk3TyKB4jR8QaIQry9iryi%2B2ir5Dq1wyUPmDNbdSvQjSBQ7Rr3PrTw9aHmq1XhmxegXfxKNZ8pJL7EewqiarGGDRdvhPNakOVMdOITakA95wHUdJGzjJqvBbXBvIC88MKpakFWfC2Eeh5UkWZ69t95HXdvb64FMW9Szlqw46o5OTcRk0%2BCTbabwdibYjCi%2BIyjduKIip8YRbo2ceap0m7XwweqtckzsRqbETfHjfrsOstmlvUd8M207o631LJhTDex1cu2xxIs1zyEsV3rEyfBqgYrCnWq0hhGMmpYkmcTnCghMVhCoqvFjDduDmwP%2BzryPdKnupf%2BhdTwY3OnFhSg7qrjQYFpgzvGiQJgNmRkb%2Frvj3XEzKRbfyxOVGjkcmSlnkGzsl3z1ywfD34vkNEWk0KmqKPvgMdJvztqOvgQWzFhSCbqyziNF1%2BtXs3U60amQvQxLkwGNiEgeRG%2FUqUff6w5fpJZorazg1gxe0opgnChqGrOeR8dNUt3TvOZ6SXuer3HEMkPZQ9py2p5xmk%2F1ujt14fLu6L1aQhkDdHZJu0UgWagZvAC0HQHkr4%2F18DHUrsdgR6y2xvvokxhB%2B3CwzgkfSA23OOXZU17kGxE4fq7Y18BqtwTBM%2FX%2FRqYrGkaRsbtcB1mXWMX%2FnT9xNKGmd04Wq3iTJozSdpF1FWHupWv0ROyolB%2BGDvRow4OmoROkgdA0UiJG8ju3QR3Hpbzjd%2BnlsX%2FkY1zUTFynkpDKEbsRg6bqxJnRp%2Bmfc7pP1HlhVxGDRqo7XYxuoxXR9Selt9WmGijp1Bm%2FufeBs782p0vt9D8Nb80g%2F%2BGGTbQIkHBOH%2FFj8KYpOCitt%2BOx%2Fr6na6f6CMjfS5c0nROjog4pidP5W0xNGRUAxNIkvByZpBdUKSxMBKFuhxysLjGokaiFjH5vE7WXXW3kC%2Bqsd0icjQxXSvIKBIalul%2FfhVzOzNRD4jxCyI%2BaGyQybHGG31kuxa0Koav3IkuF%2BFFN4kYBV5a0dzNB49cD%2FrZ2NFJd2SSYTl1vxZNv3y%2FJsmy76FDRUGfukeLCjWxSYt7v1KbtEvfWpmv1z9jiUJ0jo2877Fi2ro%2BesM6CFD3qe8GIL5c1Gtn1bcZHEkuyl%2Fu4lNlqGCbVlRLJbv6TjwS5BD4JiUK8iDDQrcBmnhQFjVWBHMjR9kIRBIDkOoHAUpjnWmggh%2B2iB6vMnpQyYqOxxTivj4eUyhZz5QZTN7iFVrW1qFNGZYiMeKW7sZFW4jeM66UouRoO6KSayjqh0JDfXnP6bLufhC4aIXAxRmBbRCoscjRWiJQEXMIHBmANTaRaykChXYi8Fi6x%2BAApFT0DMBRAFhja%2BmWErA2ABdnAPagg0WhrRI22IbUkRHIWxvdEoFiFn6pODyGQEYBXyhKqy3ehsdl7XyTkhSlaXBp9ATLsalhjY%2BWtYPlohqWZxxFV8x1dhfAgmasC6Rk%2FSsVlHlV3RpJ%2BNB3ScAjvdwH3jbMrseF%2FwI%3D)
