# Maquina_de_anestesia_lab6
Instrumentación Biomédica y Biosensores, Ingeniería Biomédica, UMNG (Semestre VII).

### Integrantes
María José Peña Velandia - 5600876. 
Antonia Garzón Vanegas - 5600843. 
Ana Sofia Conde Porras -5600770.

---
## Introducción 
En el presente documento, se hablará sobre las máquinas de anestesia, las cuales su función principal es mantener las funciones vitales del paciente en un estado equilibrado y estable de inconsciencia controlada, cumpiendo las labores de proporcionar oxígeno y ventilación alpaciente, además de mezclar diferentes gases anestésicos en las dosis adecuadas. A pesar de lo fundamental de sus funciones, y de los posibles riesgos que puede simbolizar al paciente un error en la máquina y del operador, no se trata de un dispositivo complejo u hostil, sino se trata de un conjunto de tuberías y sistemas de bombeo quesuministran una mezcla de gases de forma cuidadosamente controlada y de fácil uso y mantenimiento bajo la capacitación adecuada.

## Parte A – Revisión de literatura

### a. ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican durante una cirugía?

En la práctica clínica se reconocen **cuatro tipos** principales de anestesia [1], [2]:

#### 1. Anestesia general
Se administran fármacos intravenosos (propofol, opioides, relajantes musculares) y/o agentes inhalados (sevoflurano, isoflurano, desflurano) que producen pérdida total de la conciencia, analgesia, amnesia y relajación muscular. Normalmente requiere manejo de la vía aérea (tubo endotraqueal o máscara laríngea) y ventilación mecánica. **Es la que se administra con la máquina de anestesia.**
- **Estado del paciente:** inconsciente, sin reflejos protectores; respiración asistida o controlada.
- **Ejemplos:** cirugías abdominales, torácicas, neurocirugía y procedimientos largos.

#### 2. Anestesia regional
Se inyecta anestésico local cerca de un nervio o grupo de nervios para bloquear la sensibilidad de una región del cuerpo. Incluye la anestesia **neuroaxial** (raquídea/espinal y epidural) y los **bloqueos de nervios periféricos** (por ejemplo, bloqueo del plexo braquial).
- **Estado del paciente:** consciente o con sedación; respira por sí mismo.
- **Ejemplos:** cesáreas, cirugía de cadera o rodilla, cirugía de miembro superior.

#### 3. Anestesia local
Se infiltra anestésico local (lidocaína, bupivacaína) directamente en el tejido de un área pequeña.
- **Estado del paciente:** completamente despierto.
- **Ejemplos:** suturas, biopsias de piel, procedimientos odontológicos.

#### 4. Sedación o cuidado anestésico monitorizado (MAC)
Se administran fármacos intravenosos que disminuyen el nivel de conciencia en distintos grados (mínima, moderada o profunda), con frecuencia combinada con anestesia local o regional.
- **Estado del paciente:** relajado o somnoliento; responde a estímulos según la profundidad.
- **Ejemplos:** endoscopias, colonoscopias, cirugía de cataratas.

> **Nota:** según la vía de administración, la anestesia general puede ser **inhalatoria**, **intravenosa total (TIVA)** o **balanceada** (combinación de ambas). La balanceada es la más común en quirófano.

---

### b. ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante sistema de alta presión?

La WATO EX-20 trabaja con tres gases medicinales: **oxígeno (O₂), óxido nitroso (N₂O) y aire** [3], [4], además de los **agentes anestésicos volátiles** que se agregan en el vaporizador.

#### Oxígeno (O₂)
- Gas indispensable para el metabolismo del paciente; garantiza una fracción inspirada de oxígeno (FiO₂) segura.
- Actúa como **gas portador** del agente anestésico.
- En la WATO EX-20 también puede funcionar como **gas impulsor (drive gas)** del ventilador, que es de accionamiento neumático y control electrónico [4].
- Alimenta el **flush de O₂** (lavado rápido) y el sistema de alarma por falla de suministro de oxígeno.

