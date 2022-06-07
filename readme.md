# **Propagation Engineering in Radio Link Desing (1,3)**

## **Introduccíon**

En **1865** Maxwell introdujo la noción de ondas electromagnéticas propagandose con velocidad constante en un medio homogeneo basado en las relaciones de la variación de campos eléctricos y magnéticos.

La velocidad de propagación de OEM en el espacio libre corresponde a la **velocidad de la luz**.

$$ v = c = 3*10^8 (m/s) $$

Varios años despues Hertz encontró que las ondas de radio tienen una naturaleza similar a las OEM pero son invisibles.

### __*Capas de la atmósfera*__

La atmósfera terrestre está compuesta de diferentes:

* Gases
* Vapores
* Meteoros
* Hidrometeoros
* Particulas de polvo

Algunos elementos permanentes de la atmósfera bajo la influencia del sol y otras estrellas haces diferentes capas con características particulares

* **Tropósfera**   
Abarca hasta 20 km e incluye fenómenos climáticos como :


    * Lluvia
   * Nubosidad
   * Nieve
   * Vientos
   * Tormentas
  
   Una de las principales partículas húmedas como la lluvia y la nieve es su atenuación     dependiente de la frecuencia.
   El índice de *permitividad relativa* es :

   $$ E_r  = E'_r - jE''_r $$
   $ E'_r:  $
   Causa la reflexión y la disperción de ondas de radio

  $ E''_r:$
Causa la absorsión de potencia de las ondas de radio y a su vez la atenuación
* **Estratósfera** 


    * Contiene una gran proporsión de los gases admosféricos
    * Bajas variaciones de temperatura con la altura 
* **Ionósfera**

    Tiene un gran impacto en la propagación de ondas de rario y tiene 3 subcapas 
    $$ D, E , F$$ 
  En el día la  $ F $ se divide en  $ F_1$ y $ F_2$

* **Magnetósfera** 
    
    Actúa como escudo protectorantimágnetico 

### __*Otras clasificaciones de bandas*__

| **Modelo Inicial (GHz)** | **Designación de banda** | 
| --------------- | --------------- | 
| 0.225 | P         | 
| 0.390 | L         | 
| 1.550 | S         | 
| 3.900 | C         | 
| 6.200 | X         | 
| 10.900| K         | 
| 36.000| Q         | 
| 46.000| V         |
| 56.000| W         |


| **Modelo Nuevo (GHz)** | **Designación de banda** | 
| --------------- | --------------- | 
| 0.100 | A        | 
| 0.250 | B         | 
| 0.500 | C         | 
| 1.000 | D         | 
| 2.000 | E         | 
| 3.000 | F         | 
| 4.000 | G         | 
| 6.000 | H         |
| 8.000 | I         |
|10.000 | J         |
|20.000 | K         |
|60.000 | L         |
|80.000 | M         |


## **Asignación de frecuencias**

Las bandas de radio son un recurso natural limitado y se debe asignar a diferentes servicios de radio.
Esta asignación debe ser estudiada cuidadosamente y coordinada por todos los países.

Las consideraciones principales son:

* Distribución geogáfica
* Tipos de servicio de radio 
* Volúmen de tráfico de comunicaciones
* Características de la propogación de las ondas de rario
* Tecnologias de vanguardia 

### __*Registro de frecuencias*__
El registro de frecuencias lo debe realizar cada administración competente en cada país **(ANE)**

Tambien el planeta los principales aspectos de las frecuencias asignadas en ciertos servicios debe ser registrados en el **IFRB** (International Frecuency Coordinacion Global)

### __*Regiones ITU de asignaciónde frecuencias*__
La tierra se divide en 3 regiones 

1. Región 1: Asia - Sur, Oceanía
2. Región 2: Europa - Africa - Rusia
3. Región 3: America

![Regiones ITU](regiones.png)

### __*Asignación de frecuencias*__
Además del artículo 5 , la asignación de frecuencias , la **ITU** y la **ITU-R** han oreoarado varias tablas a través de un número de apéndices.
**Ejemplo:**
Dos tips de canales RF para sistemas de relevo de microondas extraidos de la remcomendación **ITU-R** , F.·386 en 8.6 Hz es asi:

* 6 canales con una separación de 14MHz con el siguiente criterio:

$$f_n= f_0 - 108.5 + 14 n $$
$$ f_0 = 8387.5MHz $$
$$f_n'= f_0 - 10.5 + 14  $$
$$n=1,2,...,6$$
Usando la ecuación las frecuencias portadoras a los canales $RX$ y  $TX$ son :

$$f_1= 8293 $$
$$f_1'= 8412 $$


![Canal RF](ejemplo1.png)


## **ITU**
### __*Objetivos*__
En el campo de las radiocomunicaciones los códigos y las normas tienen una posición importante debido a los números de razón.

* La demanda creciente de servicio. 
* El crecimiento en tráfico y capacidades 
* Hay tres partes en un radioenlace en $RX$ y   en $TX$. Para una operación adecuada sus específicaciones deberían estar normalizadas y compatibles , de esta forma no trabajan satisfactoriamente.
* De hecho las normas son un **mínimo** técnico de los requerimientos que deberían reunir las industrias de telecomunicaciones y los proveedores de servicios. 
* Mejores normas redundan en una mejor calidad de servicios.
### __*Regulaciones de Radio*__
Tienen nueve capitulos 

1. Terminología y características técnicas.
2. Frecuencia. 
3. Coordinación , notificación , asignación a diferencias y planes de modificación.
4. Interferencia.
5. Disposiciones administrativas.
6. Disposiciones para servicios y estaciones.
7. Seguridad en la comunicación.
8. Servicios aeronaúticos.
9. Servicios marítimos.

Estas regulaciones se actualizan y modifican en los **WARC** (*Word Administrative Radio Conference*).

La **ITU-R** es un gripo de estudio de telecomunicaciones , por muchos años ha estado involucrado en directrices técnicas bajo varias recomendaciones.

Los productos de la **ITU-R** son preparados en diferentes series.

La serie **P** está dedicada a la radio-propagación.

Algunas recomendaciones se trabajarán a los largo del curso(*ver adelante*).

![Tipos de radioenlaces](Tiposderadioenlaces.png)

1. Onda de tierra.
2. Onda reflejada.
3. Línea de vista.
4. Enlace troposférico.
5. Enlace ionosférico.
6. Enlace satelital.
7. Onda espacial.



* AM radio:
  * Ayuda de radionavegación.
  * Sistema de onda corta.

* Ondas multicaminos
  * UHI , microondas.
  * IM , TV.




* Microondas , UHF y Radio
* Retracción , reflexión de ondas en la tropósfera y usan troposcatters transhorizontales.
* Comunicación a larga distancia , usando la reflexión  en la ionósfera en las capas D ,E y F en MF, HF y radiodifusión
* Comunicaiones entre satélite y estaciones terrestres con distancias al rededor de 40000 Km
* Comunicaión entre la tierra y estaciones espaciales.
## **Servicios de Radio** 
Las ondas de radio se utilizan para transmitir varias clases deseñales de:
* Audio.
* Video.
* Datos.
* Control.
* Navegación.

Entre los numerosas aplicaciones tenemos:

