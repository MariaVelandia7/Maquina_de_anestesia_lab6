# Maquina_de_anestesia_lab6
Instrumentación Biomédica y Biosensores, Ingeniería Biomédica, UMNG (Semestre VII).

### Integrantes
María José Peña Velandia - 5600876. 
Antonia Garzón Vanegas - 5600843. 
Ana Sofia Conde Porras -5600770

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
(Fig 4. Válvula APL y fuelle sistema de respiración
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

# b. Válvula APL

Se ubica en el sistema de respiración, sobre el circuito del paciente, junto al selector de modo manual/mecánico.

Su función es limitar la presión máxima de las vías aéreas durante la ventilación manual con la bolsa reservorio, permitiendo la salida del exceso de gas hacia el sistema de evacuación de gases anestésicos. Al cerrar la perilla aumenta la presión en el circuito. En ventilación mecánica queda fuera del circuito y la presión la controla el ventilador.

# c. Recipiente absorbente de CO2

Se ubica en el sistema de respiración, en la rama espiratoria, como un canister transparente con cal sodada.

Su función es retirar el CO2 exhalado por el paciente mediante una reacción química, lo que permite reinhalar el gas exhalado de forma segura (circuito circular) y trabajar con flujos bajos de gas fresco, ahorrando anestésico y oxígeno. Un indicador cambia de color cuando el absorbente se agota.

# d. Fuelle

Se ubica dentro de la carcasa transparente del ventilador, integrado al sistema de respiración.

Su función es separar el gas motor (que acciona el ventilador de forma neumática) del gas del paciente. En la inspiración, el gas motor comprime el fuelle y empuja la mezcla hacia el paciente; en la espiración, el fuelle se llena con el gas exhalado. Además permite observar visualmente la ventilación y detectar fugas.

## 2. Mensaje "batería en uso" con el paciente conectado

El mensaje indica que se perdió la alimentación de red y la máquina funciona con su batería interna. Las acciones son:

1. No apagar ni desconectar la máquina; el paciente sigue siendo ventilado.
2. Verificar de inmediato el cable de alimentación, la toma, el interruptor de red y el breaker.
3. Si se restablece la red, el mensaje desaparece y la batería se recarga.
4. Si no se restablece, avisar al equipo quirúrgico y revisar la autonomía restante de la batería.
5. Tener lista una bolsa de ventilación manual autoinflable como respaldo.
6. Reportar el evento a mantenimiento biomédico.

## 3. Frecuencia de reemplazo del recipiente absorbente de CO2

No hay un intervalo fijo en tiempo; el absorbente se reemplaza según su nivel de agotamiento:

- Cuando el indicador de color cambia en gran parte del canister (criterio habitual: cerca de dos tercios).
- Cuando el monitor muestra CO2 inspirado (FiCO2) mayor a 0.
- Si estuvo sin uso por mucho tiempo, ya que puede resecarse y el color puede revertir.

Se revisa antes de cada cirugía y se cambia cada vez que se cumpla alguno de estos criterios.

## 4. Procedimiento para verificar fuga en el cilindro de alta presión

La prueba se hace con la máquina desconectada de la toma de pared:

1. Desconectar el suministro de gas de pared y dejar los flujómetros al mínimo.
2. Encender el sistema y verificar que el cilindro esté bien instalado en el yugo.
3. Abrir lentamente la válvula del cilindro y registrar la presión del manómetro.
4. Cerrar la válvula del cilindro.
5. Observar el manómetro durante el tiempo indicado en el manual (cerca de 1 minuto) y medir la caída de presión.
6. Si la caída supera la tolerancia del manual, hay fuga; se revisan el sello del yugo, las conexiones y el regulador.
7. Repetir el procedimiento con cada cilindro (O2 y N2O).

## 5. Influencia del sensor de O2 en la prueba del sistema de control de flujo

Sí influye. El sensor de O2 mide la concentración de oxígeno en el circuito (FiO2) y es la referencia para comprobar que el sistema de control de flujo entrega la proporción correcta de gases, especialmente el enlace O2/N2O que evita mezclas hipóxicas (menos de 21 % de O2).

Con el sensor instalado y calibrado, la prueba verifica numéricamente que la concentración de O2 se mantiene en un rango seguro al variar los flujos de N2O y O2. Sin sensor, o con el sensor agotado o sin calibrar, esta verificación no es confiable: solo se puede evaluar lo que marcan los flujómetros y no hay vigilancia de FiO2, lo cual es un riesgo para el paciente.

## 6. Para qué se requiere el sistema de presión negativa

El sistema de presión negativa es un módulo opcional de aspiración que genera vacío para extraer secreciones, sangre y fluidos de la vía aérea del paciente o del campo quirúrgico. Funciona generalmente con un principio tipo Venturi, aprovechando el gas de suministro, y tiene regulación del nivel de vacío para no dañar los tejidos. Permite despejar la vía aérea (por ejemplo, antes de intubar o extubar) sin depender de una toma de vacío de pared.

---


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


