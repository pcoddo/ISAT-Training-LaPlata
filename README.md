<!-- Header -->
![Header](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/header.png)

# **ISAT-Training-LaPlata**
<!-- Badges -->
[![Español](https://img.shields.io/badge/Traducir-Espa%C3%B1ol-orange)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.es.md)
[![Português](https://img.shields.io/badge/Traduzir-Portugu%C3%AAs-brightgreen)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.pt-br.md)

## About
Contains installation instructions, agenda, and training materials for the Interagency Water Working Group (ISAT) workshop conducted in Buenos Aires, Argentina, November 2022. Workshop organized in partnership with the Organization of American States (OAS) and the Comité Intergubernamental Coordinador de los Países de la Cuenca del Plata (CIC).

---
## Table of Contents
<div id="user-content-toc">
  <ul>
    <li><a href="#1-training-agenda">1. Training Agenda</a>
    <li><a href="#2-installation-instructions">2. Installation Instructions</a>
      <ul>
        <li><a href="#21-requirements">2.1. Requirements</a></li>
        <li><a href="#22-install-miniconda">2.2. Install Miniconda</a></li>
        <li><a href="#23-download-training-materials">2.3. Download training materials</a></li>
        <li><a href="#24-create-conda-environment">2.4. Create conda environment</a></li>
        <li><a href="#25-test-installation">2.5. Test installation</a></li>
      </ul>
    <li><a href="#3-acknowledgements">3. Acknowledgements</a>
    </li>
  </ul>
</div>

---
## 1. Training Agenda
<!--- ![Agenda](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/agenda_10.26.22.jpg) --->
<details open>
  <summary>Click to collapse agenda</summary>
  
#### Day 1: Monday, November 14
<table style="text-align:left">
    <tr>
        <td colspan="4">Introductions</th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-10:30</td>
        <td>Opening Session</td>
        <td>Discussion</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>10:30-11:30</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>11:00-12:00</td>
        <td>Introduction to the ISAT Partnership</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:00-13:00</td>
        <td colspan="3">Lunch</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_1"><b>Session 1: Introduction to Hydrological Remote Sensing</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>13:00-14:00</td>
        <td>Introduction to Remote Sensing Principles</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>14:00-15:00</td>
        <td>Overview of Land Cover Remote Sensing</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>15:00-15:30</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>15:30-16:30</td>
        <td>Accessing and Examining Land Cover</td>
        <td>Exercise</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>16:30-17:00</td>
        <td>End-of-day Discussion</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>17:00-18:00</td>
        <td>Opening Day Welcome Reception</td>
        <td>Event</td>
        <td>CIC</td>
    </tr>
</table>

#### Day 2: Tuesday, November 15</td>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2A"><b>Session 2A: Precipitation</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Welcome/Agenda</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>GPM Mission Overview</td>
        <td>Presentation</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>Precipitation Analysis and Discussion</td>
        <td>Excercise</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introduction to MODIS</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>12:00-13:00</td>
        <td>Access &amp; Analysis of MODIS NDVI</td>
        <td>Excercise</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>13:00-14:00</td>
        <td colspan="3">Lunch</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2B"><b>Session 2B: Soil Moisture &amp; Evapotranspiration</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>14:00-14:30</td>
        <td>Introduction to SMAP</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>14:30-15:30</td>
        <td>SMAP Data Access &amp; Analysis</td>
        <td>Exercise</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>15:30-16:00</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>16:00-16:30</td>
        <td>Introduction to Evapotranspiration Access</td>
        <td>Presentation</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>16:30-17:00</td>
        <td>Access Landsat-Based ET</td>
        <td>Exercise</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>17:00-17:30</td>
        <td>Questions/End-of-day Discussion</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
</table>

#### Day 3: Wednesday, November 16
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3A"><b>Session 3A: Water Height / Aerial Extent</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Welcome/Agenda</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>Introduction to MOGWAI</td>
        <td>Presentation</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>MOGWAI Example</td>
        <td>Exercise</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td>Break</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introduction to AWS</td>
        <td>Presentation</td>
        <td>AWS</td>
    </tr>
    <tr>
        <td>12:00-12:30</td>
        <td>Q&amp;A</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:30-13:30</td>
        <td colspan="3">Lunch</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3B"><b>Session 3B: Water Quality</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>13:30-14:00</td>
        <td>Introduction to Water Quality Remote Sensing</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>14:00-15:00</td>
        <td>Water Quality Remote Sensing Applications</td>
        <td>Exercise</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>15:00-15:30</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>15:30-16:00</td>
        <td>Freshwater Health Index</td>
        <td>Presentation</td>
        <td>CI</td>
    </tr>
    <tr>
        <td>16:00-16:30</td>
        <td>Q&amp;A</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>16:30-17:00</td>
        <td>Questions/End-of-day Discussion</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
</table>

#### Day 4: Thursday, November 17
<table style="text-align:left">
    <tr>
        <td colspan="4">Field Visit</th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-13:00</td>
        <td>INA's Laboratory and Field Visit</td>
        <td>Field Visit</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>13:00-14:00</td>
        <td colspan="3">Lunch</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_4"><b>Session 4: Introduction to Land Surface Modeling</b></a></th>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>14:00-14:45</td>
        <td>Overview of Global Land Data Assimilation (GLDAS)</td>
        <td>Presentation</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>14:45-15:30</td>
        <td>Summary of Surface Water Budget Components</td>
        <td>Presentation</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>15:30-4:00</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>4:00-5:00</td>
        <td>Access &amp; Analysis of GLDAS Runoff </td>
        <td>Exercise</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>5:00-5:30</td>
        <td>Questions/End-of-day Discussion</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
</table>

#### Day 5: Friday, November 18
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5A"><b>Session 5A: Introduction to Modeling Frameworks</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Welcome/Agenda</td>
        <td>Discussion</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:30</td>
        <td>Introduction to SWAT-Online &amp; NASAaccess</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>10:30-11:00</td>
        <td colspan="3">Break</td>
    </tr>
    <tr>
        <td>11:00-12:00</td>
        <td>Introduction to Hydrologic Modeling System (HEC-HMS)</td>
        <td>Presentation</td>
        <td>USACE</td>
    </tr>
    <tr>
        <td>12:00-13:00</td>
        <td>Introduciton to NASA's Land Information System (LIS)</td>
        <td>Presentation</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>13:00-14:00</td>
        <td colspan="3">Lunch</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5B"><b>Session 5B: Training Debrief &amp; Future Directions</b></a></th>
    </tr>
    <tr>
        <th>Time</th>
        <th>Title and Topics&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Type&emsp;&emsp;&emsp;&emsp;</td>
        <th>Presenter&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>14:00-16:00</td>
        <td>Training Debrief</td>
        <td>Discussion</td>
        <td>ISAT/CIC</td>
    </tr>
    <tr>
        <td>16:00</td>
        <td>Close Out</td>
        <td>Discussion</td>
        <td>ISAT/CIC</td>
    </tr>
</table>
</details>

## 2. Installation Instructions
### 2.1. Requirements
Operating system: 
* Windows 8 or newer, 64-bit 
* macOS 10.13+
    * If you are unsure which chip you have (Intel vs. M1), check [here](https://support.apple.com/en-us/HT211814). 
* Minimum 5 GB disk space to download and install

### 2.2. Install Miniconda
*Conda* is an open-source package and environment management system that runs on Windows, macOS, and Linux. Conda quickly installs, runs, and updates packages and their dependencies. It also easily creates, saves, loads, and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language. This training will use a simplified installation called *Miniconda*. 

1. Navigate to the [installation page](https://docs.conda.io/en/latest/miniconda.html) and download the installer for your operating system.

[Windows Installers](https://docs.conda.io/en/latest/miniconda.html#windows-installers)
![windows-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/windows-installer.png)

[Mac OS Installers](https://docs.conda.io/en/latest/miniconda.html#macos-installers). For Mac OS users, choose the **pkg** installer option.
![mac-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-installer.png)

2. Go to your *Downloads* folder and double-click the installer to launch.
3. Read the licensing terms and click **I Agree**.
4. Select Installation Type. It is recommended that you install for **Just Me** as this does not require administrator rights.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-type.PNG" width="400">
</p>

5. Select a destination folder to install Anaconda and click *Next*.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-location.PNG" width="400">
</p>

For Mac OS users, choose the "Standard Install" option:
<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-standard.png" width="400">
</p>

6. Choose whether to add Anaconda to your PATH environment variable or register Anaconda as your default Python. We **don’t recommend** adding Anaconda to your PATH environment variable, since this can interfere with other software.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-path.PNG" width="400">
</p>

7. Click **Install**. If you want to watch the packages Miniconda is installing, click Show Details.

### 2.3. Download training materials
1. Open terminal window ("Anaconda Prompt" on Windows, "Terminal" on Mac)
![terminal](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/terminal.png)

2. Install *git* through terminal. This allows your computer to download the training materials hosted on Github:
```shell
conda config --add channels conda-forge
conda install -c conda-forge git
```
When asked to Proceed, type **"y"**


3. Navigate to desired working directory (e.g. "C:\Users\Name\Documents\Training_materials"):
```shell
cd Documents/
cd Training_materials/
```

4. Clone repository to working directory:
```shell
git clone https://github.com/pcoddo/ISAT-Training-LaPlata.git
```

### 2.4. Create conda environment
Create conda environment using provided `environment.yml` file:
```shell
conda env create -f environment.yml
```

This environment should install all necessary software and packages for the training. Depending on internet and processor speeds, **this may take several minutes.**

Activate new environment:
```shell
conda activate plata
```

The terminal should now display the activated environment:
![plata-activated](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/plata-activated.PNG)

### 2.5. Test installation


## 3. Acknowledgements
These materials draw on previous trainings developed by the NASA Advanced Remote Sensing Training [(ARSET)](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset) Program. Special thanks to [Dr. Amita Mehta](https://sciences.gsfc.nasa.gov/sed/bio/amita.v.mehta), [Dr. Erika Podest](https://science.jpl.nasa.gov/people/podest/), [Dr. Ana Prados](https://jcet.umbc.edu/jcet-faculty/person/ed05369/) and the rest of the ARSET team for providing those materials!


<p align="center">
  <a href="#ISAT-Training-LaPlata">(Back to top)</a>
</p>