#### Óxido nitroso (N₂O)
- Gas anestésico de baja potencia con efecto **analgésico** y sedante.
- Se usa como coadyuvante: reduce la cantidad de agente volátil necesaria (efecto de segundo gas) y acelera la inducción.
- Nunca se administra sin O₂: la máquina tiene un sistema de proporción O₂/N₂O que impide mezclas hipóxicas.

#### Aire medicinal
- Gas **portador alternativo** al N₂O.
- Permite **disminuir la FiO₂**, lo que evita atelectasias por absorción y toxicidad por oxígeno cuando no se desea usar N₂O.
<img width="945" height="1261" alt="image" src="https://github.com/user-attachments/assets/aefcd5cc-3fe4-4512-8ea6-7337f61df24e" />
(Fig 1. Suministro de gases médicos WATO EX-20.)
Cabe mencionar que los gases anteriores necesitan de un sistema de alta presión pues ingresan a la máquina por medio de cilindros, estos cilindros se conectan a través de uniones de horquilla (yoke) con válvulas antirretorno y filtros, luego los gases pasan por un regulador que reduce la presión a aproximadamente a 400kPa y posteriormente a 200kPa. La presión que pueden poseer estos gases antes de pasar por el regulador varian, por ejemplo el O₂ y el aire pueden poseer una presión de entre 6.9 – 15MPa, en cambio el N₂O es significativamente menor con valores de 4.2 – 6MPa.

#### Agentes volátiles (sevoflurano, isoflurano, desflurano, halotano, enflurano)
- Producen la **hipnosis y el mantenimiento** de la anestesia general.
- Son líquidos que se evaporan en el **vaporizador** y se incorporan al flujo de gas fresco en una concentración controlada (% en volumen).
- La WATO EX-20 admite hasta dos vaporizadores, pero solo uno puede usarse a la vez [3].

#### Sistema de alta presión

La máquina recibe los gases de dos formas:

1. **Suministro central (red hospitalaria):** llega a **presión intermedia** (aproximadamente 280–600 kPa) por mangueras conectadas en la parte posterior del equipo [5].
2. **Cilindros montados en los yugos (*yokes*) de la parte posterior:** constituyen el **sistema de alta presión**. Los gases que se incorporan por este sistema son:
   - **O₂:** cilindro lleno a aproximadamente 2000 psi (≈ 13,8 MPa).
   - **N₂O:** cilindro a aproximadamente 745 psi (≈ 5,1 MPa), almacenado en estado líquido.
   - **Aire:** cilindro a aproximadamente 2000 psi (≈ 13,8 MPa), si la configuración lo incluye.

El sistema de alta presión está formado por el **yugo con sistema de seguridad de pines (PISS)**, un filtro, una válvula de retención (*check valve*), el **manómetro de alta presión del cilindro** y el **regulador de presión primario**, que reduce la presión a un valor intermedio antes de que el gas llegue a los flujómetros [5], [6].

Los **agentes volátiles no** entran por el sistema de alta presión: se agregan en el sistema de baja presión, después de los flujómetros, a través del vaporizador.

**Recorrido del gas:** cilindro (alta presión) → yugo/PISS → filtro y válvula de retención → regulador primario → presión intermedia (aquí se une con la red hospitalaria) → flujómetros → vaporizador → salida de gas fresco.

---

### c. ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

#### ¿Qué es?
El **sistema de respiración** (circuito de respiración o *breathing system*) es el conjunto de componentes que **conecta la salida de gas fresco de la máquina con la vía aérea del paciente**. En la WATO EX-20 es un **sistema circular con absorción de CO₂** (*circle system*), compacto y desmontable [3], [7].
<img width="930" height="689" alt="image" src="https://github.com/user-attachments/assets/b62a54f4-1ea6-4889-aa58-84d1b7f2578b" />
(Fig 2. Diagrama sistema de respiración.) [Manual Service]

