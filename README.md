# Simulación y Monitoreo de Variables Cardiovasculares y Hemodinámicas
**Integrantes:**
- Luciana Carbone Calderón (5600882)
- Paula Andrea Delgado Pecha (5600605)
- Marya Kathalina Prieto Martinez (5600875)

# Parte A
# 1) Revisión de la literatura


**1.1. Monitores de signos vitales**


Los monitores de signos vitales son dispositivos médicos utilizados para medir, visualizar y registrar diferentes variables fisiológicas de los pacientes. Su función principal es proporcionar información continua sobre el estado clínico, permitiendo identificar cambios que puedan indicar alteraciones fisiológicas o condiciones que requieran atención médica. Entre las variables que pueden monitorizarse se encuentran la frecuencia cardíaca (FC), la frecuencia respiratoria (FR), la presión arterial, la saturación periférica de oxígeno (SpO₂) y la temperatura corporal [1].

Estos equipos cuentan con sistemas de adquisición y procesamiento de señales que permiten transformar las variables fisiológicas en valores numéricos y representaciones gráficas. Además, incorporan sistemas de alarmas que notifican al personal médico cuando una medición supera los límites establecidos, facilitando la identificación oportuna de posibles situaciones de riesgo [1], [2].


**1.2. Monitor de signos vitales Mindray uMEC 100**

<img width="400" alt="image" src="https://github.com/user-attachments/assets/66102f3f-4257-422c-a091-f0f907570449" />

**Imagen 1.** Monitor de signos vitales Mindray uMEC 100.

*Tomado de: https://shop.hduhealthcare.com/product/mindray-umec-100-patient-monitor*


El Mindray uMEC 100 es un monitor multiparamétrico diseñado para la supervisión de pacientes en entornos hospitalarios. Este equipo pertenece a la serie uMEC de Mindray y permite visualizar diferentes parámetros fisiológicos mediante valores numéricos y formas de onda en su pantalla [1].

De acuerdo con el manual del fabricante, la serie uMEC permite monitorizar variables como electrocardiograma (ECG), frecuencia cardíaca, respiración, temperatura, saturación periférica de oxígeno (SpO₂), frecuencia del pulso y presión arterial no invasiva (PNI). Dependiendo de la configuración del equipo, también puede incorporar módulos para presión arterial invasiva, gasto cardíaco y dióxido de carbono (CO₂) [1].

Una de sus características principales es la capacidad de generar alarmas visuales y sonoras cuando los valores medidos superan los límites configurados por el operador. Estas alarmas permiten advertir sobre condiciones como frecuencias cardíacas elevadas o disminuidas y niveles de saturación de oxígeno fuera de los rangos establecidos. Su funcionamiento debe realizarse siguiendo las indicaciones del fabricante y bajo la supervisión de personal capacitado [1].


**1.3. Pulsioximetría y medición de la SpO₂**

La pulsioximetría es una técnica no invasiva que permite estimar la saturación de oxígeno de la hemoglobina arterial (SpO₂) y determinar la frecuencia del pulso sin necesidad de extraer muestras de sangre. Su funcionamiento se basa en las propiedades ópticas de la hemoglobina oxigenada y desoxigenada, las cuales presentan diferentes características de absorción de luz [2], [3].

El sensor de pulsioximetría utiliza dos fuentes de luz con longitudes de onda diferentes: una correspondiente a la luz roja y otra a la luz infrarroja. Estas atraviesan el tejido, generalmente a través de un dedo, y son detectadas por un fotodetector ubicado en el sensor. A partir de las variaciones en la intensidad de luz recibida durante el ciclo cardíaco, el monitor procesa la señal y estima la saturación de oxígeno [2].

La señal obtenida se conoce como onda pletismográfica y representa las variaciones del volumen sanguíneo en el tejido asociadas con cada pulsación arterial. Esta señal permite identificar la actividad pulsátil y obtener información relacionada con la frecuencia del pulso. Por lo tanto, además del valor numérico de SpO₂, su representación gráfica permite observar la calidad y estabilidad de la señal adquirida [1], [2].



**1.4. Simuladores de parámetros fisiológicos**

Los simuladores biomédicos son instrumentos utilizados para evaluar el funcionamiento de los equipos médicos mediante la generación de señales o condiciones fisiológicas controladas. Su utilización permite comprobar la respuesta de los dispositivos, verificar sus mediciones y evaluar el funcionamiento de los sistemas de alarma sin necesidad de utilizar pacientes reales [4].