* Servicios móviles , aeronáuticos , de tierra y marítimos.
* Búsqueda y rescate y ayudas de navegación.
* Servicios fijos de baja , media y alta capacidad.
* División de audio y video.
* Telemetría , SCADA y sensado remoto.
*Sistemas de control de tráfico aeronáutico de tierra y marítimos.
* Servicios de radioespaciales para aplicaciones industriales, científicas , investigación , médicas y sociales.
## **Propogación troposférica**
La mayoría de las transmisiones de radio se realizan en la tropósfera. 

Algunos tips de sistemas de radio son:

* PtP
* PtM
* PtArea
 
En las líneas de vista:

* **UHF EHF**
* **SHI**
* **BO:** Servicios de difusión satelital
* **BR:** Grabación de sonido y TV.
* **BS:** Broadcasting service (sound)
* **DT:** "         " (TV)
* **L:** Lixed service
* **IS:** Interservice sharing and compatibility
* **M:** Mobile ,radio determination , amateur y related satelite servicios.
* **P:** Radio wave propagation
* **RA:** Radios Astronomy
* **S:** Fixed Satelital
* **SA:** Space aplicattion an metereology
* **SF:** Frecuency Sharing beetwen the fixed satellite and hixed service
* **SN:** Gestión de espectro
* **TF:** Señales de tiempo y normas de emisión 
* **V:** Vocabulario

*Radio móvil : TV , IM , VHF , UHF*

Debido al gray iss de estos sistemas  de comunicaciones , el estudio de la tropósfera y sus impactos en la propagación de OEM es extremadamente importante.

Existen otros tips de comunicaciones donde solo una parte del enlace están en la tropósfera.

**Por ejemplo**
* **Satélite:** Voz , video , datos , ayudas de navegación.
* **SAR:** Search and recover
* **Posicionamiento y telemetría**
* **Comunicaciones ionosféricas a HF y MF**

Hay unos fenómenos naturales que ocurren en el plano de las ondas de radio y afectan:

* Nivel de la señal
* Calidad 
* Desempeño

Básicamente la propagación de ondas esta afectada por uno o varios aspectos:

* La tierra y sus características físicas y naturales 

  * Estructura 
  * Rugosidad
  * Material
* Condiciones ambientales como:
  * Temperatura 
  * Humedad
  * Composición atmosférica
  * Moléculas del aire como
    * Oxígeno 
    * Nitrógeno
    * Vapor de agua

* Fenómenos atmosféricos como:
  * Vientos
  * Tormenta
  * Nubes
  * LLuvias 
  * Nieve 
  * Granizo

* Fenómenos celestes 
  * Tormentas magnéticas 
  * Efectos estacionarios
  * Manchas solares
* Cosas artificiales 
  * Partículas químicas 
  * Gases generados por fábricas

Lamatoría de los efectos a estos fenómenos depende de la frecuencia de la onda.

Un estudio de estos fenomenos a enventos de la serie **P** de los recomendados de la **ITU**.
 ### __*Efectos de ondas de radio troposféricas*__
 * Absorción y atenuación
 * Reflexión 
 * Ductos troposféricos 
 * Despersión y difusión 
 ### __*Tropósfera normal*__

 La tropósfera normal se deriva con el onjeto de vacio posible calcular las pérdidas debido a los componentes gaseosos en la atmósfera terrestre y para definir la :
 * Temperatura
 * Presión atmosférica

Con respecto a la altitud , esta es la recomendación  :

 $$ ITU-R , P-835-8$$

 La presión estándar y la temperatura estándar en la superficie terrestre es :

 $$P_0 = 1,013.35 hpa$$
 $$T_0 = 288.15  K$$

 La atmósfera se divide en 7 capas consecuticas , que se pueden ver en la siguiente figura : 


![Capas de la atmósfera](grafica.png)

$$T(h)= T_i + L_i (h-H_i)$$
$$T_i = T(H_i)$$

**$L_i:$** Gradiente de temperatura en la altitud  $H_i$

**$h:$** Altura en Km

**$T:$** Temperatura en K 


| **i** | **$H_i$** |  **Gradiente $L_i(ºK/km)$** | 
| --------------- | --------------- |  --------------- | 
| 0 | 0         |  - 6.5        | 
| 1 | 11        |  0        | 
| 2 | 20        |  + 1.0        | 
| 3 | 32        |  + 2.8        | 
| 4 | 47        |  0        | 
| 5 | 51        |  - 2.8        | 
| 6 | 71        |  - 2.0        | 
| 7 | 85        |  -   | 


Los cambios en la distribución de varios están dados proximamente por :

$$ \rho(h)= \rho_0 e^{-(h/h_0)}$$

$h_0=2 km$ 

$\rho_0= 7.5 g/m^3$ 


La presión de la capa de agua también del lugar , altura y estación del aire 

La presión deñ vapor de agua también deriva exponencialmente con la altura en partículas.

Para calcular la atenuación causada por otros gases atmosféricos , se hace un procedimiento similar.

$$H_0= 6 km$$

### __*Refracción de ondas de radio en la tropósfera*__

La propagación de ondas de radio en la atmósfera terrestre siempre sifrir el fenómeno de refracción.

En la medida que aumenta a altos la densidad del aire y en concecuencia el índice de refracción se decrementa.

Esta es una característica no homogenea del aire que cauda la desviación de ña onda , de  tal forma que no viaja en línea recta.

Cuando el índice de refeacción cambia linealmente con $h$ altura , el rayo suma unis aros de un círculas con un radio cosntante.

#### *Índice de refracción  del aire*

El índice de refracción de cada ambiente está relacionado con la permitibilidad relativa deacuerdo a la sigiente ecuación.

$$n=\sqrt{ \varepsilon_r }$$

Aplicando la relación apropiada para $\varepsilon_r $ encontramos:


$n=\sqrt{ \varepsilon_r } = {(1 + \frac{155.1}{T} [P + \frac{4810e}{T}*10^{-6}] )}^{1/2}$ **(1.7)**

Usando la expansión binomial y seleccionando los primeros dos términos tenemos 

$n= (1 + \frac{77.6}{T} [P + \frac{4810e}{T}*10^{-6}] )$ **(1.8)**  
Ya que es difícil usar el calor de este término en los cálculos , se utiliza otro parámetro llamado número de retractividad , denotado **N** lo denominamos así:

$N=(n-1)*10^{6} $**(1.9)**

Deacuerdo a esta definición el número de retractividad del aire a nivel del mar y una altituf igual a 1 Km  es :

$$h=0 \Rightarrow N_0=289$$

$$h=1 \Rightarrow N_0=251$$

También un nuevo parámetro llamado índice de refracción modificado denotado por:

$n_M= n + h/R_e$**(1.10)**

*En la ecuación anterior*

$n:$ Índice de refracción del aire

$h:$ Altura

$R_e:$ Radio terrestre

*$h$ y $R$* en unidades iguales

Hay otros parámetros llamados módulo retractivo y se define como:


$M=(n_M -1)*10^{6} $**(1.11)**

$M=N + 10^{6}h/R_e $**(1.12)**

**Ejemplo 1.3:**

Calcule el valor de **$n$** y **$N$** para el aire a una altitud de 2 km basada en la fórmula 1.7 