#### Funciones
- **Entregar** al paciente la mezcla de O₂, gases y agente anestésico en la concentración programada.
- **Eliminar el CO₂** exhalado mediante el absorbente (cal sodada), lo que permite la **reinhalación** de los gases y el uso de **bajos flujos** (ahorro de anestésico y conservación de calor y humedad).
- Permitir la **ventilación manual** (con bolsa reservorio y válvula APL) o **mecánica** (con el fuelle del ventilador), seleccionadas con el interruptor **Bolsa/Ventilador (Manual/Auto)**.
- **Limitar la presión** en la vía aérea y enviar el exceso de gas al sistema de evacuación de gases (AGSS).
- **Monitorizar** la presión en la vía aérea, los volúmenes (sensores de flujo) y la concentración de O₂ (sensor de O₂).
Es decir, conduce los gases anestésicos desde la máquina de anestesia hasta el paciente y viceversa; elimina el dióxido de carbono (CO₂) exhalado mediante un absorbente de CO₂ (cal sodada – CO₂ absorbent canister); también permite la re‑inhalación de gases (con CO₂ eliminado) para conservar calor y humedad, reduciendo la pérdida de agua insensible y el consumo de agentes anestésicos. Por último, cabe resaltar que dispone de dos modos de ventilación: manual (con bolsa reservorio y válvula APL) y mecánica (con fuelle y ventilador neumático).
<img width="725" height="723" alt="image" src="https://github.com/user-attachments/assets/decc50c2-2c6f-437e-92d3-f9b0f66f3d2e" />
(Fig 3. cal sodada – CO₂ absorbent canister.) [Manual Service]
<img width="960" height="1253" alt="image" src="https://github.com/user-attachments/assets/fe0bd984-a9d9-487d-ac35-8f8683d13b70" />
(Fig 4. Válvula APL y fuelle sistema de respiración)

#### Componentes principales
- **Válvulas unidireccionales inspiratoria y espiratoria:** garantizan que el gas circule en un solo sentido.
- **Recipiente (canister) absorbente de CO₂:** contiene la cal sodada que retira el CO₂ del gas exhalado.
- **Fuelle (*bellows*) y su carcasa:** entregan el volumen corriente durante la ventilación mecánica.
- **Bolsa reservorio:** permite la ventilación manual y sirve de reserva de gas.
- **Válvula APL:** limita la presión durante la ventilación manual o espontánea.
- **Manómetro de presión de vía aérea (Paw):** indica la presión en el circuito.
- **Sensores de flujo y sensor de O₂:** miden los volúmenes inspirados y espirados y la FiO₂.
- **Tubos corrugados, pieza en Y y mascarilla:** conectan el circuito con el paciente.

#### Partes que pueden esterilizarse en autoclave
La mayoría de las piezas del sistema de respiración **soportan autoclave a vapor** hasta **134 °C** (ciclo recomendado de **20 minutos**), mientras que los componentes electrónicos o de medición **no** [5], [8].

** Sí pueden autoclavarse:**
- Bloque o cuerpo del circuito de respiración.
- Válvulas inspiratoria y espiratoria con sus cubiertas.
- Recipiente absorbente de CO₂ (vacío, sin cal sodada).
- Fuelle y su carcasa (el fuelle: 121 °C durante 20 min o 134 °C durante 7 min).
- Brazo de la bolsa y partes desmontables de la válvula APL.
- Tubos corrugados, pieza en Y y bolsas **reutilizables** de silicona.

** No deben autoclavarse:**
- Manómetro de presión de la vía aérea.
- Sensores de flujo.
- Sensor de O₂.
- Tubos y frascos de aspiración, y el sistema AGSS.
- Cal sodada (es desechable).
- Accesorios desechables (de un solo uso).

>  Antes de autoclavar cualquier pieza se debe verificar en el manual que esté identificada como autoclavable. Las piezas no autoclavables se limpian con un desinfectante aprobado o mediante limpieza superficial.

---

### d. ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

Al presionar la tecla **[Menú]** en la pantalla del ventilador de la WATO EX-20 se despliega el menú principal, compuesto por **cuatro submenús** [5]:

