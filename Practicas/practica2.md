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

##### Las principales razones para controlar y auditar sistemas (son 7):
- **Costos por pérdidas de datos**: pérdida de cuentas corrientes, pérdida de los datos de los alumnos.
- **Costos por toma de decisiones incorrectas**:cálculo de amortización erróneo en un bien de poco valor
- **Costos por abusos computacionales** (hacking, virus, abuso de privilegio)
- **Costos por errores de computación**: Procesos automatizados que producen pérdida de dinero o incluso pérdida de vida humanas, daño al medio ambiente.
- **Valor de hardware y software personal** (Determinar el impacto que alguno de estos valores críticos pueda fallar)
- **Evolución controlada de TI**: La confiabilidad de los sistemas computarizados complejos no está garantizada.
- **Mantenimiento de privacidad**: Hoy en día se maneja gran información de los individuos: trabajo, residencia, tarjetas de crédito... Se podría utilizar datos de la genética humana de una persona para usarla en su contra. Prevenir la exposición de datos privados de los usuarios de un sistema.

#### 2. Para cada uno de los siguientes interesados, presente un ejemplo de cómo un mal procesamiento de información realizado por un sistema informático, puede conducir a una toma de decisiones incorrecta:
- **Gerente de una empresa vinculada a la industria automotriz**
Un mal cálculo podría ocacionar información errónea sobre el stock disponible teniendo inconvenientes en el momento de entregar los vehículos.

- **Funcionario de ARBA**
Un fallo en el cálculo de los valores fiscales de bienes puede ocacionar un error de revalorización ocacionando pérdidas importantes de recaudación de la provincia.

- **Consejo Directivo de una facultad**
Una pérdida de datos relacionados con la historia académica de los alumnos.

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

##### Factorización:

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

###### Formas de factorización

Para realizar una auditoría se debe factorizar en subsistemas:
- Funciones gerenciales
- Funciones de aplicación

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
4) Testeos substantivos de: (resultados gerenciales o balances contables)
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

##### Tareas de planificación
 
1) Determinar el alcance de la auditoría
2) Emitir una opinión sobre el RDA.
3) Emitir una opinión sobre el RI.
4) Emitir una opinión sobre el RC.
5) Calcular el RD que se debe lograr para cumplir con el RDA,
6) Recolectar evidencia
7) Documentar evidencia

RDA: Riesgo deseado de auditoría
RI: Riesgo Inherente
RC: Riesgo de control
RD: Riesgo de detección


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
4) **Opinión sin calificación:** El auditor considera que no han ocurrido pérdidas materiales o no existen registros incorrectos.



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

