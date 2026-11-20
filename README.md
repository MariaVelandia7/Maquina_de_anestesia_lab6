# Maquina_de_anestesia_lab6
Instrumentación Biomédica y Biosensores, Ingeniería Biomédica, UMNG (Semestre VII).

### Integrantes
María José Peña Velandia - 5600876. 
Antonia Garzón Vanegas - 5600843. 



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