#### 1. Modo de ventilación
Permite seleccionar el modo de ventilación: **VCV** (ventilación controlada por volumen), **PCV** (ventilación controlada por presión) y ventilación **manual/espontánea**. También permite ajustar los parámetros del paciente: volumen corriente (Vt), frecuencia respiratoria, relación I:E, PEEP, presión límite (Plimit) o presión inspiratoria (Pinsp) y pausa inspiratoria.

#### 2. Configuración de alarmas
Define los límites superior e inferior de las alarmas: presión de vía aérea (Paw), volumen minuto (MV), volumen corriente (Vt), FiO₂, frecuencia respiratoria y apnea. También permite revisar el historial de alarmas.

#### 3. Configuración de usuario / sistema
Contiene los ajustes generales de la interfaz: brillo de la pantalla, volumen de alarmas y teclas, unidades de presión, idioma, fecha y hora.

#### 4. Mantenimiento
Reúne las funciones de mantenimiento de usuario: prueba de fugas del sistema, calibración de los sensores de flujo, calibración del sensor de O₂ (al 21 % y al 100 %) y configuraciones del sistema (algunas protegidas con contraseña para el servicio técnico).

#### ¿En cuál se activa la pausa inspiratoria?
La **pausa inspiratoria** (parámetro **TIP:TI**, también llamado *Tpause* o *plateau inspiratorio*) se activa en el submenú **Modo de ventilación**, **únicamente en el modo VCV** [5], [9]:
- Se expresa como **porcentaje del tiempo inspiratorio** y se ajusta entre **OFF (apagado) y 5 %–60 %**, en pasos de 5 % [4].
- En **PCV no está disponible**, porque en ese modo la presión ya se mantiene constante durante toda la inspiración [9].
- **Utilidad clínica:** mantiene el gas en los pulmones al final de la inspiración, mejora la distribución del volumen entre los alvéolos y permite medir la **presión meseta (Pplat)**, útil para calcular la distensibilidad (*compliance*) pulmonar.

# Parte B

## 1. Identificación y ubicación de partes del WATO EX-20

# a. Vaporizador

Se ubica en la parte superior de la máquina, en la plataforma de vaporizadores (el EX-20 tiene dos posiciones), conectado en serie al circuito de gas fresco.

Su función es convertir el anestésico inhalatorio líquido (por ejemplo, sevoflurano o isoflurano) en vapor y mezclarlo con el gas fresco en una concentración precisa, que se ajusta con el dial. Está calibrado para un agente específico, compensa temperatura y flujo, y cuenta con un sistema de bloqueo que impide usar dos vaporizadores a la vez.
<img width="934" height="1276" alt="image" src="https://github.com/user-attachments/assets/11d4deaf-20a1-45f4-a7b3-4e19f0c9a5c5" />
(Fig 5. Ubicación vaporizador.)

<img width="622" height="381" alt="image" src="https://github.com/user-attachments/assets/f9ebe11f-fc96-4006-a74d-93ff551921d5" />
(Fig 6. Vaporizador conectado.) [Manual service]


# b. Válvula APL

La válvula APL se localiza en el sistema de respiración, específicamente en el circuito manual. Se puede identificar como un mando giratorio con una escala de presión (en cmH₂O) situado en la parte frontal del sistema de respiración, tal como se observa en la figura 10. La función de esta válvula es durante la ventilación manual, la válvula APL limita la presión máxima que alcanza el circuito cuando se aprieta la bolsa manual; permite ajustar un umbral de presión, por ejemplo de 0 a 75 cmH₂O, si la presión supera el valor fijado la válvula se abre liberando el exceso de gas al exterior o al sistema de evacuación de gases anestésicos. Gracias a lo anterior se protege los pulmones del paciente de presiones excesivas durante la ventilación manual.

<img width="932" height="1259" alt="image" src="https://github.com/user-attachments/assets/55457e81-b616-4e99-8b9f-9239d1b277c4" />
(Fig 7. Ubicación valvula APL.)


# c. Recipiente absorbente de CO2

Se ubica en el sistema de respiración, en la rama espiratoria, como un canister transparente con cal sodada.

