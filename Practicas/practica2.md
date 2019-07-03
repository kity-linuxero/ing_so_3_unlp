# Ingeniería de Software III 2019
## Práctica 2 – Auditoría y peritaje de sistemas

### Parte I: Conceptos generales

#### 1. Explicar las razones principales para auditar sistemas y dar ejemplos de cada una.

Objetivos de una auditoría:
1) Salvaguardar activos
2) Asegurar integridad de los datos
3) Asegurar que los sistemas son efectivos
4) Asegurar que los sistemas son eficaces

_Para poder cumplir con los objetivos, se debe recolectar evidencia._

Las principales razones para controlar y auditar sistemas (son 7):
- **Costos por pérdidas de datos**: pérdida de cuentas corrientes, pérdida de los datos de los alumnos.
- **Costos por toma de decisiones incorrectas**:cálculo de amortización erróneo en un bien de poco valor
- **Costos por abusos computacionales** (hacking, virus, abuso de privilegio)
- **Costos por errores de computación**: posible pérdida de vida humana, daño al medio ambiente
- **Valor de hardware y software personal** (Determinar el impacto que alguno de estos valores críticos pueda fallar)
- **Evolución controlada de TI**: La confiabilidad de los sistemas computarizados complejos no está garantizada.
- **Mantenimiento de privacidad**: Hoy en día se maneja gran información de los individuos: trabajo, residencia, tarjetas de crédito... Se podría utilizar datos de la genética humana de una persona para usarla en su contra.

#### 2. Para cada uno de los siguientes interesados, presente un ejemplo de cómo un mal procesamiento de información realizado por un sistema informático, puede conducir a una toma de decisiones incorrecta:
- Gerente de una empresa vinculada a la industria automotriz
- Funcionario de ARBA
- Consejo Directivo de una facultad

#### 3. ¿Qué tipo de abusos computacionales conoce? ¿Cuáles son las consecuencias de estos abusos?

Es un incidente relacionado con tecnología informática, en el cual una víctima sufre una pérdida, y un perpetrador podría lograr alguna ganancia. Las pérdidas por abusos computacionales suele ser sustancialmente mayor que la pérdida por fraudes convencionales
- Hacking
- Virus
- Acceso físico ilegal
- Abuso de privilegios

Las concecuencias pueden ser:
- Destrucción de activos
- Sustracción de activos
- Modificación de activos
- Violación de privacidad
- Interrupción de operaciones
- Uso no autorizado de activos
- Daño físico a personas

#### 4. Explique al menos dos características que diferencien entre un abuso informático y otro tipo de fraude comercial.

Dado a que los sistemas controlan monitoreo de pacientes, cirugías, vuelo de misiles, reactores nucleares, etc un abuso informático puede resultar altamente peligroso e incluir (a diferencia de un fraude comercial):
- La pérdida de vidas humanas
- Daño al medio ambiente

#### 5. Describir con sus palabras que entiende por auditoría de sistemas de información.

_Auditoría en los sistemas de información se **entiende** como la verificación y el control en los sistemas para que los mismos realicen de forma eficiente y segura la tarea para lo cual fueron programados._

#### 6. Explique los cuatro objetivos de la auditoría de sistemas de información.

La auditorías de sistemas de información es el proceso de recolectar y evaluar evidencia para determinar si:
1) el sistema automático preserva los activos
2) mantiene la integridad de los datos
3) permite que los objetivos organizacionales se alcancen con eficacia
4) usa los recursos con eficiencia

#### 7. ¿Qué significa que la alta gerencia implemente un sistema de control interno? ¿Cómo se lleva a cabo?

Un sistema de control interno incluye:
1) Separación de obligaciones (33)
2) Delegación clara de autoridad y responsabilidades (34-36)
3) Reclutamiento y entrenamiento de personal calificado (37-38)
4) Sistema de autorizaciones (39)
5) Documentos y registros adecuados (40)
6) Control físico y documentación sobre activos (41-42)
7) Chequeos independientes de performance (43)
8) Comparación periódica de activos con registros contabilizados (44)

**Control interno - Implementación**

El uso de computadoras afecta de varias maneras la implementación de los componentes de un sistema de control interno.

Ejemplo:
1) En un sistema automatizado deben existir registros
2) Las funciones son realizadas por un programa


### Parte II: Controles y riesgos de Auditoría

#### 8. Explique por qué un control en un sistema de información es un sistema.

>Un _control_ es un sistema que previene, detecta, o corrige eventos ilegales.