----
## Mi resumen
[Ayuda de memoria - Grafico](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Auditoria#R7R1pc6M49te4anaq0sVhwP7oOOleV022s0nvMR9lkG3NYMQInE7n148kEKfA%2BOBImnRVJwhd6D09vVsTfbl%2F%2FUKAv3vADnQnmuK8TvS7iaap%2BnxKf7GSH1GJpSpRwZYgJ66UFjyjNxgXimoH5MAgVzHE2A2Rny%2B0sedBO8yVAULw93y1DXbzo%2FpgC0sFzzZwy6X%2FQ064i0pnmpWW%2FxOi7U6MrJrz6M0eiMrxlwQ74ODvmSL9fqIvCcZh9Nf%2BdQldtnhiXaJ2nyveJhMj0AubNLi%2FVX57BG9rd7%2Fw%2FHAfPG1XNzdG%2FB1B%2BEN8MXToAsSPmIQ7vMUecO%2FT0lv7QF4g61VlD3iP7PjvPw57XzSln0t8WpZ28RvGvqgIw%2FBHDGxwCDEt2oV7N35LP4j8%2BH%2F24Xf6oHwyxOMdQy8lefoRPwUhwX%2FCJXYx4Z%2BiK%2FyHvtlgL%2FwM9shlVZd8xpryDLyA%2Fnp4phWiVWCfXrm6cVGAD8SGNUsqsBSQLQxr6k3NBAno7oF4D%2Bm30IYEuiBEL%2FmJgBiNt0m9FNL0jxjYJwDeVIYM%2BAysf8%2B%2B%2BxCA1%2FqEuzV7R3BX2oM7qxDPh0GjDzywrD4RQdX0QWNCZ6R%2FAJigqkavqBD1%2BwLcQzzSRDNdOuHbdQ4%2FzL8OjFnhK3YT8CVb0Aqa5r%2FydRPv6V%2Fb%2BLcr6l%2FU0eLgoJBCdqlPFndAdEu%2FNeo5PxotXqdlBQwn%2BOA5CQJ%2F36EQPvuAA%2FE7ZWDzyLhBrptBKQfA2caWIZtpz%2BB6Q99sCXAQRZPMuw3%2FSVoJJlI7HzVfIAnhaz1yllEpbqDPrU9G1CjmyA3BCnxP%2BVt1GpftMrztTGsJ%2F7QhMqHVFOWKBEJryjLofdKH6RB5xWHwfE0BqFfsyo4IvDqe9W2f9U0x4VKpjzddEAJ%2BZCr4GHlhkOn5kRWkVN9UlBzN182CruBY%2FalSQMJoBilKJp9ywTFQx4ZE5%2FkX6EECXOQAphRqcuDTcZEfwNMPewPOnKkM22baWjfNI4f9NU5qqwADTXJOa7JzWmmNjEwHTUY%2BgvBoNhUZLpUYzqMjszzvKHC0VbpgHqcLT%2BANe4wisDUHkTqYgtcFpBGRoJs0PMJdmPynTCc2BvtHyylV2nq0zKYgh%2FTlLdv8yAbuIn6xR47jVhGiVC5RCruE4VpmvOjnOhTGnB6nMLN5mcBMWyMwRiWoD25RznNRsSTwgSfKljgIMUcIunJ0qutDwB%2Fp0vqHENiI0ZjcGZJtnSkuD3PSwD4XWufEoWcWfXQg%2Bw%2FwGi2PHOJ9OiK0UYDiLYI8GxMC7RC0PwlICCZ8VD6PZPXZqtzq3vXH%2Fy9w%2BcB8uN131jH7z4ckYBC%2F%2FoAPgO53D%2B0ZJ4DFwD5BL%2FQrKZty%2FQHvX7B7yKxgQutSBPu2OmdYWpjdZXIaWSKMjrk2DRlh3Gw0285TVRnlqySTmL7ZuNxitqNl0CuRya0LgkCc5sK6VqSfdVxaQ0nxIiJrTOcFhYsuDtEMmdUsCSOn6q0RWu09mQFaNP%2B0KRDqDVk5bdoLKze1clipzY%2BIhMX6syP1Tb2ufksipH6cV%2Fy6pliIXnAz%2BfEnZQ0Nvagm1iRq4k6ZQ216FnP4DNwXsD0A4gDOCNpF2Nedv4sAbg%2BEN6TIDZmLCjvSo1PW5XxOkZlr2N1fh7SLAAUh3AP%2BJ2YnOtzAc6d5pF%2BKdTas73ZkA1phA%2FS8rKVa5e0kSHA32hzdHFmAK1sD9KYGX1278Mi%2FDPK1Bl%2BZyTUR4DIkhT8jb4PJXirQjWfqEYWuppRJwNwoUwCzLQowleHB4EjCQLZ2Y0tfr149U2OEYFs0Vy7nlB0qiid2hDJxswJ8ryDzCMyso%2BbLSEUUs7HEwyOdrqHTRoFVU5vR6dYkH906T%2FKBzBiS1RTyIxuv6cpzBfgRQSAtuYMu3JZ7YjtdSETRTgp87AVgjcoW2rrun6DtHkKQqFBZX4y9gx4oqFXLWty6fp8jZiU%2F3bcTPx3bhz2bQ5B85BaxbdC0g3TrbSJmKkC2%2BEgn7lyytCfJf8sdtP%2BEOFLuO9CHHpd1Ur07XTjOp3l0czWd9r6IPbST%2BMmhG3jCFc%2BJrJlZFq6Q5kjwRoWxUdg8UdjkKsl4DZRrSp7HJE3VNNriSs5T3dzBNeRqi1eKWoicsfl%2B45LK5uCJPa%2B4IMJWwLCT%2FnXgmE0wBdkejKjaL6omoo44eSWGElOCua1JSIZaAvTITmfDl5rEOc37FIisYXs%2BfgSXpcaYYPWq9bIG7bzWXajjEDDB6NefvdqjrGmoiqr7r5PKgJei3A0T4QHBYIsTthxESlaUZTzWEr4jH%2BZSROJ36%2BGqKVruuNclgna3Hq7GEBWgPfjJX5MmzJvSBEWOLB3FQw%2FRGjYkCF5dcaoWLaJKt3pTgZgN9KYNYw1%2BUn3ptODoI%2FEi7lRdKtS3J2obHgl8oV98gtrtDoan%2BWksI7%2Fboy1GVUPrqgZ1ZhbMNqoxLXMfugRxLbOtM2iITpnDlDSMps6VRq%2BR9dZ8gBCtkjm19yl0NkeFXkIv52qOykzVerfZROd5Zn1DmRawtgU3W7HkdazTZ2ALc9voG3QqD5WYoHvjoc6LxFrY2HcTo21DnmgHAwmKjFxRH1xRXiEzlYUcy1ii9gww1aq6Ojz8nLH4bSH9ehsVov3qUDLbOtLT%2BS5znB6xdBhYWjghRRRCFkll9u3WkNS8XtjqymEiKHPTJxPhWsHF0lhpzOYSCLeWSyILl9gLkAOjoIF0hBfuo6K6iDtuKMxRBTHfn2ObZ8T69mlzUV1WwnpNmrWpLWlVKOHfhWzzPkUbS2so2li9ZIMoumsYMSGslFU07aL6Zl4Wake2EWtem25CmPFGgabStqcaxTxzStmbp1OZxjrvmH66YwZfXl95Wv36tPz16a6pY%2BsqshavvB1jQsOmzpdPy6hd4jvarNVd1IqrpUdmdSjHtpzmHeVW521tg9kQLZ0fyyPKshqe27NetdPzIWqn3zlE5716NqnKEE1IP%2BnmVpV%2BcSH5okHiwscQ0BoT%2BkujQs8U0PJmBWs2qxe4Cmk%2FT60%2Fywt07Qhoqgh4HCZe%2F2w0TusDsfWCvcw8koyoWN86YlXVhd1BXr8lzUN1mGeiXngk2IZBEhAJqhLjV%2Bsj3rO7cAHossT1nboLz6o1Cg56ya27cBVnMvVNrM9hwnqs0ql0JZep9i%2FBhmM2Az7vfGkbn%2FKYSYvJCNoe0KaRjU7%2FfNYsZTXbmPnK27AF3yAPeDaCPNssJCTWtkBw7vwrKnf1WfcbRL%2BG2UkncQA2zxWFkuhp7ENSDp2%2B4PtGZVPbllFrKiGQneaYmg9aBPkQrNqssQgy64NTU4siwpE0k8X68y5uHpg15bycOM9vJtM4gTZ2WTJlwiD6gpyYiI6moSoiNc1rxGe6RCOud%2Bm%2FEUu5l7BxLtyE5YP2ZsJsOHufrozDDmKRqjl3hF7AcVWP%2Bg0GIRSBhqxue8PR32DPkMlbBz5%2FVopF0Tp08OkN53IHQ%2BC6ULA2IaGkGtgl5qav6dFNzTK1pKlUogBSxnZuowtQ2kegJ0rKMm6ZCmBpd7hgEfLkL%2FLRR56udQPiXCb1zmdlcpmkrWpBszwajpqyZ%2FOm0QnzXq8DTg7cQYG0h8jnQaDCpQnhL5PZGgR3PNIDCm0qfKJHhrekuCz6Qs0sCc%2BrSJyhWrsBYn5eSq7iTawKhSgkXn3mrJrmUTrKMfFWzzyGbqgFDJ1rEgw1uwz9mJ8X%2BrFw7RPSHH71kYd4GkPu5vf5acX%2BWzZsvQSufeCXjCnNfQKP6QuaZKM8ofG4e9pPW1fydVUVSW5vqeq1RS5dCA6DYumGyZqpIhNRg6vaL01Tc5YadVq4qs8yuvC0EKtSxwqu%2BA0AWXo78n%2FF01WdFuiDJcnJOtM7ZP9UZYgi%2FMeyzKhKU4FPVXqV%2BJKJ1l6bxTilgrC3JuJtzv%2Bg9HYkDjXMwyyfIMKShLNaEr7baI80nCca3r%2Fah4BfQtlMFHTosgVNay85j04BWal1qE8Ef3rrkW9uX%2Bo0i1Kn1BZoSLC%2FxTvOz8setmLWLefQMO4qs2so%2B8TvbGsoPAZM%2Fptww5DtHoJTrjJgkidt7Jx4AUJ0v118sRy74gG4jmQKik1S%2B9AYLN7z1koydwhfyblEHjUlHKcqrllswWo0xLuJqljO5N37YjlFNqjjLKfWa7pVVR9ioNK7B6peQRU6Aqrw7BkUUD%2BYUNkcGdReHP4scbW4kGesI%2FdEW2Zd%2FZY0W2q1534ioX7Ba2ab8t4SH%2Bhvq0aS7PsNsTDN4mV2ptjTvQVZqPoQVVVDpQ6zxkdFv8Gp0yH6m7x%2FoParRxRRdoMC6kfj8JsjQy%2F5bi09H6U3N%2BrP%2F1L96ZH6plVXvy1%2BodpFPOEDll9vV99G5fdJ%2FIaeZxZlXifdKr%2B1svovUdEpkLnyB4AFKtKnm8R3O4ap8gUGYeRNknKKKSLcQRsl2jJak4AwioLcRhqzIo%2BZtnxAIdpyn4%2F0AiG7cpyVxzTruQSmrFrsO%2B5FHyc304yquOur4szCPSeGLKmucMfrJANUrCa47AIsTXYB1sLZoxgtea0Q8%2Bt3GQqive9C7rvEkTKzFWQ4nJG9eEf%2F%2Fs%2Fq%2Fl9phxXtJ8WrskYM7%2FSGWWHF0ZK7NXJSoymRGtvKTqrq1TbtbBzyDV%2BbEAUbCj9GYT1ow0BcXx3fngzo4gSfao%2F2Yp%2FLw5rwK2vjM4P99RoSuGdRPLmnYqes9YInnGbN94Dw66KZoywDekWD9Iza4ThOhx5FdkXt6GZw1n32alyfIPrgZ6OLxp3TtpmmdAuN1HNwJvMcFIq2FvZOtQfAxQFwBZ6ZggxtPomdlvLPFVkrrh7rRtHMg2wrLBngXBA98AwImGyBh9748y%2BLx6%2F%2FaHMePDzygOKJAOcv%2BndEP3JnJ5%2FL7WLV6lzu6VTgFkRTCSB5QZRGxIsSYJ%2FK4GxSv9w9P7c6jQfsMXeiFCCQ4WO0BA%2F3i8qxR0LVAhOrlgmVxIexc0JVHSNwZUIFkwM2J%2BZ3RabiTD95gY7Bx6HA91AuF%2FXVB%2F%2B6%2FgPGl9ZFo9ulvMQtfHB0E4EdZoXjDgb%2Bcoijk4q39JbTKnUxNhOoENMVyByLRrLXMtmzCpcuCONkjuapEtldPUNDRR8JZviQai7pku8eMLv2Q7%2F%2FGw%3D%3D)