Su función es retirar el CO2 exhalado por el paciente mediante una reacción química, lo que permite reinhalar el gas exhalado de forma segura (circuito circular) y trabajar con flujos bajos de gas fresco, ahorrando anestésico y oxígeno. Un indicador cambia de color cuando el absorbente se agota.
<img width="938" height="1286" alt="image" src="https://github.com/user-attachments/assets/658fb15c-5b30-4154-aedf-95de9b0910b7" />
(Fig 8. Ubicación Recipiente absorbente de CO₂.)

# d. Fuelle

El fuelle forma parte del sistema de respiración y se aloja dentro de una carcasa transparente situada en la parte frontal del circuito (se puede observar en la figura 10), la cual se puede desmontar girando en sentido antihorario. este es el elemento que separa el gas impulsor del gas que respira el paciente, cuando el ventilador envía gas impulsor hacia la carcasa del fuelle, este se comprime y empuja el gas anestésico contenido en su interior hacia el paciente (inspiración); durante la espiración, el fuelle se reexpande al permitir la salida del gas exhalado. Finalmente, cabe resaltar que el fuelle es de un material libre de latex y no alergénico, que puede manejar un volumen de 1500ml para el control adecuado de ventilación.

<img width="936" height="1267" alt="image" src="https://github.com/user-attachments/assets/0d051dff-0264-4b4b-b4d7-13f18bd02d4b" />
(Fig 12. Ubicación fuelle.)


## 2. Mensaje "batería en uso" con el paciente conectado

En el manual de servicio se describe que hacer en este caso en la sección 3.12 Power Failure Test; cuando la máquina está funcionando con alimentación de red (AC) y de repente se desconecta el cable de alimentación, la pantalla muestra el mensaje “Battery in Use” y el LED de AC se apaga, mientras que la máquina continúa funcionando con la batería interna, conforme a lo anterior el procedimiento de acción es:

Verificar de inmediato la conexión del cable de alimentación a la red eléctrica y conectarlo nuevamente si se ha soltado.

1. Tras reconectar la alimentación AC, el mensaje debe desaparecer y el LED de AC debe encenderse. Si la batería está descargada, la máquina podría apagarse si no se restablece la AC a tiempo.

2. En caso de que la batería esté descargada y el paciente está conectado, se debe priorizar la seguridad del paciente, por tanto hay que asegurar una ventilación adecuada (manual o mecánica) mientras se restablece la alimentación principal.

3. Una vez finalizada la cirugía o el uso, realizar una prueba de autonomía de la batería y, si es necesario, reemplazar la batería de litio (la lista de piezas reemplazables cada 3 años incluye la batería)

## 3. Frecuencia de reemplazo del recipiente absorbente de CO2

La vida util de este recipinete depende del flujo de gas, el número de pacientes y la concentración de CO₂ exhalado, sin embargo en la sección 4.1.1 del manual de servicio se proporciona indicaciones prácticas:

• En la sección mencionada se listan los sellos del recipiente absorbente como el canister absorvente, que deben reemplazarse cada año para evitar posibles fugas. La cal sodada no se específica porque es un consumible de corta duración.

• En las pruebas de fugas del sistema de respiración (secciones 3.7.2 y 3.7.3), se comprueba que el canister no tenga fugas. La vida útil del absorbente se determina por el cambio de color (indicador químico) que muestran muchas marcas comerciales: cuando el color cambia, por ejemplo de blanco a violeta, el absorbente está agotado.

Ahora bien conforme a lo investigado en la práctica clínica, el absorvente de CO₂ se debe cambiar cada 8-12 horas de uso continuoo cuando el indicador de color muestre agotamiento. En entornos de baja frecuencia como quirófanos con pocas cirugías, se recomienda cambiarlo al menos cada 1‑2 semanas o antes si ha estado expuesto a la humedad.

## 4. Procedimiento para verificar fuga en el cilindro de alta presión