$$h=2 km \Rightarrow T=277 ºK \Rightarrow \rho=716 mb \Rightarrow e= 2 mb  $$ 

#### *Radio efectivo en la tierra*

La refracción de las ondas de radio en la atmósfera terrestre tienen varios efectos en su propagación y puede producir en un viaje más allá del horizaonte.

Se puede obtener en línea recta conducir el radio terrestre **(Re)**

$$ R'_e= 8,500 km$$ 

$$ R_e= 6370 km  $$ 

### __*Factor K*__
#### *Definición*

Para analizar el espacio libre de las ondas de radio en los enlaces de línea de vista , es preferible asumir un camino recto para la propagación en lugares de una trayectpria curva.

Esta suposición puede ser satisfectoria considerando un factor llamado **K** que está definido como la razón entre el radio equivalente con la tierra **(R'e)** a su valor actual **(Re)**.

Ek factor **K** es un parámetro dinámico que depende de las variaciones del índice de refracción en la atmósfera.

![ Variación del factor K](grafica3.png)

#### *Rangos de variacíón del factor K*

Los valores de **K** juegan un papel importante en el diseño de radioenlaces.

Su valor y el rango de variación estan relacionados con las condiciones específicas del sitio.

Los siguientes valores de **K** son usados para analizar los fenómenos de propagación en radioenlaces terrestres de línea de vista.
* Valor estándar de $k=4/3$ ,se usa generalmente como criterio de propagación *LOS*
* El menor valor de **K** , por ejemplo $K= 2/3$ , causa que el radio efectivo de la tierra disminuye y en concecuencia el camino ente dos puntos particulares con una distancia específica tiene más protuberancias.

Por lo tanto , se necesitan torres más altas para *LOS* , aumentando el costo de la implementación.

* Para valores mayores de 4 , por ejemplo , $K=2$ causa un gran rango de *LOS* anormal que produce la formación a caminos reflejados indeceados.

* El valor efectivo de 4 que es llamado $K_e$ y está bajando en un gráfico aproximado por condiciones ambientales concecuencia y amplitud utilizando en el diseño de sistemas de radio fijos en un rando de 2 - 10 GHz.

![ Condición de trayectoria vs N'](tabla1.png)

Si es gradiente vertical del número de refractividad se representa como :

 $$ N'= dN/dh$$

 Tenemos las siguientes condiciones : 

 * **$N'>0 : $** Subrefracción
 * **$N'= -39 : $** Refracción normal
 * **$N'= -157 : $** Condición crítica $(K=\infty)$ lo que significa que la onda se propaga paralelo a la superficie terrestre
 * **$N'< -157 : $** Superrefracción condición que causa el efecto de conducto.

 El estado relativo de la propagación de la onda y la superficie terrestre se ve en la siguiete figura , para los tres casos de la tierra.


![ Trayectoria del rayo relativa a la Tierra](rayos.png)

#### *Curvatura terrestre*

La curvatura entre el transmisor y el receptor está definida como la altura de cada punto de la tierra equivalente con respecto a la línea recta **T-R**

![ Geometría de la protuberancia de la tierra](tierra.png)

Este parámetro se puede calcular como :

$$ h_k = \frac{500d_1d_2}{k R_e}$$ 
La máxima altura se obtiene en la mitad de la trayectoria que es igual a :

$$h_M= \frac{125d^2}{k R_e}$$

En las dos ecuaciones anteriores $h$ es la protuberancia de la tierra en metros 
* **$R:$** Radio actual de la tierra
* **$d_1:$** Distancia entre $P$ y $T_x$
* **$ d_2 :$** Distancia entre $P$ y $R_x$
* **$d:$** Distancia total en Km

Deacuerdo a estas ecuaciones la protuberancia es inversamente proporcional al valor de *k* 

En la medida en que *k* disminuye , la protuberancia de la tierra y las alturas del transmisor y receptor aumentan.

**Ejemplo 1.4**

Si la permitividad relativa del medio  is 1.001 , el gradiente vertical es :

$$-35*10^{-6}$$

Y  la distancia entre el transmisor y el receptor es 20 km.

1.  Encuentra la curvatura terrestre

$$\varepsilon_r= 1.001$$

$$ n=\sqrt{\varepsilon_r}= 1.0005$$

$$R= \frac{n}{dn/dh}=\frac{1.0005}{35*10^{-6}}=28.586 km$$
$$K= \frac{R}{R-R_e}= 1.287 $$
$$h_M=\frac{125*20^2}{1.287*6370}=6.1m$$
## **Trayectoria y factor K**
### __*Curvatoria del rayo*__

Las indas de radio que pasan a través de la atmósfera estan reflejandose continuamente 

Con el incremento de las alturas la dendidad del aire disminuye , lo que produce una valoración del índice de refracción.

Debido a los efectos de refracción el rayo seguía a una línea recta y seguirá una trayectoria curva.
## **Propagación Ionosférica**
 El fenómeno fundamental de propagación en la tropósfera se explicó en la sección anterior.

 En esta sección estudiaremos los fenómenos principales de la propagación de ondas de radio en la ionósfera.

 Esta capa inicia desde la altura de 50 km y se extiende hasta los 600 km 

 En el caso que una onda de radio entre en esta capa se verá afectada por fenómenos específicos de esta capa.

 Las que se afectan son las señales de **MF** y **HF** , así como las comunicaciones espaciales y satélites, daña uno a los dos extremosque estén en la tierra.

 ### __*Subcapas de la Ionósfera*__

 Tenemos 3 subcapas: *D,E y F* con las siguientes características principales.

 * **D:**
    * Su altura alcanza los 70 km durante el día
    * La cantidad de electrodos y su densidad se relaciona directamente con la actividad solar
    * Su impacto es mayor en verano que en invierno
    * La absorsión de potencia de la subcapa **D** es más significativa en las frecuencias bajas de HF

* **Sub-capa E**

  * Está sobre la sucbapa **D** con una altitud de 100 km
  * Es la capa atmósferica más baja y es capaz de reflejar - refractar ondas de radio
  * Su impacto en la propagación de ondas de radio durante el día es mayor que durante la noche , con un máximo al mediodía y un mínimo al atardecer.
  * Su impacto es mayor durante el veranoque durante el invierno 

  * Teniendo en cuenta la naturaleza refractiva de las ondas de radio, puede cubrir comunicaciones de unos 2.000 km en la banda **MF/HF**.

  ![Capas de la Ionósfera](montaña.png)

* **Sub-Capa F**
    * Está sobre la sub-capa **E** y se extiende hasta 300 a 1000 km 
    * Suministra comunicaciones de radio a larga distancia hasta de 4000 km enla banda de **HF** durante la noche mediante un solo salto de radio.
    * Durante el día se divide en **$F_1$**  y **$F_2$** y se unen durante la noche.
    *  **$F_1$** se comporta de manera simílar a la sub-capa **E**
    * **$F_2$**  tiene la mayor densidad de ionización atmosférica.
    * **$F_2$**  es capaz de proporcionar comunicaciones de hasta 4.000 km con un solo salto de radio.

### __*Ionización y estado de plasma*__
 
La propiedad más importante de la ionósfera son sus gases ionizados , la cantidad de gases ionizados en esta capa es mucho mayor que los gases inertes.

Esta capa puede cambiar las propiedades eléctricas que son factores degterminantes y tienen una gran influencia en la propagaciónde ondas de radio.

El estado de la materia es el plasma , ya que la ionósfera tiene la mayoria de las propiedades del plasma.

Debido al hecho de que la mayor parte del mundo visible está en estado de plasma, el estudio del plasma es valioso no solo para la propagación de ondas de radio sino también para la percepción del mundo del plasma.

Esta no es una capa estática y se estudia mediante monitoreo y unas pruebas periódicas.

La tierra está bombardeada por rayos cósmicos , algunos de ellos tienen grandes amplitudes y transmiten una cantidad considerable de energía que permite que los electrones se separen de las moléculas y formen iones positivos y negativos.

El número de electrones libres por unidad de volumen se denomina densidad del plasma.

Este parámetro se representa en función de la altura.

___

## **Solución ejemplo 1.3**

$$h=2 km \Rightarrow T=277 ºK \Rightarrow \rho=716 mb \Rightarrow e= 2 mb  $$ 

$$\varepsilon_r= 1 + \frac{151.1}{277} (716 +  \frac{4,810*2}{277})*10^{-6} = 1.00042$$

$$n=  \sqrt{\varepsilon_r} = 1.00021 $$

$$ N = (n-1) * 10^{6}  \Rightarrow N= 210 $$

___
 ### __*Clasificación de la ionósfera*__

 Varios tipos de rayos cósmicos ionizan diferentes moléculas en la atmósfera del aire.

 Esto estratifica la ionosfera a diferentes alturas en diferentes subcapas.

 La densidad del plasma suele tener un valor entre :

 * **D =** $10^{9}$ $el/m^{3}$ de 50 a 70 km

 * **E =** máximo relativo de 70 a 100 km


 * **F =** máximo absoluto de 1000 km 

 $F_1$ y $F_2$ aparecen en el día 

 $F$ se une en la noche 

 ### __*Fenómeno ionosférico*__

 Cuando las ondas de radios pasan a través o penetran la ionósfera , ellos se afectan por diversos fenómenos 

 * Rotación de Faraday
 * Retardo de propagación
 * Retardo de grupo
 * Refracción  
 * Reflexión 
 * Disperción
 * Absorción
 * Centelleo

 Los primeros cuatro elementos dependen del estado del plasma de la ionosfera.

 **Tec:**  
   El número total de electrones en un cilindro con una sección transversal de un metro cuadrado en dirección al cenit solar. Medido en términos de $el/m^{2}$ se utiliza como un parámetro esencial para evaluar la calidad de la ionosfera.

   El calor nominal para diferentes estudios de la capa ionósfera está en el rango de :

   $$ 10^{16} - 10^{18} el/m^{2}$$

   La mayoría de los fenómenos en la atmósfera tienen propiedades estadísticas y dependen de diferentes factores como:

   * Latitud y longitud geográfica y ubicación geomagnética
   * Movimiento orbital de la Tierra o efectos estacionales
   * Movimiento de rotación de la Tierra o efectos diurnos
   * Actividades solares, especialmente el número de manchas solares.
   * Tormentas magnéticas
   * Efectos del campo geomagnético

  Teniendo en cuenta los factores anteriores y su relación estadística entre sí, las telecomunicaciones ionosféricas tienen una amplia gama de cambios que se deben tener en cuenta para garantizar comunicaciones confiables y eficientes.

  **Ejemplo 1.5**

 1.  Determinar el valor aproximado de la densidad del plasma a una altitud de 400 km sobre el nivel del suelo.

  *Leyendo el gráfico...*

  $$h=400 \Rightarrow 1.1*10^{11} \leq P_D \leq 1.1*10^{11} el/m^{3} $$

 2)  Si las alturas de las capas D, E y F son 70, 100 y 300 km, respectivamente, encuentre el valor de TEC para cada una de estas capas.

 *El espesor de cada capa es ...*

 $$W_D= 20 km $$
 $$ W_E = 40 km $$ 
 $$W_F= 190 km $$

Según la figura la densidad promedio es :

$$P_{D/D}\approx 1*10^{8} N/m^{3}$$
$$P_{D/E}\approx 1*10^{10} N/m^{3}$$
$$P_{D/F}\approx 1*10^{11} N/m^{3}$$

*Por lo tanto...*

$$TEC/D= 20*10^{3}*1*10^{8} = 2 * 10^{12} el/m^{2}  $$
$$TEC/E = 40*10^{3}*1*10^{10} = 4 * 10^{14} el/m^{2} $$
$$TEC/E = 190*10^{3}*1*10^{11} = 5.7 * 10^{16} el/m^{2} $$

3. Encuentre el valor efectivo de TEC para una transmisión satelital usando ondas de radio con ángulo de elevación igual a 40º

*Si se ignora el número de electrones en el espacio por encima de los 300 km, entonces el valor de TEC para la radiación vertical se calcula asi :*

$$TEC= TEC/D + TEC/E + TEC/F \approx 5.75 * 10^{16}el/m^{2}$$

Cómo el camino de radiación está inclinado, el valor efectivo de **TEC** es:

$$(TEC)_e=(TEC)*SEC 45º= 8.1*10^{16}el/m^{2}$$

## **Fórmulas ITU-R**

Considerando que la propagación por el espacio libre es una referencia fundamental para la ingenieria de radioenlaces.

La asamblea de **ITU-R** recomienda en la *Rec.525* que se utilicen los siguientes métodos para el cálculo de la atenuación en el espacio libre.

### __*Enlaces punto a área*__

Si hay un transmisor que da servicio a varios receptores distribuidos aleatoriamente (radiodifusión, servicio móvil), la intensidad de campo se calcula en un punto ubicado a cierta distancia apropiada del transmisor mediante la expresión : 

$$ e= \frac{\sqrt{30p}}{d} $$

*Dónde..*

**$e:$** Intensidad del campo eléctrico R.M.S

**$P:$** Potencia Isotrópica Radiada Equivalente *(PIRE)* del transmisor en la dirección del punto en cuestión

**$d:$** Distancia del transmisor al punto en cuestión (m)

*Esta ecuación se reemplaza por:* 

$$e_m[V/m]=173 \frac{\sqrt{p[kW]}}{d[km]} $$

Para antenas que funcionan en condiciones de espacio libre, la fuerza cimomotriz  puede obtenerse multiplicando **e** y **d**

Su dimensión es de voltios, y para aplicar las fórmulas anteriores se tendrán en cuenta los siguientes puntos.

Si la onda está polarizada elípticamente y no es lineal, y si las componentes del campo eléctrico a lo largo de dos ejes ortogonales se expresan mediante $e_x$ y $e_y$.El término de la izquierda puede ser reemplazado por:

$$\sqrt{e_x^{2} + e_x^{2}}$$

O puede simplificarse solo si se conoce la razón axial.

El término de la izquierda puede ser reemplazado por $e\sqrt{2}$ en el caso de poralización circular.  *Ver la recomendación **PN-368***

### __*Enlaces punto a punto*__

Con un enlace punto a punto , es preferible calcular la atenuación de espacio libre entre antenas isotrópicas.


$$ L_{bf} = 20log(\frac{4 \pi}{\lambda}) $$

**$L_{bf}:$** Pérdidas por espacio libre básicas

**$d:$** Distancia

**$\lambda: $** Longitud de onda

También se puede escribir en términos de la frecuencia:

$$ L_{bf} = 32.4 + 20log f + 20 log d $$

*Donde...*

$f:$ Frecuencia (MHz)

$d:$ Distancia (km)

### __*Enlaces de radio*__

Los sistemas de radar representan un caso especial porque la señal está sujeta a una pérdida mientras se propaga tanto desde el transmisor al objetivo como desde el objetivo al receptor.

Para los radares que utilizan una antena común tanto para el transmisor como para el receptor, la pérdida de transmisión básica en el espacio libre de radar, $L_{br}$ , se puede escribir de la siguiente manera:

$$L_{br} [dB]= 103.4 + 20log (f) + 40log (d) - 10log(\sigma)$$

*Donde...*

**$\sigma:$** Sección transversal del radar

**$d:$** Distancia del radar al objetivo

**$f:$** Frecuencia del sistema

La sección transversal del objetivo de radar de un objeto es la relación entre la potencia dispersa isotrópicamente equivalente total y la densidad de potencia incidente.
 
 ### __*Densidad de flujode potencia*__

 Existen también relaciónentre características de una onda plana en un punto 

 $$ S = \frac{e^{2}}{120\pi}=\frac{4\pi p_r}{\lambda^{2}}$$

 **$S:$** Densidad de potencia
 
 **$e:$** Intensidad de campo RMS
 
 **$P_r$** Potencia disponible de una antena isotrópica localizada en este punto

 **$\lambda:$** Longitud de onda 

 ### __*Relaciones de conversión*__

 Sobre la base de la propagación por espacio libre , se pueden utilizar las siguientes fórmulas de conversión.

 La amplitud de campo para  para una potencia transmitida isotrópicamente transmitida.

 $$E= P_t - 20log d + 74.8 $$
Intensidad de campo para una potencia transmitida isotrópicamente dada

$$P_r = E - 20log f - 162.2$$

Potencia recibida isotrópicamente para una intensidad de campo dada.

$$L_{br} = P_t -E + 20log (f) 167.2 $$

Densidad de flujo de potencia para una intensidad de campo determinada

$$S = E -145.8$$

**$P_t:$** Potencia transmitida isotrópicamente 

**$P_r:$** Potencia recibida isotrópicamente

**$E:$** Campo eléctrico

**$f:$** Frecuencia 

**$d:$** Distancia (km)

**$L_{bf}:$** Pérdida por espacio libre básicas

**$S:$** Densidad de flujo de potencia


## **Potencia radiada equivalente**
### __*ERP y EIRP*__

**ERP** incluye todos los factoresdeganancias y pérdidas en el lado del transmisor y normalmente se expresa en 
$dB_m$ o $dB_w$.

$$ERP=\frac{G_t*P_t}{L_t}$$

**$L_t:$** Pérdidas 
$$ERP[dB_m]=P_t[dB_m] + G_t[dB_d]-L_t[dB]$$
$$EIRP[dB_m]=P_t[dB_m] + G_t[dB_i]-L_t[dB]$$
$$EIRP[dB_w]=P_t[dB_w] + G_t[dB_d]-L_t[dB]$$

### __*Intensidad de campo eléctrico*__

La intensidad de campo eléctrico se puede expresar en funcion de **EIRP** , para hallar esta relación tenemos :

$$S=R_e(\overline{E} X \overline{H})=\frac{|E^{2}_d|}{\eta_0}$$

La densidad de antena a una distancia dada *d* es:

$$S=\frac{P_t*G_t}{L_t*4\pi d^{2}}= \frac {EIRP}{L_t*4\pi d^{2}}$$


*Si* $n_0=120 \pi$

$$\frac{|E_d|^{2}}{\eta_0}=\frac{P_t*G_t}{L_t*4\pi d^{2}}= \frac {EIRP}{4\pi d^{2}}$$
$$\Rightarrow |E_d| = \frac{\sqrt{30EIRP}}{d}$$

**Ejemplo:**

Una onda es radiada por un transmisor de **10 W** conectado a una antena de $5dB_i$.

1. Halle el **PIRE** si las pérdidas en alimentación son $2 dB$

$$EIRP[dB_w]=P_t[dB_w] + G_t[dB_i]-L_t[dB]= 13dB_w$$
$$\Rightarrow EIRP = Antilog(1.3)= 20 W$$

2. Halle $|E_d|$ y $S$ a 48 km del $T_x$
$$|E_d|= \frac{\sqrt{20*30}}{8000}=3.06*10^{-3}V/m= 3.06mV/m$$
$$W= \frac{1}{2\eta_0}|E_d|^{2}\Rightarrow S= 12.4nW/m^{2}$$

## **Pérdidas de transmisión**
### __*Pérdidas de enlaces de radio*__

La propagación de ondas de radio entre un transmisor y un  receptor , además de las pérdidas por espacio libre sufren también las siguientes pérdidas:
* Alimentadores de RF
* Antenas
* Mecanismos de prioagación
* Despolarización

La recomendación **P.134** ha definido los conceptos a pérdidas en los enlaces de radio.


  ![Pérdidas de transmisión](perdidas.png)

### __*Pérdidas de transmisión básicas*__

**$L_m:$** Pérdidas del medio

$$L_b =FSL * L_m $$
$$L_b[bB]= FSL [dB]+L_m[dB]$$

Entre las pérdidas de medio se encuentran:

* Pérdida por absorción atmosférica debida a gases, vapores y aerosoles.
* Pérdida a reflexión
* Dispersión de ondas de radio debido a irregularidades en el índice de refracción atmosférica o por hidrometeoros.
* Pérdida por difracción debido a obstrucciones.
* Clima : nubes y niebla
* Pérdida de acoplamiento de antena a media
* Pérdida de acoplamiento de polarización
* Efectos adversos multitrayecto.

### __*Péridas totales y pérdidas del sistema*__

**$Ls:$** Pérdidas del sistema

$$L_b[dB]= 10 log(\frac{P_t}{P_a})$$

*Donde...*

**$P_t:$** Potencia del transmisor entregada a la entrada de la antena **TX**

**$P_a$** Nivel de señal recibida (RSL) a la salida de la antena **RX**

$$L_b[dB]=L[dB]+L_{tc}[dB]+L_{rc}[d]=P_{t}[dB_m]-P_{ax}[dB_m] $$

Pérdida básica de transmisión

$$L_b[dB]= 20 log(\frac{4\pi d}{\lambda})$$

### __*Pèrdida básica de transmisión de un enlace radioeléctrico*__

$$L_b= L_{bf}+L_m$$

**$L_m:$** Pérdidas en el espacio libre

**$L_m$** incluye pérdidas por:

* Absorción
* Difracción en el caso de ondas de superficio
* Dispersión o reflexión efectiva, propagación ionosférica
* Acoplamiento de polarización
* Acoplamiento abertura- medio
* Dispersión del haz
* Ocupación del suelo.
* Entrada en edificios

### __*Pérdida de transmisión de una enlace radioeléctrico*__

Es las relación entre la potencia radiada por la antena de transmisión y la potencia que estaría disponible en una entrada de antena receptora.

$$ L=L_b-G_t-G_r$$

### __*Pérdida del sistema*__

Es la relación entre la potencia de radiofrecuencia entregada a los terminales de la antena transmisora y la potencia de la señal de radiofrecuencia resultante disponible en los terminales de la antena receptora.

$$L_s = L + L_{tc}+L_{rc}$$

**$L_{tc}:$** Pérdidas en el circuito de la antena transmisora

**$L_{rc}:$** Pérdidas en el circuito de la antena receptora.

$$L_{tc}= 10log(r'/r)$$

**$r':$** Componente resistivo de la impedancia de la antena

**$r:$** Resistencia de la radiación.

$$L_s= 10log(P+P_a)$$

## **Radioenlaces satelitales**

El primer satélite fue lanzado por la *URSS* en una órbita al rededor de la tierra.

Usando la tecnología espacial en telecomunicaciones creo una nueva rama de radioenlaces denominada "comunicaiones satelitales".

El objetivo de las comunicaiones satelitales es suministrar unos servicios de radio de buena calidad con una gran cobertura para una gran capacidad de tráfico.

En las comunicaciones satelitales laondas de radio estás sujetas a un número de fenómenos de propagación en las diferentes capas de la atmósfera.

Las comuniaciones satelitales son un tipo de radioenlaces con línea de vista y poseen una naturaleza diferente a su medio de propagación.

Las redes de comunicaciones satelitales , emplean una órbita terrestre en los planos:

* Ecuatorial
* Polos 
* Inclinados 

Las órbitas incluyen 

* Baja  **LEO**
* Medio  **MEO**
* Geoestacional **GEO**

La órbita *GEO* es de alta interés.Esta es una órbita única circular localizada en el plano ecuatorial en la cual el satélite y la tierra sincrónicamente, resultando en que la ubicación del satélite es justo en la tierra.


 ![Radioenlaces satelitales](satelite.png)

### __*Concepto básico*__

En sus inicios se consideraron los satélites como reflectores pasivos para lograr comunicaciones universales incrementando la distancia de los saltos.

Se probaron como reflectores 

*  La luna
* Balones reflectivos

Este es un enlace de radar :

$$P_r = \frac{P_t*G_t*G_r*\sigma}{(4\pi )^{2}*d^{2}_t*d^{2}_r}$$

$P_t,P_r:$ Potencia **TX** y potencia**TX**

$G_t,P_r:$  Ganancia antena **RX** y **TX**

$d_r,d_t$ Distancia de las estaciones terrestres al satélite

$\sigma:$ Factor de ganancia satelital

*Si $d_r \approx d_t \Rightarrow$*

$$P_r=K*\frac{\sigma}{d^{4}}*P_t$$

El factor de ganancia/pérdida es función de :

* Forma
* Material
* Tamaño
* Frecuencia de las ondas de radio 

La ecuación muestra que la potencia es inversamente proporcional a la potencia de la distancia 

Finalmente basados en los siguientes hechos:

* Se necesitan altas potencias de transmisión
* Receptores muy sensibles 
* Antenas con altas ganancias 
* Movimientos de reflectores en el espacio.

Para los satélites repetidores  activos, podemos usar la siguiente expresión.

$$P_r= \frac{P_t*G_t*G_r*g_s*A_s}{(4\pi)^{2}*d_t^{2}*d_r^{2}}$$

$g_s:$ Coeficiente de amplificación del transpondeo

$A_s$ Área efectiva de la antena satelital 

*Asumiendo que $g_s$ esproporcional a $4\pi d_r^{2}\Rightarrow$*

$$P_r=K'*\frac{A_s}{d^{2}}*P_t$$


La potencia recibida es inversamente proporcional a la segunda potencia de la distancia.

**Aplicaciones:**

* Son muy variadas en órbitas ecuatoriales *(LEO,MEO,GEO)*
* Orbitas inclinadas 
* Orbitas polares   

*En aplicaciones tenemos...*

* Redes internacionales para manipular tráfico de :

  * Audio
  * Video 
  * Data
* Cobertura global para ayudas a la navegación
* Redes públicas de radiodifusión de audio y vídeo
* Redes de comunicaciones móviles
* Redes de :
  * Teledetección
  * Meteorología 
  * Telemedida
* Redes satelitales dedicadas:
  * Nacionales
  * Regionales 
  * Miltipropósitos 

### __*Características de las comunicaciones satelitales*__

* Amplia cobertura sin restricciones geográficas o políticas.

* Flexibilidad y capacidad de suministrar diversos servicios.

* Gran ancho de banda utilizando varios servicios
* Evolución de diferentes tecnologías de acceso y uso óptimo de anchos de banda

* Independencia relativa con respecto a la distancia para los usuarios en la región de cobertura del satélite.

* Solución para enlaces entre usuarios separados por distancias muy grandes

* Alta confiabilidad y buena calidad de la comunicación

Por estas razones los satélites de comunicaciones son la mejor alternativa para suministrar servicios en muchos campos de telecomunicaciones.

### __*Enlaces satelitales*__

Los enlaces satelitales se pueden dividir en 2 grupos:
* Enlace satelital terrestre
* Enlace entre satélites **(ISL)**

![Ruta de referencia hipotética para enlace de radio satelital](enlacetierra.png)

Cada enlace bidireccional consta de un enlace s
de subida y otro de bajada.

Los **ISL** se pueden usar para una comunicación directa entre satélites.

En el pasado los enlaces entre satélites se realizaban a través de estaciones terrestres debido a:
* La movilidad del satélite 
* Gran distancia entre ellos 
* Limitacio nes de potencia eléctrica
* Limitaciones en el paso del satélite

Pero hoy en día en el uso de satélites **LEO** para el cubrimiento continuo **ISL** necesario.

Esto es posible debido a las mejores telecomunicaiones.
* Tecnología de facturación a componentes RF

Principales servicios de comunicaciones satélitales 

* Difusión 
* Exploración terrestre 
* Radio determinación 
* Metereología
* Servicios fijos 
* Servicios móviles
* Radio navegación 
* Servicio entre satélites

#### **Servicios de Telecomunicaciones**

Numerosas bandas y sub bandas se han asignado a :

* Servicios fijos 
* Servicios marítimos , aeronáuticos 
* Servicios militares 
* Servicios públicos de difusión 
* Servicio VSAT
* Servicios intersatelitales
* Servicios espaciales de telecomunicación 
  * Ayudas de navegación
  * Sensado remoto 
  * Posicionamiento
####  **Bandas de frecuencia satelitales**

Se han asiganado partes de las bandas 

* VHF
* UHF
* SHF
* EHF

para suministro de servicios de telecomunicaciones satelitales.

*Aspectos:*

* Técnicos 
* Operacionales

de cada sub banda se deberias observar por los diseñadores y autoridades competentes.

Entre las limitaciones de cada sub banda , hay también :

*  Ancho de banda total
* Frecuencia central
* Número de canales RF
* Espacio de canal 
* Banda de guarda
* Polarización

Se deben tener en cuenta los siguientes aspectos para el diseño de enlaces de radio satelitale:

* Tipo de tráfico 
* Capacidad de tráfico 
* Propagación de ondas de radio y sus fenómenos:
  * Atenuación atmosférica
  * Composición de las capas atmosféricas
  * Polarización de las ondas
* Tipos de satélite y circuitos que se usen incluido la integración a servicios y determinacion de transponderes requeridos

* Tipos de servicios como :
    * Telefonía
    * Datos
    * Video
    * Multimedia

Algunas de las bandas para los servicios satelitales son :

* **UHF:** Meteorología , servicios espaciales y militares 

* **Banda L:** 1.5 - 1.6 GHz comunicaciones de unidades móviles marítimas

* **Banda C:** 4 - 6 GHz Enlaces terrestres

* **Banda Ku:** 12 - 14 GHz 
    * Intersatelital
    * Estaciones terrestres 
    * Servicios VSAT

* **Banda Ka:** 20 - 30 GHz 
  * Exploración de la Tierra.
  * Intersatelital : Fijos y móvoles 
## Geometría de las órbitas
### __*Tipos de órbitas*__

Una órbita es el camino en el que viaja el satéite al rededor de la tierra en condiciones estables.

La ruta se puede ajustar ocacionalmente por faroles de baja energía emanados por un dispositivo propulsor.

* Órbita ecuatorial: En plano coaincide con el ecuador de la tierra.
* Órbita polar:La órbita está en un plano que contieneel eje polar de la tierra (la línea que pasa por los puntos de referencia de los polos norte y sur)
.
* Órbita inclinada: No es ni ecuatorial ni polar.

![Principales órbitas de los satélites](orbitasatelital.png)

El ángulo de inclinación del plano orbital en relación con
el plano del ecuador se denota por **i** y en esta condición :

$i=0º\Rightarrow Ecuatorial$

$i=90º\Rightarrow Polar$

$0<i<90º\Rightarrow Inclinada$

Otra clasificacion y altitudes de los satélites:

* Satélites **GEO:** 
  
  En la órbita geo-síncrona está definido como un satélite àra el cual el período de una redducción del satélite es igual al periodo de una rotación de la Tierra.

  La **GEO** es una órbita circular en el plano ecuatorial a una altura de 36000 Km de la superficie. 
  
  Esta órbita es única y un recurso natrual de las comunicaciones satelitales.

  El uso de esta órbita necesita coordinarse internacionalmente y los permisos los suministran las autoridades pertienentes.

* Satélites **HEO:**
  
  Es un satélite de órbita altamente inclinada que se define como una órbita elíptica con un perigeo de 500 km o más y un apogeo de 50000 km o menos de altura sobre la tierra con una inclinación mayor a 40º respecto al plano ecuatorial.

* Satélites **LEO:**
  
  Es una con una órbita circular elíptica a una altura de 700 - 3000 km.
  
* Satélites **MEO:**

  Es una órbita circular o elíptica enttre 8000 km  y 20000 km sobre la superficie terrestre

### __*Principios básicos de movimientos de satélites*__

Para los satélites en el plano orbital , se debe tener en cuenta los siguientes principios:

1. El centro de la tierra está ubicado en el plano orbital del satélite, de otra manera el satelite no se estabilizará en  este plano orbital
2. En el caso ideal , el movimiento del satélite es a lo largo de una trayectoria elṕtica con una excentricidad de $ e (0\leq e \leq1)$ que en caso extremos será una trayectoria circular $(e=1)$ o una línea recta $(e=0)$.
3. El centro de la tierra está ubicada en uno de los puntos locales de la órbita elíptica.
4. En la órbita satelital la fuerza resultante ejercida debe ser igual a cero.Esta fuerza consisten principalmente el peso del satélite y la fuerza centrípe  ta.
5. Las reglas de Kepler gobiernan el movimiento de los satélites y basados en estas reglas podemos concluir que:

$$T= 2\pi \sqrt{\frac{a^3}{\mu}}$$

$T:$ Periodo de rotación al rededor de la tierra en segundos

$a:$ La mitad del eje mayor de la trayectoria elíptica en metros

$\mu:$ Constante de Kepler y equivalente al producto de la masa y la fuerza de gravedad constante de la Tierra.

$$\mu=3.99*10^4 m^3/s²$$

La siguiente ecuación determina la velocidad del satélite en cualquier instante.

$$V_e=\sqrt{\mu (\frac{2}{r}-\frac{1}{a})}$$

$V_e:$ Velocidad del satélite en m/s

$r:$ Distancia del satélite al centro de la tierra en m

La siguiente gráfica muestra la variación de $T$ y $V_e$ en términos de la altitud del satélite.

![Variación del período y la velocidad del satélite vs la altura](variacion.png)
  
### __*Parámetros orbitales*__

Para definir especificaciones exactas de los parámetros orbitales se deben considerar:

* La forma elíptica de la trayectoria al rededor del planeta
* Ajustar el centro de la tierra a uno de los puntos focales  de la elipse.

En base a la geometría de sólidos , es escensial desarrollar los siguientes casos:

1. Plano orbital , incluido el plano que contiene la órbita del satélite.
2. Las principales características de la elípse en el plano.
3. Las especificaciones de la posición elíptica y el ángulo del eje mayor de la elipse relativo a la línea base.

Para determinar cada uno de los casos anteriores, se deben indicar dos factores entre los siguientes seis factores:

1. Ángulo de inclinación entre el plano orbital y el plano ecuatorial que se denota $i$.
2. Ángulo entre la dirección ascendente (interconectando la línea del centro de la tierra en el punto $\Omicron$ y el satélite atravesando el plano ecuatorial en una dirección específica) denotado como $\Omega$.
3. Excentricidad de la órbita elíptica denotada como $e$ y que tiene un valor entre 0 y 1.
4. La mitad del eje mayor de la órbita elíptica denotada como $a$
5. Argumento del punto meridiano indicado por $\omega$.
6. Anomalía media indicada por $M$

![Geometría de las órbitas de los satélites](geometria.png)

### __*Huella satelital*__


La cobertura geográfica de un transpondedor de satélite se define como una región de la Tierra donde es posible establecer un enlace directo entre las estaciones terrestres y el satélite.
La cobertura geográfica de los satélites estacionarios es casi fija, mientras que para un satélite en movimiento es una función del tiempo.

Estas se pueden clasificar en: 

* Cubrimiento global
* Cubrimiento regional
* Cubrimiento nacional
* Cubrimiento local

La huella es una de las cuestiones más significativas en el diseño de los satélites

Para la planificación de los diferentes segmentos de la red de satélites ya sean estaciones espaciales o terrestres, se requieren los siguientes datos básicos:

* Número de satélites 
* Órbita de satélites
* Arreglos de los canales de **RF** en los transpondedores satelitales.
* Cálculo de propagación.

El concepto geométrico de la cobertura  de un satélite y el radio en la tierra se da en :

![Geometría de la cobertura satelital](radio.png)

Para el cálculo del radio del área cubierta de un satélite tenemos que :

$$\frac{R_e}{R_e+h}=cos\frac{(\beta+E_1)}{cos E_1}$$

$E_1:$ Ángulo de elevación de la antena terrestre

$\beta:$  Ángulo de vista del satélite

$h:$ Altura de satélite desde el suelo 

$R_e:$ Radio de la tierra

Para una condición extrema donde $E_1=0$ esto es , $SB$ y una línea tangente a la tierra , entonces tenemos la mayor cobertura , es denominada área de cobertura ideal. Y obtenemos la siguiente relación.

$$\beta_0= cos^{-1}\frac{R_e}{R_e + h}$$

Entonces el área cubierta es :

$$S_M=2\pi R_e^2(1-cos \beta_0)$$
**Ejemplo:**

En un sistema GPS , los satélites están localizados a una distancia de 25000 km del centro de la tierra. En caso del ángulo de elevación es 20º y se considera la desviación de la trayectoria causada por la tropósfera y la ionósfera , entonces tenemos :

1. El área de cobertura de cada satélite.

$$E_l=20º, R_e=6370 km $$
$$R_e+ h=25000km$$

$$(\beta_0+20º=cos^{-1}[\frac{6370}{25000} *cos 20º])$$

$$\beta_0=56º$$

$$S_M=2\pi R_e^2(1-cos \beta_0)=1.1238*10^8(km)^2$$

2. El ancho del lóbulo de la antena satelital

$$\angle S =180-\beta-E_l-90º$$
$$\angle S = 14º$$
$$BW=2*\angle S=28º$$
### __*Cubrimiento global*__

En los servicios de telecomunicaciones internacionales, se requiere proporcionar una red satelital para cubrir posiblemente toda la superficie terrestre o al menos una gran parte de ella. Este tipo de servicio se denomina “cobertura global” e incluye normalmente muchos países repartidos en diferentes continentes y océanos.

En la actualidad, existen varias redes de satélite que operan a nivel mundial, entre las cuales las siguientes son las más populares:

* International telecommunications satellite **(INTELSAT)** network
* International maritime satellite **(INMARSAT)** network
* GPS

*Cubrimiento por satélites **GEO***

La cobertura global de los satélites GEO está disponible a través de tres satélites posicionados en órbita geoestacionaria.

Este satélite deben estas separados 120º a una altitud de 36000 km o 41750 km desde el centro del planeta.

![Cobertura global satelital](cobertura.png)

*Red **INETELSAT***

![Cobertura mundial INTELSAT-5](INTEL.png)

* Región del Océano Atlántico **(AOR)**
* Región del Océano Índico **(IOR)**
* Región del Océano Pacífico **(POR)**

El área de cobertura de cada satélite **GEO** con una antena de 17,3º de ancho de haz equivale a 216 millones de km².

Considerando toda la superficie de la Tierra alrededor de 510 millones de km²

Las latitudes más allá de los 75º en el hemisferio norte y sur  no están cubiertas por ángulos de elevación de antena superiores a 5º, por lo que sus enlaces no son fiables.


*Cubrimiento global  por satélites **LEO***

Debido a que los  satélites **LEO** se están en movimiento con respecto a la Tierra, es posible ajustar sus movimientos orbitales de forma que proporcionen una cobertura global.

Si el número de  satélites es limitado, entonces en esta situación la cobertura permanente no estará disponible en ciertos momentos.

Normalmente en estas redes la opereción está limitada a aplicaciones particulares como:

* Exploraciones terrestres
* Topografía
* Telemedida
* Sensado remoto

El número de satélites se incrementarán de acuerdo a las siguientes cuestiones:

* Altitud del satélite
* Ancho del lóbulo de la antena
* Estructura de la estación terrena
* Capacidad de tráfico

**Ejemplo:**

Si, en el ejemplo anterior, empleamos seis órbitas circulares, cada una con cuatro satélites igualmente espaciados, encuentre:

1. Núrmero de satélites:

$$N_s=6*4=24$$

2. Tipo de cobertura de red y porcentaje de superposición

$$S_t=24*1.1238*10^8=2.696*10^9 km²$$
$$S_E=4\pi R_e²=5.0965*10⁸ km²$$
$$S_t >S_E \Rightarrow Cubrimiento-global$$
*Porcentaje de superposición es:*

$$C  = \frac{S_t}{S_E} *100 \approx 500 $$

3. Número de satélites que tengan línea de vista con cada estacíon terrestre
  Observe que la superposición , en cada instante  de tiempo, 5 satélites en diferentes posiciones se pueden observar por una estación terrestre.

    Hay que tener en cuenta que hay 4 parámetros necesarios:
    * Longitud
    * Altura
    * Ancho
    * Tiempo
  
    Cada terminal GPS  para recopilar información adecuados de al menos cuatro satélites en cada medición.

    ### __*Tiempo de cubrimiento*__

Se considera en el caso de satélites no estacionarios , incluye **LEO,MEO,HEO** , en órbita ecuatorial , polar e inclinada.

En las redes satelitales **LEO** situadas en el plano ecuatorial debido a que su órbita es circular , el área de cobertura es en su mayoria fija y uniforme pero su localización cambia continuamente.

En las  órbitas elípticas debido a las variaciones de altitudes del satélite con respecto a  la Tierra , cambia no solo la ubicación de cobertura sino también el área de cobertura.

En satélites estacionarios su tiempo de cobertura se supone constante, pero en la práctica está influenciada por efectos varables del tiempo como:

* Derivas del satélite en el espacio 
* Variaciones atmosféricas
* Efectos en el cielo para ángulos de elevación menor a 10º para la antena en la estación terrestre.

Para tener un cubrimiento continuo en un área de la tierra con satélites **MEO** y **LEO** se debe usar un racimo de satélites.

El número de satélites se puede calcular con base en el tamaño del área de cobertura.

* Coordenadas geográficas
* Patrones de elevación y radiación del satélite
* Plano orbital

Cuando el área de cobertura es grande y toma dimensiones regionales o globales , se vuelve dificil sumistrar el cubrimiento permanente y aumenta el número de satélites.

En estas circustancias se considera lo siguiente:

* Usar antenas pequeñas y en algunas ocaciones omnidireccionales en las estaciones terrestres.

* Sistema de ajusto automático para antenas direccionales 
* Conexión entre satélites y manipulación del tráfico principal y control de data
* Sistema de control en la estación terrestre

### __*Cobertura de tráfico*__

Está influenciada principalmente por los siguientes factores:

* Número de usuarios en cada regíon 
* Versatilidad de los servicios 
* Tráfico promedio y pico para cada usuario
* Capacidad de tráfico en horas pico
* Grado de servicio requerido
### __*Cobertura de la huella*__

**G/T:** Es una medida de mérito de un sistema receptor para determinar la señal principal.

Este parámetro se define en escala logarítmica 

$$\frac{G}{T}=G(dB_i)- T_s(dB_k)$$

*Dónde...*

$G:$ Ganancia de antena receptora

$T_s:$ Temperatura de ruido del sistema receptor  

Para mostrar el cubrimiento del transporte a un satélite **GEO** utilizan las huella de transmisión/recepción.

Estos contornos contienen datos de **G/T** y **EIRP**:

![Huella de transmisión típica del transpondedor de satélite](EIRP.png)

![Huella de recepción típica del transpondedor de satélite](GT.png)