Hay tres aspectos claves en esta definición:
1. **Un control es un sistema**
2. Eventos ilegales
3. Los controles son usados para prevenir, detectar o corregir eventos ilegales.

Un control es un sistema -> Habitualmente tendemos a nombrar los controles, teniendo en cuenta sólo un aspecto del control.

Una password se convierte en control, solo en el contexto de un sistema que asegure:
1) Seguridad para elegir password
2) Correcta validación de password
3) Almacenamiento seguro de las password
4) Seguimiento en el uso indebido de passwords

#### 9. Explicar las diferencias entre un control preventivo, control detectivo, y control correctivo. Provea ejemplos para cada tipo de control.

Ej:
- __Control preventivo:__ Instrucciones de cómo completar un formulario. _Las instrucciones no son el control_.
- __Control detectivo:__ Un programa que valida datos de input, rechazando los erróneos.
- __Control correctivo:__ Un programa que detecta el ruido en comunicaciones y permite corregir datos corruptos.


Los **controles preventivos** reducen la probabilidad que ocurran eventos ilegales. 
Los **controles detectivos y correctivos** reducen la cantidad de pérdidas cuando los eventos ilegales ocurren.

#### 10. ¿Cuál es la tarea del auditor en cuanto a los controles?

Determinar si los controles están ubicados y funcionan para prevenir los eventos ilegales.

#### 11. Explique desde el punto de vista de auditoría de sistemas de información el concepto de “factorizar en subsistemas” y qué criterio(s) se aplica(n) para factorizar un sistema en subsistemas.

Para administrar la complejidad se sugiere:
1) **Factorizar** el sistema en subsistemas
2) **Determinar la confiabilidad de cada subsistema**, y las implicancias de cada uno de ellos en el nivel de confiabilidad general del sistema.

#####Factorización:

Para realizar una auditoría se debe factorizar en subsistemas:
- Funciones gerenciales
- Funciones de aplicación


Un subsistema es un componente de un sistema que:
1) Realiza ciertas funciones básicas necesarias para el sistema en general
2) Le permite atender sus objetivos fundamentales

Los subsistemas son componentes lógicas y no físicas. El proceso de particionar en subsistemas se denomina **factorización**.

Es necesario un **criterio** para poder factorizar. Los auditores deben identificar primero, las principales funciones que el sistema realiza para cumplir sus objetivos.

El proceso de factorización termina cuando se han particionado el sistema en partes lo suficientemente pequeñas, de tal modo que puedan ser atendidas y evaluadas.



#### 12. Indique qué otros criterios de factorización existen.

Además de las funciones, existen otras dos guías:

- **Acoplamiento:**
    - Cada subsistema debería ser relativamente independiente de otros subsistemas.
    - Sistemas con _poco acoplamiento_ son mas fáciles de comprender
- **Cohesión:**
    - Cada subsistema debe ser internamente cohesivo.
    - Todas las actividades realizadas por el sistema apuntan a cumplir la función principal del subsistema.

#### 13. ¿De qué manera se mide la confiabilidad de los controles?

Los auditores deben recolectar evidencias sobre la existencia y confiabilidad de los controles, para determinar si las pérdidas por los eventos ilegales se reducen a niveles aceptables

Para cada evento ilegal, se debe considerar:
1) Cómo los controles cubren a este tipo de evento.
2) Cuánto de confiable son los controles.
3) Si puede ocurrir un error material o una irregularidad.

Se publican listas que ayudan a realizar esta tarea. Estas listas muestran, por ejemplo:
- Las caídas en los sistemas de información
- Errores e irregularidades que ocurren en diferentes tipos de transacciones.

_Las listas muestran los controles que se pueden realizar para reducir las pérdidas esperadas por errores o irregularidades._

1) Se deben identificar todos los posibles tipos de eventos que pueden ocurrir en el subsistema.
2) Se deben considerar todos los eventos válidos o ilegales.

Para identificar los eventos, hay que _considerar las principales funciones_ que realiza el subsistema.

Ejemplo de la tabla (transparencia Auditoria - Clase 2 - 31)

| Controles/_Errores-irregularidades_ 	| _Cantidad incorrecta_ 	| _Precio incorrecto_ 	|
|----------------------------------------	|---------------------	|-------------------	|
| **Operador bien entrenado**            	| M                   	| M                 	|
| **Revisión gerencial de ventas**       	| B                   	| M                 	|


Efectividad del Control: A: Alta; M: Media; B: Baja