Acorde a la sección 3.3.2 Cylinder High Pressure Leak Test, se deben tener ciertas precauciones previas: para el N₂O, después de la prueba se debe abrir el suministro de O₂, después se debe cerrar el interruptor principal de N₂O y abrir el flujómetro de N₂O para liberar el gas residual, finalmente esperar a que el manómetro de N₂O indique cero. Teniendo la precación explicada se debe seguir el siguiente procedimiento paso a paso:

1. Asegurar que el interruptor general (system switch) esté en la posición ⭘ (apagado).

2. Cerrar todas las válvulas de los cilindros, excepto la del cilindro que se va a probar.

3. Abrir la válvula del cilindro que se está comprobando.

4. Registrar la presión actual del cilindro (leer el manómetro de alta presión correspondiente).

5. Cerrar la válvula del cilindro.

6. Esperar un (1) minuto exacto.

7. Registrar nuevamente la presión del cilindro tras ese minuto.

Ahora bien el criterio para determinar una fuga, depende de la presión del gas impulsor, si este valor disminuye más de 5000 kPa (725 psi), hay fuga; de mismo modo, si la presión del gas no impulsor es menor de 690 kPa (100 psi) también significa fuga. Llegados a dichos casos se debe instalar una nueva junta del cilindro, de cambiarse y aún presentar la fuga se debe de revisar el circuito de alta presión.

## 5. Influencia del sensor de O2 en la prueba del sistema de control de flujo

El sensor de O₂ influye notablemente, pues permite realizar una comprobación de la concentración real de oxígeno (FiO₂) y requiere que el sensor esté previamente calibrado. Para demostrar la impor tancia del mismo en el manual de servicio en la sección 3.4.1 y 3.4.2 se muestra una comparación cuando se uso, o no, el sensor.

1. Prueba sin sensor de O₂:

Para esta modalidad se debe verificar el funcionamiento mecánico que impide que el flujo de O₂ sea peligrosamente bajo cuando aumenta el flujo de N₂O. Para ello se conecta el suministro de gases y se abren sus válvulas por completo, posteriormente se deben llevar los flujos a mitad de escala y comprobar que los flotadores de los tubos de flujo se mueven suavemente, estos porcesos se deben verificar para la medición del flujo de O₂ y N₂O; finalmente se debe probar que si se disminuye el el flujo de O₂, el flujo de N₂O debe disminuir proporcionalmente. Aunque se puede medir y controlar el flujo de e O₂, no se sabe realmente la concentración real del mismo, olo se comprueba que los flujos mecánicos mantengan una relación mínima.

2. Prueba con sensor de O₂:

Para este método se conserva el objetivo anterior, pero adicionando la verificación que la concentración de oxígeno medida nunca sea inferior al 25% durante toda la prueba, es decir, se debe llevar a cabo el mismo procedimiento descrito con anterioridad, pero manteniendo un control estricto de de la concentración de O₂. En llegado caso de que la concentración baje del 25%, la prueba falla y se debe revisar el sistema de enlace o el sensor. La principal ventaja de esta prueba radica en que con sensor de O₂ se detecta fallos en la mezcla real de gases que no serían detectados solo con los flujos.

## 6. Para qué se requiere el sistema de presión negativa

El sistema de presión negativa (succión) tiene como propósito aspirar fluidos corporales, como las secreciones, sangre, vómito, y otros de la viía aérea del paciente (generalmente de la faringe o tráquea) durante la cirugía, para prevenir la obstrucción, la broncoaspiración y la neumonía durante los procedimientos; este sistema está integrado directamente en la máquina de anestesia. Este elemento es fundamental cuando se entiende que durante a anestesia, el paciente no puede toser ni expulsar secreciones voluntariamente, lo que aumenta el riesgo de la obstrucción de la vía aérea, por tanto no es un elemento opcional, sino que es un requisito de seguridad obligatorio

Este elemennto está compuesto principalmente por un generador de vacio, por medio del flujo de gases impulsores; un reguldor de presión negativa, que permite controlar el nivel de vacio requerido; y finalmente un frasco colector para fluidos aspirados y un filtro.

# PARTE C
## A) Fallas que pueden presentarse en el funcionamiento de los subsistemas y sus causas

1. Fallas subsistema de suministro de gases

