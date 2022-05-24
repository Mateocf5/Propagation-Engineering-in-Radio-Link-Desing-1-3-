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