Para estimar la confiabilidad:
En cualquier nivel de la estructura, los pasos de evaluación son:
1) Identificar las transacciones que ingresan al sistema
2) Considerar los eventos legales e ilegales que puedan ocurrir
3) Asegurar la confiabilidad de los controles que detectan los eventos ilegales.

Detectar nuevos controles -> A medida que se evalúan los sistemas de mas alto nivel, se pueden encontrar nuevos controles

#### 14. Identificar cuatro tipos de riesgos. Explicar la naturaleza de cada uno de ellos.

>Def: El **riesgo de auditoría** es el riesgo de que un auditor fracase al detectar las pérdidas materiales reales, o potenciales, o los riesgos incorrectos.

- RDA: Riesgo deseado de Auditoría
- RI: Riesgo inherente
- RC: Riesgo de control
- RD: Riesgo de detección

`RDA = RI * RC * RD`

_**Riesgo deseado:** el riesgo que se desea correr_

**Riesgo inherente:** refleja la probabilidad que una pérdida material o una imputación errónea exista en algún segmento de la auditoría, antes que sea considerada la confiabilidad de los controles internos.

**Riesgo de Control:** refleja la probabilidad que en algún segmento de la auditoría, los controles internos no prevengan, detecten o corrijan pérdidas materiales o imputaciones erróneas que puedan surgir.

**Riesgo de detección:** refleja la probabilidad que los procedimientos de auditoría utilizados en algún segmento, fallen en detectar pérdidas materiales o imputaciones erróneas.


### Parte III: Proceso de Auditoría

#### 15. Explicar brevemente el proceso de auditoría.

Una auditoría


Existen diferentes procedimientos de auditoria, dependiendo de lo que se desee controlar:
1) Determinar si ocurrieron pérdidas materiales o la información financiera es errónea
2) Determinar la eficiencia y eficacia de las operaciones



#### 16. Enunciar cinco tipos de procedimientos de auditoría que pueden ser usados para recolectar evidencia en una auditoría.

Se usan los siguientes procedimientos para recolectar evidencia

1) Procedimientos para comprender los controles
2) Testeo de controles
3) Testeos substantivos de detalle de transacciones
4) Testeos substantivos de:
    4.1) Balances Contables (Para el caso de determinar pérdidas materiales o información financiera errónea)
    4.2) de resultados generales. (Para determinar eficiencia y eficacia de las operaciones. Ej.: testeos de performance.)
5) Procedimientos de revisión analítica


#### 17. Enumere tres tipos de testeos que se pueden realizar durante una auditoría.

2) Testeo de controles
3) Testeos substantivos de detalle de transacciones
4) Testeos substantivos de:
    4.1) Balances Contables (Para el caso de determinar pérdidas materiales o información financiera errónea)
    4.2) de resultados generales. (Para determinar eficiencia y eficacia de las operaciones. Ej.: testeos de performance.)


#### 18. ¿Cómo se lleva a cabo la planificación de una auditoría? Diferencias entre auditoría interna y externa.

**Planificación de una auditoría**

La primera etapa es la _planificación_

Las tareas que se realizan en la etapa de planificación varían dependiendo si es una:
- Auditoría interna
    1) Asignar personal adecuado a las auditorías
    2) Obtener información del cliente
    3) Realizar procedimientos de revisión analíticos para comprender el negocio del cliente
    4) Identificar las áreas de riesgo
- Auditoría externa
    1) Investigar nuevos clientes
    2) Asignar personal adecuado a las auditorías
    3) Obtener el contrato
    4) Obtener información del cliente
    5) Realizar procedimientos de revisión analíticos para comprender el negocio del cliente
    6) Identificar áreas de riesgo

_Los auditores externos se preocupan por el tamao de los errores en los estados financieros._

#### 19. Describa el contenido de un informe de auditoría.

Un informe típico debería incluir:
1) Una introducción que describa los objetivos de la auditoría.
2) El enfoque general utilizado.
3) Un resumen de las conclusiones críticas.
4) Recomendaciones para abordar las conclusiones críticas.
5) Datos que respalden las conclusiones críticas.


#### 20. Describa los cuatro tipos de opinión que un auditor puede emitir.

Los estándares en varios países requieren que la opinión sea:
1) **Opinión excusada:** En base al trabajo realizado no se puede emitir opinión.
2) **Opinión adversa:** Se concluye que han ocurrido pérdidas materiales o que los estados financieros están distorsionados.
3) **Opinión con calificación:** Se concluye que han ocurrido pérdidas materiales o existen riesgos incorrectos, pero las cantidades no son considerables.
4) **Opinión sin calificación:**v El auditor considera que no han ocurrido pérdidas materiales o no existen registros incorrectos.