• Fugas en las conexiones de suministro pueden ocurrir a partir de un tubo de suministro dañado o sello en la conexión deteriorado, también a partir de la propia entrada del suministro.

• El manómetro de presión de red puede muestrar lecturas inexactas o no muestra nada a causa del mal estado del mismo, o una obstrucción en la entrada del suministro.

• No ocurre la alarma “O₂ Supply Failure” cuando la presión de O₂ es baja, o ocurre cuando la presión es normal, se debe a que el interruptor de presión de la entrada de O₂ está mal ajustado.

2. Fallas subsistema de administración de gases anestésicos

• Fuga en el conjunto del pulsador de O₂ u de otros gases puede deberse a un error en el sellado o po el vaporizador sin ajustar correctamente.

• El flotador del flujómetro indica valores incorrectos o no se mueve puede deberse a un flujómetro dañado.

• El sistema de corte O₂‑N₂O no funciona si las válvulas de dichos gases se encuentran en mal estado o directamente dañadas.

3. Fallas subsistema del circuito del paciente

• La fugas en el circuito del paciente son las que más sujetos a fallas están pues depende de si el canoster se encuentra en buen estado o bien instalado, del estado del sello del brazo de la bolsa manual, del frasco colector de agua, de la carcasa y sellos del fuelle, de las válvulas de respiración, de los sensores de O₂ o inclusive por los propios tubos de respiración.

• Errores en las mediciones de concentración de oxígeno se pueden deber a agua acumulada en los sensores, un error en la calibración o en el estado de los mismos.

• La onda de flujo se muestra anormal, a causa de errores en los sensores y controladores de flujo, como una fuga en la línea de muestreo de presión del sensor de flujo.

4. Fallas subsistema neumático del ventilador

• La falla más común es un volumen tidal inexacto, que puede deberse a errores en el sensor de flujo, fugas en el sistema de respiración o en la línea de muestreo de presión del sensor de flujo, en los sensores de presión en la placa monitora defectuoso, un límite de presión demasiado bajo, provocando espiración anticipada, entre otros.

• El ventilador puede no funcionar correctamente después de una prueba de fugas, ya que la La válvula de seguridad no es controlable por la placa auxiliar.

5. Fallas subsistema eléctrico y de alimentación

• Durante la operación, la pantalla y el LED de CA se apagan repentinamente y el ventilador no arranca, lo anterior puede deberse a que la alimentación de CA no está conectada correctamente y la batería interna es insuficiente.

• Al encender, la pantalla se ilumina momentáneamente con destello y luego se normaliza, y se produce una alarma de fallo de comunicación con la placa de potencia; se debe a que el Software de la placa de potencia dañado y se debe reiniciar.

• Si la máquina no arranca puede deberse a un cable del interruptor general suelto, un fusible fundido, el Software de placa de potencia está dañado, el Hardware de la placa de potencia es defectuoso o el interruptor general se encuentra en mal estado.

• No sale gas por la válvula en modo ventilación mecánica, se debe a un interruptor Bag/vent defectuoso o ACGO activado, también por una válvula que no puede abrirse.

## B) Orden de los subsistemas en función del número de fallas asociadas

Sistema de respiración: con más de 20 causas de fuga más fallas de sensores (flujo, O₂, presión) es el subsistema con mayor número de entradas en la tabla y en las pruebas de fugas según el capítulo 5 del manual de servicio.

Subsistema eléctrico y de potencia: con 12 fallas que pueden deberse a problemas de alimentación, pantalla, botones, ventilador y conexiones de red.

Suministro de gases y gas impulsor: aproximadamente 10 fallas, donde se incluyen problemas con manómetros, interruptores de presión, fugas en conexiones y reguladores.

Sistema de administración de gases anestésicos: tiene igual número de fallas que el sistema anterior, por fugas de en pulsador O₂ flush, interruptor general, rotámetros y válvula de corte O₂‑N₂O.

Sistema de ventilación: con 8 fallas que principalmente son e volumen tidal inexacto y apertura de válvulas.

