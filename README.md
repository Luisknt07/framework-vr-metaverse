# Unreal Experiment Framework-VR-Metaverse
El Framework es un conjunto de componentes que simplifican los experimentos para proyectos, para realidad virtual, escritorio y web, con diferentes modos de salida de datos. Este proyecto de desarrollo, trabaja con dos módulos enfocados en sistemas modulares y monitorización. Si desea descargar el paquete, puede probarlo en su versión limitada disponible de forma gratuita, si necesita la versión completa puede contactar para más información.

<p align="center">
  <a href="https://doi.org/10.3758/s13428-019-01242-0">
  <img src="https://user-images.githubusercontent.com/60415183/260886477-ac25d16e-7d83-4c1e-90a7-ff6d42ccb742.png">
  </a>
  

¡Lea el artículo de [acceso abierto](https://www.mdpi.com/2076-3417/12/12/6258) Smart Factory Using Virtual Reality and Online Multi-User: Towards a Metaverse for Experimental Frameworks! El documento ofrece una buena visión general de la motivación de este proyecto.

Si ha desarrollado un proyecto utilizando el Framework, ¡hágamelo saber!
</p>



**Contenido**
- [1- Repositorio de proyecto Digital Factory Metaverse](#1--Repositorio-de-proyecto-Digital-Factory-Metaverse)
   - [Disponibilidad del ejecutable del proyecto](#Disponibilidad-del-ejecutable-del-proyecto)
   - [Disponibilidad del código fuente y documentación](#Disponibilidad-del-código-fuente-y-documentación)
   - [Plugins Utilizados](#Plugins-Utilizados)
- [2- Cuestionario de pruebas de usabilidad](#2--Cuestionario-de-pruebas-de-usabilidad)
- [3- Aplicación de la metodología SLP para el proyecto Digital Factory Metaverse](#3--Aplicación-de-la-metodología-SLP-para-el-proyecto-Digital-Factory-Metaverse)
- [4- Documento de Diseño del Juego](#4--Documento-de-Diseño-del-Juego)
- [5- Bases de datos para monitorización](#5--Bases-de-datos-para-monitorización)
- [6- Guías de prácticas de laboratorio para el aplicativo de realidad virtual](#6--Guías-de-prácticas-de-laboratorio-para-el-aplicativo-de-realidad-virtual)

# 1- Repositorio de proyecto Digital Factory Metaverse

## Disponibilidad del ejecutable del proyecto
Se pone a disposición de los investigadores la versión beta del ejecutable del proyecto Digital Factory Metaverse, la cual pueden descargar desde la plataforma Virprot https://virprot.com/Proyecto/Ref=DIGITAL-FACTORY-METAVERSE opción descargas.
Se recomienda contar con los requisitos mínimos recomendados de los equipos de gafas de realidad virtual y cómputo para poder experimentar una buena experiencia de usuario.

## Disponibilidad del código fuente y documentación
Digital Factory Metaverse está disponible gratuitamente en una versión limitada para descargar a través del repositorio GitHub como un paquete de Unreal Engine https://github.com/mickluis/framework-vr-metaverse En cuanto a la documentación y soporte, están disponibles en el wiki de GitHub https://github.com/mickluis/framework-vr-metaverse/wiki y también en la plataforma de realidad virtual y metaversos Virprot/proyectos/DIGITAL-FACTORY-METAVERSE https://virprot.com/Proyecto/Ref=DIGITAL-FACTORY-METAVERSE.

Si desea la versión completa del proyecto puede contactarse con el autor para más información.

## Plugins Utilizados
Al proyecto se le ha agregado (plugins) para su funcionamiento, los cuales por derechos de autor se deben adquirir en la plataforma de Epic Games https://www.unrealengine.com/marketplace/en-US/store?sessionInvalidated=true.

Los Plugins utilizados para el proyecto son los siguientes:
```csharp
    - Plugins de comunicación multiusuario: EOS core, Vivox Core
    - Plugins de bases de datos: Json, Socket.io
    - Plugins de comunicación web: Web view y Web server  
```

# 2- Cuestionario de pruebas de usabilidad

Para las pruebas de usabilidad con los usuarios, se ha realizado un cuestionario con preguntas para las categorías de experiencia de usuario, preparación y control de dispositivos, multiusuario, efectos de inmersión, diseño modular y monitorización. A continuación, se proporciona el enlace del cuestionario: https://forms.gle/MJNCa1CjfceJACiD7.


# 3- Aplicación de la metodología SLP para el proyecto Digital Factory Metaverse

La metodología SLP utilizada para el proyecto permitió estructurar el contenido de estudio técnico para el diseño de distribución de la planta de producción con enfoque de Smart Factory. En el repositorio del proyecto se pueden encontrar los detalles de la metodología SLP, su contenido y los diseños de distribución de la planta: \url{https://github.com/mickluis/framework-vr-metaverse}. El propósito del repositorio es mejorar y actualizar información del proyecto para la comunidad interesada en el desarrollo del Framework.


A continuación se presenta los datos más importantes resumidos utilizando la metodología SLP para el proyecto Digital Factory Metaverse.

Desarrollo de las fases de la metodología:

# 4- Documento de Diseño del Juego
A continuación se ofrece el enlace al Documento de Diseño del Juego (GDD), que proporciona detalles específicos sobre el desarrollo del aplicativo de realidad virtual. Dado que el documento es extenso, se ha optado por compartirlo en el repositorio del proyecto en una versión pública a través del siguiente enlace: \url{https://github.com/mickluis/framework-vr-metaverse} opción documento de diseño del juego.

El contenido del GDD se muestra a continuación:

# 5- Bases de datos para monitorización
El repositorio de información y bases de datos para la monitorización se deja disponible con el propósito de mantener actualizada la información utilizada en el proyecto caso de estudio y para proporcionar recursos a la comunidad científica y a nuevos investigadores. Esto promueve la transparencia, el acceso abierto a los datos, la colaboración y el avance del conocimiento en el campo de la monitorización. 

En el siguiente enlace se muestra el repositorio que contiene las bases de datos para monitorización tenidas en cuenta para el desarrollo de este proyecto:

## Bases de Datos para la Monitorización en una Planta de Ensamble de Automóviles en Smart Factory

|Tipo de monitorización |Monitorización| Bases de datos|
|---|---|---|
| `Monitorización por Procesos` |Base de datos de seguimiento de procesos de ensamblaje |• [Registro de inicio y finalización de cada etapa del ensamblaje.](#) <br> • [Datos de producción por fase y tiempo de ciclo de ensamblaje.](#) <br> • [Identificación de operadores y maquinaria involucrada en cada proceso.](#) <br> • [Registros de calidad y control de defectos durante el ensamblaje.](#)|
|`Monitorización por Procesos` | Base de datos de rendimiento de procesos |• [Registro de eficiencia y productividad de cada línea de ensamblaje.](#) <br> • [Análisis de tiempos de inactividad y paradas no programadas.](#) <br> • [Indicadores clave de rendimiento (KPI) para evaluar el desempeño.](#) |
| `Monitorización por Maquinaria y Robots` | Base de datos de estado de la maquinaria y robots | • [Registro del estado operativo de cada máquina y robot en tiempo real.](#) <br> • [Datos de mantenimiento preventivo y correctivo.](#) <br> • [Información sobre averías y reparaciones.](#) |
| `Monitorización por Maquinaria y Robots`| Base de datos de utilización de maquinaria y robots | • [Registro de tiempo de uso de cada equipo.](#) <br> • [Cálculo de la utilización y eficiencia de las máquinas y robots.](#) |
| `Monitorización por Calidad de Producto`| Base de datos de control de calidad de ensamblaje | • [Registro de datos de inspección y pruebas de calidad en línea de producción.](#) <br> • [Trazabilidad de componentes y piezas utilizadas en cada vehículo.](#) <br> • [Información sobre desviaciones y acciones correctivas.](#) |
|`Monitorización por Calidad de Producto` | Base de datos de feedback de clientes | • [Registro de comentarios y sugerencias de los clientes sobre la calidad del automóvil.](#) <br> • [Evaluación de satisfacción del cliente y retroalimentación.](#) |
|`Monitorización por Recursos y Logística`| Base de datos de inventario y suministros | • [Registro de existencias de piezas, componentes y materiales.](#) <br> • [Gestión de pedidos y control de reposición de inventario.](#)|
|`Monitorización por Recursos y Logística` | Base de datos de recursos humanos | • [Registro de información del personal, habilidades y formación.](#) <br> • [Gestión de horarios y asignación de tareas en la línea de ensamblaje.](#) |

    

# 6- Guías de prácticas de laboratorio para el aplicativo de realidad virtual
Se desarrolló un conjunto de guías de laboratorio para el aplicativo de realidad virtual. Estas guías tienen como objetivo mejorar la experiencia de los usuarios al utilizar el aplicativo y permitirles realizar prácticas de manera estructurada.

Las guías abarcan temas de producción, logística, almacenamiento, diseño modular, monitorización y Smart Factory, proporcionando a los usuarios una comprensión completa de diversas áreas relevantes para la realidad virtual en entornos industriales.

En total, se han diseñado 10 guías de laboratorio, disponibles en la plataforma Virprot- https://virprot.com/Proyecto/Ref=DIGITAL-FACTORY-METAVERSE opción guías de laboratorio.