### Parte IV: Gobernanza de TI

#### 21. Explique el significado del concepto “Gobernanza de TI”.

Concepto: La gobernanza de TI es un subconjunto de Gobierno Corporativo de las organizaciones que se centra en los sistemas TI, su desempeño y los riesgos asociados.

Gobernanza de TI:
- Trata con la relación entre el enfoque empresarial y la gestión de TI
- Destaca la importancia de las cuestiones de TI
- Promueve que las decisiones estratégicas de TI deben ser tomadas por una junta directiva corporativa.

Metas:
- Asegurar que las inversiones de TI generen valor
- Mitigar riesgos asociados con TI

Definiciones:
>Son estructuras y procesos de liderazgo y organizativos que aseguran que las TI de la organización sostienen y extienden las estrategias y los objetivos de la organización. _Instituto de gobernanza de TI_

>Se trata de especificar los derechos de decisión en el marco de rendición de cuentas para fomentar el comportamiento deseable en el uso de TI.

#### 22. Explique qué es COBIT y cuáles son sus elementos.

**COBIT:** _Objetivos de control para información y tecnología relacionada (COBIT)_ es un conjunto de recursos que contienen toda la información que las organizaciones necesitan para adoptar un marco de gobernanza y control de TI.

- Auditoría
- Control
- Administración
- Gobernanza de TI
- Gobernanza de TI empresarial


#### 23. Explique la diferencia entre Gobernanza y Administración de TI.

Son dos conceptos diferentes.

Administración de TI: Se trata de tomar e implementar decisiones de TI.

Gobernanza de TI: Se trata de quién toma las desiciones de TI
- Quién tiene autoridad para tomar las decisiones importantes
- Quién tiene información para tomar las decisiones importantes
- Quién es responsable por implementar las decisiones importantes

#### 24. ¿Cuáles son los principios de COBIT?

1) Satisfacer las necesidades de las partes interesadas.
2) Cubrir la empresa de extremo a extremo
3) Aplicar un marco integrado
4) Habilitar un enfoque holístico
5) Separar las funciones principales

#### 25. Indicar de qué forma organiza COBIT los procesos de TI.

*COBIT 5** es un conjunto de recursos que contienen todas las organizaciones de información que necesitan para adoptar una gobernanza de TI y un marco de control. Los procesos de TI se dividen en 5 dominios (COBIT 5):

GOBERNANZA
1. Evaluar, dirigir y monitorear
ADMINISTRACIÓN
2. Alinear, planear y organizar
3. Construir, adquirir e implementar
4. Entrega, servicio y soporte
5. Monitorear y evaluar


Elementos sobre el enfoque de COBIT a la Gobernanza de TI

1. Procesos de TI y dominios
2. Objetivos de control
3. Prácticas de control
4. Guías de auditoría
5. Guías de administración


- PROCESOS DE TI -> (auditados por) Guías de auditoría
- PROCESOS DE TI -> (satisfacen) Requerimientos de negocio
- PROCESOS DE TI -> (clasificados en) Dominios
- PROCESOS DE TI -> (control facilitado por) Objetivos de control -> (Considerando) Prácticas de control
- PROCESOS DE TI -> (administrados por) Guías de administración

#### 26. Explicar cómo COBIT clasifica la administración de TI.

COBIT clasifica la administración de TI en 4 dominios:
- Alinear, planear y organizar (APO): Proporciona direcciones a la entrega de soluciones y servicios.
- Construir, adquirir e implementar (BAI): Provee soluciones a DSS para la entrega de servcios.
- Entrega, servicio y soporte (DSS): Recibe soluciones y las hace utilizables para los usuarios finales.
- Monitorear y evaluar (MEA): Monitorea todos los procesos para asegurar que se siga la dirección provista.

#### 27. Justificar la importancia de aplicar COBIT en una organización.

Beneficios generales de aplicar COBIT:
- Permite a los administradores públicos cerrar la brecha entre los requisitos de control, los problemas técnicos y los riesgos comerciales.
- Permite un desarrollo claro de políticas y buenas prácticas para el control de TI en todas las organizaciones gubernamentales.
- Enfatiza el cumplimiento regulatorio.
- Ayuda a las organizaciones del sector público a aumentar el valor obtenido de TI
- Optimiza las inversiones en TI, garantiza una prestación de servicios efectiva y proporciona medidas