Sensor de O₂ y calibración: específicamente con 5 fallas, que incluyen errores de calibración, conexión y desviaciones.

## C) ¿Qué tipos de anestésicos son los más usados en cirugía?

la anestesia se utiliza depediendo de su uso, y este uso depende de dos categorías, anestésicos intravenosos e inhalatorios, su selección depende del tipo de cirugía, la duración, el estado del paciente y la necesidad de relajación muscular o analgesia adicional; a partir de lo annterior se describen los anestésicos más usados de cada categoría [4]:

1. Anestésicos intravenosos

• Propofol: es sin duda alguna el más usado en la actualidad para inducción y para sedación en procedimientos ambulatorios, ya que permite una recuperación rápida y suave con efecto antiemético, es decir, de aliviar las nauceas.

• Etomidato: se usa en pacientes con inestabilidad hemodinámica o shock, se caracteriza por tener una mínima depresión cardiovascular.

• Ketamina: se usa en procedimientos dolorosos, asmáticos, o en entornos con recursos limitados; pues posee una analgesia potente, manteniendo reflejos protectores y frecuencia cardíaca.

• Tiopental: anteriormente era el más usado, pero fue reemplazado por el propofol, aunque aún se usa en ciertos procedimientos de neurocirugía por sus características barbitúricas, es decir, que es depresor del sistema nervioso central.

2. Anestésicos inhalatrios

• Sevoflurano: de la categoría de las anestesias inhalatorias es el más usado debido a su baja solubilidad sanguínea, no es irritante en vías respiratorias, y posee inducción y recuperación rápidas; es ideal para pacientes de todas las edades por las carecterísticas anteriores, sin embargo, puede generar compuestos nefrotóxicos al reaccionar con el absorbente de CO₂ seco.

• Isoflurano: es menos soluble que el sevoflurano y puede provocar cierto grado de depresión miocárdica, sin embargo es muy estable, de bajo costo y usado en cirugías largas; a pesar de ello posee una recuperación más enta que sevoflurano, adicionalmente puede causar taquicardia.

• Desflurano: de todos es el que menos solubilidad tiene, y con una recuperación extremadamente rápida, destaca en tener un excelente control de la profundidad anestésica aunque requiere de un vaporizador calentado especial y es irritante para las vias inhalatorias.

## Referencias

[1] American Society of Anesthesiologists, "Types of Anesthesia," *Made for This Moment*. Disponible: https://madeforthismoment.asahq.org/anesthesia-101/types-of-anesthesia/

[2] R. D. Miller, *Miller's Anesthesia*, 9.ª ed. Filadelfia, PA, EE. UU.: Elsevier, 2020.

[3] Mindray, "WATO EX-20 – Anesthesia Machine." Disponible: https://www.mindray.com/en/products/anesthesia/wato-ex-20

[4] Soma Technology, "Mindray WATO EX-30/20 anesthesia machine – Specifications," 2020. Disponible: https://www.somatechnology.com/pdfFiles/Mindray-WATO-EX-30-20-anesthesia-machine.pdf

[5] Shenzhen Mindray Bio-Medical Electronics Co., *WATO EX-20 Anesthesia Machine – Operator's Manual*. Shenzhen, China, 2009.

[6] J. A. Dorsch y S. E. Dorsch, *Understanding Anesthesia Equipment*, 5.ª ed. Filadelfia, PA, EE. UU.: Lippincott Williams & Wilkins, 2008.

[7] Mindray, "WATO EX-30/20 Máquinas de anestesia" (folleto). Disponible: https://www.tecnoimagen.com.ar/folleto/HOSPITALARIA/Maquina_Anestesia/Maquina_anestesia_WATO-EX20-30_Mindray.pdf

[8] Mindray, *A-Series Anesthesia System – Cleaning and Disinfection Instructions*. Disponible: https://manuals.online/mindray/medical-equipment/a-series/installation-instructions/1pahj

[9] Shenzhen Mindray Bio-Medical Electronics Co., *WATO EX-35 Anesthesia Machine – Operator's Manual*, 2015.