En el caso de los pulsioxímetros, estos simuladores permiten reproducir señales ópticas que representan diferentes valores de saturación de oxígeno, frecuencia cardíaca y condiciones de perfusión. De esta manera, es posible comprobar si el monitor reconoce los cambios introducidos y responde de acuerdo con los parámetros configurados [2], [4].



**1.5. Simulador Pronk OxSim OX-1**


<img width="400" alt="image" src="https://github.com/user-attachments/assets/bf07ba53-453a-4e44-b0c8-5aab1cfe959d" />

**Imagen 2.** Simulador Pronk OxSim OX-1.

*Tomado de: [https://shop.hduhealthcare.com/product/mindray-umec-100-patient-monitor](https://www.medicalexpo.com/prod/pronk-technologies/product-112475-745960.html?)*



El Pronk OxSim OX-1 es un dispositivo diseñado para comprobar el funcionamiento de los pulsioxímetros mediante la generación de señales ópticas simuladas. Su funcionamiento consiste en emitir señales de luz roja e infrarroja que son detectadas por el sensor de SpO₂ del monitor, permitiendo evaluar la respuesta del sistema de medición [4].


De acuerdo con el manual de operación de Pronk Technologies, el equipo dispone de diferentes modos de simulación que permiten representar condiciones fisiológicas específicas. Entre las principales variables que reproduce se encuentran:
- **Saturación de oxígeno (SpO₂):** permite establecer diferentes porcentajes de saturación para comprobar la respuesta del monitor ante cambios en la oxigenación simulada.
- **Frecuencia cardíaca:** reproduce diferentes frecuencias de pulso, permitiendo evaluar la capacidad del monitor para identificar valores bajos, normales o elevados.
- **Índice de perfusión (PI):** representa la intensidad relativa del componente pulsátil de la señal óptica, permitiendo evaluar el comportamiento del pulsioxímetro ante condiciones de perfusión reducida [4], [5].

El fabricante establece cinco modos principales de funcionamiento, cuyas características se presentan a continuación:

**Tabla 1**. Principales funcionamientos.

*Tomado de: Manual de operación y ficha técnica del Pronk OxSim OX-1 [4], [5].*

| Modo de simulación | SpO₂ | Frecuencia cardíaca | PI aproximado |
|:------------------:|:----:|:-------------------:|:-------------:|
| 85 %               | 85 % | 80 bpm              | 2,0           |
| 95 %               | 95 % | 40 bpm              | 2,0           |
| 98 %               | 98 % | 80 bpm              | 2,0           |
| 140 BPM            | 98 % | 140 bpm             | 2,0           |
| Low Perfusion      | 99 % | 80 bpm              | 0,2           |


Estos modos permiten evaluar diferentes condiciones durante la práctica, como la bradicardia, la taquicardia, la disminución de la saturación de oxígeno y la baja perfusión. Sin embargo, es importante considerar que el simulador permite comprobar la respuesta funcional del pulsioxímetro, pero no sustituye las pruebas clínicas necesarias para establecer la exactitud real de la medición de SpO₂ [3], [4].

**1.6. Índice de perfusión y condiciones de baja perfusión**
El índice de perfusión (PI) es un indicador relacionado con la intensidad del componente pulsátil de la señal detectada por el sensor de pulsioximetría en comparación con su componente no pulsátil. Este parámetro permite estimar la intensidad de la señal arterial presente en el sitio de medición [1].

Cuando existe una disminución de la perfusión periférica, la amplitud de la señal pulsátil puede reducirse, dificultando la detección de los cambios ópticos necesarios para calcular la saturación de oxígeno. Como consecuencia, el monitor puede presentar lecturas inestables, errores de medición o dificultades para obtener un valor confiable de SpO₂ [1], [3].

El modo Low Perfusion del Pronk OxSim OX-1 permite evaluar esta condición al simular una saturación del 99 %, una frecuencia cardíaca de 80 bpm y un índice de perfusión aproximado de 0,2. Esta configuración permite analizar el comportamiento del monitor cuando recibe una señal pulsátil de baja intensidad [4].


**1.7. Sistemas de alarmas en los monitores de signos vitales**
Los sistemas de alarmas son elementos fundamentales de los monitores multiparamétricos, debido a que permiten advertir al personal clínico cuando una variable fisiológica supera los límites establecidos. Generalmente, las alarmas se configuran mediante valores máximos y mínimos para parámetros como la frecuencia cardíaca y la saturación de oxígeno [1], [6].

De acuerdo con la norma IEC 60601-1-8, los sistemas de alarmas de los equipos electromédicos deben considerar aspectos como la prioridad de las alarmas, sus señales visuales y sonoras y los mecanismos de control correspondientes. Estos elementos buscan facilitar la identificación de situaciones que requieren atención y mantener una comunicación adecuada de las condiciones de alarma [6].

Durante la evaluación funcional de un monitor, es importante comprobar que las alarmas se activen cuando los valores simulados superan los límites configurados. También debe registrarse el tiempo transcurrido entre la modificación de la variable y la activación de la alarma, ya que permite analizar la respuesta del equipo ante condiciones que podrían representar un riesgo para el paciente.

**1.8. Exactitud y tolerancias de medición**
La exactitud de un equipo biomédico representa el grado de concordancia entre el valor indicado por el instrumento y un valor de referencia. Su evaluación es importante para determinar si las mediciones obtenidas se encuentran dentro de las especificaciones establecidas por el fabricante y las normas técnicas aplicables [3].

En los pulsioxímetros, la exactitud de la SpO₂ se evalúa mediante comparaciones con mediciones de saturación arterial obtenidas por cooximetría. La FDA recomienda considerar los criterios de evaluación establecidos en la norma ISO 80601-2-61, que contempla aspectos relacionados con la exactitud, la perfusión reducida, el movimiento y el funcionamiento de las alarmas [3], [7].

Para evaluar las diferencias entre los valores de referencia y los mostrados por el monitor, se pueden utilizar el error absoluto y el error porcentual, expresados mediante las siguientes ecuaciones:

Error absoluto:
$$
E_a = |V_{\text{referencia}} - V_{\text{medido}}|
$$

Error porcentual:
$$
E_{\%} = \frac{|V_{\text{referencia}} - V_{\text{medido}}|}
{|V_{\text{referencia}}|} \times 100
$$

Estas expresiones permiten cuantificar las diferencias entre los valores programados en el simulador y los registrados por el monitor. No obstante, la tolerancia de medición debe establecerse de acuerdo con las especificaciones particulares de cada equipo y sensor, sin asumir que el error del simulador corresponde directamente a la exactitud clínica del monitor [3], [4].




# 2) Preguntas
**a. ¿Cómo colocar al uMEC 100 en modo “monitor”?**
De acuerdo con el manual de operación del fabricante Mindray, el monitor uMEC 100 ingresa automáticamente al modo de monitorización (Monitoring Mode) cuando se enciende, por lo que no es necesario seleccionarlo manualmente desde un menú [1].

Para realizar este procedimiento se deben seguir los siguientes pasos:
1. Verificar que el equipo no presente daños físicos y que sus cables y accesorios estén correctamente conectados.
2. Conectar el cable de alimentación a la fuente eléctrica.
3. Presionar el interruptor de encendido ubicado en el equipo.
4. Esperar a que finalice el proceso de inicio. Una vez encendido, el monitor ingresa automáticamente al modo de monitorización.
5. Comprobar que los parámetros fisiológicos y las formas de onda se visualicen correctamente en la pantalla.
Es importante tener en cuenta que, durante los primeros dos minutos después del encendido, las alarmas permanecen temporalmente pausadas. Posteriormente, el sistema de alarmas se activa automáticamente.


**b. ¿Qué tipo de parámetros o variables fisiológicas pueden simularse con el
Pronk OxSim OX-1? Explique cada uno.**

El simulador Pronk OxSim OX-1 permite reproducir señales ópticas que representan diferentes condiciones fisiológicas para comprobar el funcionamiento de los pulsioxímetros. Principalmente, permite simular tres parámetros: la saturación periférica de oxígeno (SpO₂), la frecuencia cardíaca o del pulso (FC) y el índice de perfusión (PI).

**1. Saturación periférica de oxígeno (SpO₂):**

Representa el porcentaje de hemoglobina arterial que se encuentra unida al oxígeno. El OxSim permite simular diferentes niveles de saturación, específicamente 85 %, 95 %, 98 % y 99 %, dependiendo del modo seleccionado. Esto permite comprobar la respuesta del monitor ante condiciones de saturación normal y reducida.

**2. Frecuencia cardíaca o frecuencia del pulso (FC):**

Corresponde al número de pulsaciones detectadas durante un minuto y se expresa en latidos por minuto (bpm). El simulador permite establecer frecuencias de 40, 80 y 140 bpm. Estos valores permiten evaluar la respuesta del monitor ante diferentes condiciones, como bradicardia (40 bpm), frecuencia de referencia (80 bpm) y taquicardia (140 bpm).

**3. Índice de perfusión (PI):**

Es un indicador de la intensidad relativa del componente pulsátil de la señal óptica detectada por el sensor de pulsioximetría. Se relaciona con la cantidad de sangre arterial que produce variaciones en la señal durante cada pulsación. El OxSim permite simular valores aproximados de PI de 2,0 y 0,2. El primero representa una condición de perfusión de mayor intensidad, mientras que el segundo corresponde a una condición de baja perfusión, en la que la señal pulsátil es más débil y puede dificultar la medición de la SpO₂ [2], [3].

El fabricante integra estos parámetros en cinco modos de funcionamiento, como se presenta a continuación:

| Modo          | SpO₂ | Frecuencia del pulso | PI  |
|:-------------:|:----:|:--------------------:|:---:|
| 85 %          | 85 % | 80 bpm               | 2,0 |
| 95 %          | 95 % | 40 bpm               | 2,0 |
| 98 %          | 98 % | 80 bpm               | 2,0 |
| 140 BPM       | 98 % | 140 bpm              | 2,0 |
| Low Perfusion | 99 % | 80 bpm               | 0,2 |





**c. En el ámbito clínico ¿Cuáles son las tolerancias o errores máximos
permitidos (EMP) para cada parámetro fisiológico mencionado en la parte
(b)?**


Para establecer las tolerancias de medición es necesario diferenciar entre la exactitud de la señal generada por el simulador y la exactitud del monitor que recibe dicha señal. El fabricante Pronk Technologies establece especificaciones particulares para la simulación de SpO₂ y frecuencia del pulso; sin embargo, no proporciona una tolerancia numérica específica para el índice de perfusión.

**1. Saturación periférica de oxígeno (SpO₂):**

El fabricante establece que el error de saturación mostrado debe ser menor o igual a la tolerancia especificada para el sensor de pulsioximetría. Generalmente, los sensores reutilizables presentan una tolerancia de ±2 %, mientras que los sensores desechables pueden presentar tolerancias de ±2 % o ±3 %.

Por otra parte, en el ámbito clínico, la norma ISO 80601-2-61 establece criterios de evaluación de la exactitud de los pulsioxímetros. Uno de los criterios utilizados es $$ (A_{RMS}\leq 4\%\$$ para el intervalo de saturación de 70 % a 100 %, bajo las condiciones de evaluación correspondientes. Este valor representa un error cuadrático medio, no un error máximo individual permitido para cada lectura.

**2. Frecuencia cardíaca o frecuencia del pulso (FC):**

Según las especificaciones técnicas del Pronk OxSim OX-1, el error de simulación de la frecuencia del pulso es inferior a 1 bpm. Por lo tanto, los valores mostrados por el monitor deberían presentar una diferencia inferior a 1 bpm respecto al valor programado en el simulador.

**3. Índice de perfusión (PI):**

Para este parámetro, el fabricante establece valores aproximados de simulación de 2,0 y 0,2, pero no especifica una tolerancia o error máximo permitido para su medición. Además, el índice de perfusión no cuenta con un límite universal de exactitud clínica aplicable a todos los pulsioxímetros, ya que su interpretación depende del fabricante y del dispositivo utilizado.

Por esta razón, no es correcto asignarle arbitrariamente un error máximo permitido. En la práctica, se debe comprobar que el monitor responda adecuadamente a las condiciones de perfusión simuladas.


# Parte B

# Tabla para verificación de alarmas y errores de medición

**Tabla 3.** Configuraciones y tiempos de respuesta.

*Tomado de: Elaboración propia.*

| Parámetro | Configuración 1 | Configuración 2 | Configuración 3 | Configuración 4 |
|:---|:---:|:---:|:---:|:---:|
| Límite configurado | Bajo 90%, alto 97% | Bajo 90%, alto 97% | Bajo 90%, alto 97% | Bajo 90%, alto 97% |
| Valor simulado | 40 bpm, SpO2 95% | 80 bpm, SpO2 85% | 80 bpm, SpO2 99% | 140 bpm, SpO2 98% |
| Alarma activa | Sí | Sí | Sí | Sí |
| Tiempo de respuesta 1 (min) | 1:03 | 1:22 | 0:18 | 0:20 |
| Tiempo de respuesta 2 (min) | 0:08 | 0:09 | 0:10 | 0:11 |
| Tiempo de alarma (min)| 1:11 | 1:31 | 0:28 | 0:31 |






**Tabla 4.** Valores medidos y errores.

*Tomado de: Elaboración propia.*

| Parámetro | Config. 1 BPM | Config. 1 SpO2% | Config. 2 BPM | Config. 2 SpO2% | Config. 3 BPM | Config. 3 SpO2% | Config. 4 BPM | Config. 4 SpO2% |
|:---|---:|---:|---:|---:|---:|---:|---:|---:|
| Valores simulados | 40 | 95 | 80 | 85 | 80 | 99 | 140 | 98 |
| Valores reales | 40 | 96 | 80 | 85 | 80 | 100 | 140 | 99 |
| Error porcentual | 0% | 1,02% | 0% | 0% | 0% | 1,02% | 0% | 1,02% |
| Error absoluto | 0 | 1 | 0 | 0 | 0 | 1 | 0 | 1 |


# Procedimiento


# Análisis de los resultados


**• Análisis 1: Evalúe estadísticamente las diferencias entre los valores de
energía de referencia y suministrados por el desfibrilador.**


**• Análisis 2: Describa la relación entre la forma de onda que se visualiza en el
D30 y la frecuencia cardíaca/saturación periférica de oxígeno.**



# Conclusión



# Preguntas para la discusión

**• Pregunta 1: ¿Cuál es el principio de operación del Pronk OxSim OX-1 para
simular una onda pulsátil?**



**• Pregunta 2: ¿Por qué la SpO2 baja puede ser un falso positivo (falsa
alarma) en una situación de mala perfusión?**


# Referencias


[1] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., uMEC 60/uMEC 70/uMEC 80/uMEC 100/uMEC 120/uMEC 150 Patient Monitor Operator's Manual, Rev. 2.0, Jul. 2023. [En línea]. Disponible en: https://www.mindray.com/content/dam/xpace/en/site/mdr-sscp/patient-monitor/umec-series-60-70-80-100-120-150-safety-and-performance-information.pdf. 
mindray.com


[2] U.S. Food and Drug Administration (FDA), “Pulse Oximeters,” FDA, [En línea]. Disponible en: https://www.fda.gov/medical-devices/products-and-medical-procedures/pulse-oximeters. 
FDA


[3] U.S. Food and Drug Administration (FDA), “Pulse Oximeters - Premarket Notification Submissions [510(k)s]: Guidance for Industry and Food and Drug Administration Staff,” Mar. 4, 2013. [En línea]. Disponible en: https://www.fda.gov/regulatory-information/search-fda-guidance-documents/pulse-oximeters-premarket-notification-submissions-510ks-guidance-industry-and-food-and-drug. 
FDA


[4] Pronk Technologies, OxSim SpO2 Simulator: Operator's Manual, Rev. O, Jul. 18, 2017. [En línea]. Disponible en: https://www.pronktech.com/wp-content/uploads/2015/02/501-0603-OX-1-Op-Manual-Rev-O.pdf. 
Pronk Technologies


[5] Pronk Technologies, “OX-1 OxSim Optical SpO2 Pulse Oximeter Tester: Features and Technical Specifications,” [En línea]. Disponible en: https://www.pronktech.com/wp-content/uploads/2020/03/OX-1-OxSim-Pulse-Oximeter-Simulator-Features.pdf. 
Pronk Technologies+1


[6] International Electrotechnical Commission (IEC), IEC 60601-1-8:2006. Medical Electrical Equipment—Part 1-8: General Requirements for Basic Safety and Essential Performance—Collateral Standard: General Requirements, Tests and Guidance for Alarm Systems in Medical Electrical Equipment and Medical Electrical Systems, 2006, con enmiendas de 2012 y 2020. 
ISO


[7] International Organization for Standardization (ISO), ISO 80601-2-61:2026. Medical Electrical Equipment—Part 2-61: Particular Requirements for Basic Safety and Essential Performance of Pulse Oximeter Equipment, 3rd ed., Apr. 2026. [En línea]. Disponible en: https://www.iso.org/standard/84595.html. 
ISO



