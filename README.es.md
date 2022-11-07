<!-- Header -->
![Header](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/header.png)

# **ISAT-Training-LaPlata**
<!-- Badges -->
[![English](https://img.shields.io/badge/Translate-English-blue)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.md)
[![Português](https://img.shields.io/badge/Traduzir-Portugu%C3%AAs-brightgreen)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.pt-br.md)

## Resumen
Contains installation instructions, agenda, and training materials for the Interagency Water Working Group (ISAT) workshop conducted in Buenos Aires, Argentina, November 2022. Workshop organized in partnership with the Organization of American States (OAS) and the Comité Intergubernamental Coordinador de los Países de la Cuenca del Plata (CIC).

---
## Tabla de contenido
<div id="user-content-toc">
  <ul>
    <li><a href="#1-agenda-de-capacitación">1. Agenda de Capacitación</a>
    <li><a href="#2-instrucciones-de-instalación">2. Instrucciones de instalación</a>
      <ul>
        <li><a href="#21-requisitos">2.1. Requisitos</a></li>
        <li><a href="#22-instalar-miniconda">2.2. Instalar Miniconda</a></li>
        <li><a href="#23-descargar-materiales-de-capacitación">2.3. Descargar materiales de capacitación</a></li>
        <li><a href="#24-crear-ambiente-conda">2.4. Crear ambiente conda</a></li>
        <li><a href="#25-prueba-de-Instalación">2.5. Prueba de Instalación</a></li>
        <li><a href="#26-actualización-del-software-Conda">2.6. Actualización del software Conda</a></li>
      </ul>
    <li><a href="#3-recursos-útiles">3. Recursos Útiles
    <li><a href="#4-agradecimientos">4. Agradecimientos</a>
    </li>
  </ul>
</div>

---
## 1. Agenda de Capacitación
<details open>
  <summary>Click para ocultar agenda</summary>
  
#### Día 1: Lunes, 14 de Noviembre
<table style="text-align:left">
    <tr>
        <td colspan="4">Introducciones</th>
    </tr>
    <tr>
        <th>Tiempo</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-10:30</td>
        <td>Sesión de apertura</td>
        <td>Discusión</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>10:30-11:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>11:00-12:00</td>
        <td>Introducción a la Asociación ISAT</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:00-1:00</td>
        <td colspan="3">Almuerzo</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_1"><b>Sesión 1: Introducción a la Teledetección Hidrológica</b></a></th>
    </tr>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td>Introducción a los principios de la teledetección</td>
        <td>Presentación</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>2:00-3:00</td>
        <td>Descripción general de la detección remota de la cobertura terrestre</td>
        <td>Presentación</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>3:00-3:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>3:30-4:30</td>
        <td>Acceso y examen de la cobertura terrestre</td>
        <td>Ejercicio</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Discusión al final del día</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>5:30-6:15</td>
        <td>Recepción de bienvenida del día de apertura</td>
        <td>Evento</td>
        <td>CIC</td>
    </tr>
</table>

#### Día 2: Martes, 15 de Noviembre</td>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2A"><b>Sesión 2A: Precipitación</b></a></th>
    </tr>
    <tr>
        <th>Tiempo</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Bienvenida/Agenda</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>Resumen de la misión GPM</td>
        <td>Presentación</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>Análisis y discusión de precipitaciones</td>
        <td>Ejercicio</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introducción a MODIS</td>
        <td>Presentación</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>12:00-1:00</td>
        <td>Acceso &amp; Análisis de MODIS NDVI</td>
        <td>Ejercicio</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td colspan="3">Almuerzo</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2B"><b>Sesión 2B: Humedad del suelo &amp; Evapotranspiración</b></a></th>
    </tr>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>2:00-2:30</td>
        <td>Introducción a SMAP</td>
        <td>Presentación</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>2:30-3:30</td>
        <td>Acceso a datos SMAP &amp; Análisis</td>
        <td>Ejercicio</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>3:30-4:00</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>4:00-4:30</td>
        <td>Introducción al acceso a la evapotranspiración</td>
        <td>Presentación</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Acceda a ET basado en Landsat</td>
        <td>Ejercicio</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>5:00-5:30</td>
        <td>Preguntas/Discusión al final del día</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
</table>

#### Día 3: Miércoles, 16 de Noviembre
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3A"><b>Sesión 3A: Altura del agua / Extensión aérea</b></a></th>
    </tr>
    <tr>
        <th>Tiempo</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Bienvenida/Agenda</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>Introducción a MOGWAI</td>
        <td>Presentación</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>Ejemplo MOGWAI</td>
        <td>Ejercicio</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td>Pausa</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introducción a AWS</td>
        <td>Presentación</td>
        <td>AWS</td>
    </tr>
    <tr>
        <td>12:00-12:30</td>
        <td>Preguntas y respuestas</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:30-1:30</td>
        <td colspan="3">Almuerzo</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3B"><b>Sesión 3B: Calidad del agua</b></a></th>
    </tr>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>1:30-2:00</td>
        <td>Introducción a la percepción remota de la calidad del agua</td>
        <td>Presentación</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>2:00-3:00</td>
        <td>Aplicaciones de teledetección de la calidad del agua</td>
        <td>Ejercicio</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>3:00-3:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>3:30-4:00</td>
        <td>Índice de Salud del Agua Dulce</td>
        <td>Presentación</td>
        <td>CI</td>
    </tr>
    <tr>
        <td>4:00-4:30</td>
        <td>Preguntas y respuestas</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Preguntas/Discusión al final del día</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
</table>

#### Día 4: Jueves, 17 de Noviembre
<table style="text-align:left">
    <tr>
        <td colspan="4">Visita de campo</th>
    </tr>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>08:00-12:00</td>
        <td>Visita al Laboratorio y Campo del INA</td>
        <td>Visita de campo</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td colspan="3">Almuerzo</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_4"><b>Sesión 4: Introducción al modelado de la superficie terrestre</b></a></th>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>2:00-2:45</td>
        <td>Resumen de la asimilación global de datos terrestres (GLDAS)</td>
        <td>Presentación</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>2:45-3:30</td>
        <td>Resumen de los componentes del presupuesto de aguas superficiales</td>
        <td>Presentación</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>3:30-4:00</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>4:00-5:00</td>
        <td>Acceso &amp; Análisis de Escorrentía GLDAS </td>
        <td>Ejercicio</td>
        <td>USO</td>
    </tr>
    <tr>
        <td>5:00-5:30</td>
        <td>Preguntas/Discusión al final del día</td>
        <td>Discusión</td>
        <td>ISAT</td>
    </tr>
</table>

#### Día 5: Viernes, 18 de Noviembre
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5A"><b>Sesión 5A: Introducción a los marcos de modelado</ b></a></th>
    </tr>
    <tr>
        <th>Tiempo</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
         <td>09:00-10:30</td>
         <td>Sistema de Apoyo a la Decisión de La Plata (SSTD)</td>
         <td>Discusión</td>
         <td>Deltares</td>
     </tr>
     <tr>
         <td>10:30-11:00</td>
         <td colspan="3">Pausa</td>
     </tr>
     <tr>
         <td>11:00-12:00</td>
         <td>Introducción a SWAT-Online &amp; Acceso NASA</td>
         <td>Presentación</td>
         <td>NASA</td>
     </tr>
     <tr>
         <td>12:00-1:00</td>
         <td>Introducción al Sistema de modelado hidrológico (HEC-HMS) y al Sistema de información terrestre (LIS)</td>
         <td>Presentación</td>
         <td>USACE/NASA</td>
     </tr>
     <tr>
         <td>1:00-2:00</td>
         <td colspan="3">Almuerzo</td>
     </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5B"><b>Sesión 5B: Informe de capacitación y amp; Direcciones futuras</b></a></th>
    </tr>
    <tr>
        <th>Tiempo&emsp;&emsp;</th>
        <th>Título y temas&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presentador&emsp;&emsp;</th>
    </tr>
    <tr>
         <td>2:00-3:00</td>
         <td>Estudio de caso de DSS: Lima, Perú</td>
         <td>Presentación</td>
         <td>RTI</td>
     </tr>
     <tr>
         <td>3:00-4:00</td>
         <td>Informe de capacitación (Reflexiones sobre la semana, Instrucciones para futuras capacitaciones)</td>
         <td>Discusión</td>
         <td>ISAT/CIC</td>
     </tr>
     <tr>
         <td>4:00</td>
         <td>Cerrar</td>
         <td>Discusión</td>
         <td>ISAT/CIC</td>
     </tr>
</table>
</details>

## 2. Instrucciones de instalación
### 2.1. Requisitos
Sistema operativo: 
* Windows 8 o posterior, 64-bits 
* macOS 10.13+
    * Si no está seguro de qué chip tiene (Intel vs. M1), verifique [aquí](https://support.apple.com/en-us/HT211814).
* Espacio en disco mínimo de 5 GB para descargar e instalar

### 2.2. Instalar Miniconda
*Anaconda* es un sistema de administración de entornos y paquetes de código abierto que se ejecuta en Windows, macOS y Linux. Conda instala, ejecuta y actualiza rápidamente los paquetes y sus dependencias. También crea, guarda, carga y cambia fácilmente entre entornos en su computadora local. Fue creado para programas Python, pero puede empaquetar y distribuir software para cualquier lenguaje. Esta capacitación utilizará una instalación simplificada llamada *Miniconda*. 

1. Vaya a la  [página de instalación](https://docs.conda.io/en/latest/miniconda.html) y descargue el instalador para su sistema operativ.

[Instaladores de Windows](https://docs.conda.io/en/latest/miniconda.html#windows-installers)
![windows-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/windows-installer.png)

[Instaladores de Mac OS](https://docs.conda.io/en/latest/miniconda.html#macos-installers). Para usuarios de Mac OS, elija la opción de instalación **pkg**.
![mac-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-installer.png)

2. Vaya a la carpeta  *Descargas* y haga doble clic en el instalador para iniciar.
3. Lea los términos de licencia y haga clic en **Acepto**.
4. Seleccione Tipo de instalación. En Windows, se recomienda instalar para **Just Me**, ya que esto no requiere derechos de administrador. Para usuarios de Mac OS, elija la opción "Standard Install":

![install-type](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/install-type.PNG)

5. Para instalaciones de Windows, seleccione una carpeta de destino para instalar Miniconda y haga clic en *Siguiente*.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-location.PNG" width="400">
</p>

6. Elija si desea agregar Miniconda a su variable de entorno PATH o registrar Miniconda como su Python predeterminado. **No recomendamos** agregar Miniconda a su variable de entorno PATH, ya que esto puede interferir con otro software

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-path.PNG" width="400">
</p>

7. Haga clic en **Instalar**. Si desea ver los paquetes que Miniconda está instalando, haga clic en Mostrar detalles

### 2.3. Descargar materiales de capacitación
1. Abra la ventana del terminal ("Anaconda Prompt" en Windows, "Terminal" en Mac)

![terminal](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/terminal.png)

2. Instale *git* a través de la terminal. Esto permite que su computadora descargue los materiales de capacitación alojados en Github:
```shell
conda config --add channels conda-forge
conda install -c conda-forge git
```
Cuando se le pida que continúe, escriba "**y**"


3. Navegue hasta el directorio de trabajo deseado (por ejemplo, "C:\Users\Name\Documents\Training_materials"):
```shell
cd Documents/
cd Training_materials/
```

4. Clonar repositorio al directorio de trabajo:
```shell
git clone https://github.com/pcoddo/ISAT-Training-LaPlata.git
```

### 2.4. Crear ambiente Conda
Cree un entorno conda utilizando el archivo `environment.yml` proporcionado:
```shell
conda env create -f environment.yml
```

Este entorno debe instalar todo el software y los paquetes necesarios para la capacitación. Dependiendo de las velocidades de Internet y del procesador, **esto puede tardar varios minutos**.

Activar nuevo entorno:

```shell
conda activate plata
```

El terminal ahora debería mostrar el entorno activado:

![plata-activated](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/plata-activated.PNG)

### 2.5. Prueba de instalación
Verifique si QGIS se instaló correctamente.
```shell
qgis
```

La aplicación debería abrirse en una nueva ventana. Una vez que lo haga, intente abrir el archivo de mapa `Cuenca-del-Plata_Map.qgz`:

![test-map](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/test-map.PNG)

### 2.6. Actualización del software Conda
Los presentadores pueden hacer actualizaciones a este repositorio a medida que avanza el taller. Para asegurarse de tener la última versión de los materiales, es posible que deba actualizar sus archivos locales con cualquier cambio reciente.

1. Primero, asegúrese de que el entorno "plata" esté activado:
```shell
conda activate plata
```

2. A continuación, navegue a la carpeta de capacitación (por ejemplo, "C:\Users\Name\Documents\Training_materials\ISAT-Training_LaPlata\") y descargue los archivos más recientes:
```shell
cd Documents/
cd Training_materials/
cd ISAT-Training_LaPlata/
```

3. Finalmente, descargue los archivos más recientes:
```shell
git pull
```

## 3. Recursos Útiles
### <u>Fuentes de datos directos</u>
* [**USGS Earth Explorer**](https://earthexplorer.usgs.gov)
	* [Landsat](https://landsat.gsfc.nasa.gov/)
    * [Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2)
    * [SRTM](https://www2.jpl.nasa.gov/srtm/)
* [**Copernicus Open Access Hub**](https://scihub.copernicus.eu/dhus/#/home)
  * Sentinel-1 - Synthetic Aperture Radar (SAR)
  * Sentinel-2
  * Sentinel-3
  * [Sentinel-5P](https://earth.esa.int/web/guest/missions/esa-eo-missions/sentinel-5p) 
* [**NASA EARTHDATA**](https://earthdata.nasa.gov/)
  * [Alaska Satellite Facility](https://asf.alaska.edu/), a source for current and historic RADAR data
* [**GEO on AWS**](https://registry.opendata.aws/?search=tags:gis,earth%20observation,events,mapping,meteorological,environmental,transportation)
     
### <u>Visores de datos e Imágenes</u>
* [**NASA Worldview**](https://worldview.earthdata.nasa.gov/)
	* Satellite data
* [**NOAA View**](https://www.nnvl.noaa.gov/view/globaldata.html)
	* Ocean, land and atmospheric data
* [**Resource Watch**](https://resourcewatch.org/data/explore)
	* Hundreds of data sets on the state of the planet’s resources and citizens
* [**Global Forest Watch**](https://www.globalforestwatch.org/map)
	* Data, technology and tools tobetter protect forests

### <u>Fuentes de imágenes Comercial</u>
* [**Google Earth Engine**](https://developers.google.com/earth-engine/datasets/)
* [**Planet**](https://www.planet.com/)
  * High temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution
* [**Maxar**](https://www.maxar.com/)
* [**Iceye**](https://www.iceye.com/)
	* High spatial and temporal resolution synthetic-aperture radar data
* [**Airbus**](https://www.intelligence-airbusds.com/optical-and-radar-data/)
 	* High resolution RGB and synthetic-aperture radar imagery. 
* [**Blacksky**](https://www.blacksky.com/)
  * Plan for high temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution

<sup>Algunas de las fuentes anteriores fueron extraídas del repositorio [nicar20-imagery-sources](https://github.com/timwallace/nicar20-imagery-sources) por [Tim Wallace](https://github.com /timwallace)<sub>


## 4. Agradecimientos
Estos materiales se basan en capacitaciones previas desarrolladas por el Programa de Capacitación de Detección Remota Avanzada de la NASA [(ARSET)](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset). Un agradecimiento especial a [Dr. Amita Mehta](https://sciences.gsfc.nasa.gov/sed/bio/amita.v.mehta), [Dra. Erika Podest](https://science.jpl.nasa.gov/people/podest/), [Dra. Ana Prados](https://jcet.umbc.edu/jcet-faculty/person/ed05369/) y al resto del equipo de ARSET por proporcionar esos materiales! Gracias también a Aarti Arora por ayudar a diseñar la agenda de la reunión.


<p align="center">
  <a href="#ISAT-Training-LaPlata">(Back to top)</a>
</p>
