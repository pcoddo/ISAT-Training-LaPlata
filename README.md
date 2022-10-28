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
    <li><a href="#3-usage">3. Usage</a>
    <li><a href="#4-acknowledgements">4. Acknowledgements</a>
    </li>
  </ul>
</div>

---
## 1. Training Agenda
![Agenda](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/agenda_10.26.22.jpg)

## 2. Installation Instructions
### 2.1. Requirements
Operating system: 
* Windows 8 or newer, 64-bit 
* macOS 10.13+
* Minimum 5 GB disk space to download and install

### 2.2. Install Miniconda
*Conda* is an open-source package and environment management system that runs on Windows, macOS, and Linux. Conda quickly installs, runs, and updates packages and their dependencies. It also easily creates, saves, loads, and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language. This training will use a simplified installation called *Miniconda*. 

1. Navigate to the [installation page](https://docs.conda.io/en/latest/miniconda.html) and download the installer for your operating system.

[Windows Installers](https://docs.conda.io/en/latest/miniconda.html#windows-installers)
![windows-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/windows-installer.png)

[Mac OS Installers](https://docs.conda.io/en/latest/miniconda.html#macos-installers)
![mac-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-installer.png)

2. Go to your *Downloads* folder and double-click the installer to launch.
3. Read the licensing terms and click **I Agree**.
4. Select Installation Type. It is recommended that you install for **Just Me** as this does not require administrator rights.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-type.PNG" width="400">
</p>

5. Select a destination folder to install Anaconda and click Next.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-location.PNG" width="400">
</p>

6. Choose whether to add Anaconda to your PATH environment variable or register Anaconda as your default Python. We **don’t recommend** adding Anaconda to your PATH environment variable, since this can interfere with other software.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-path.PNG" width="400">
</p>

7. Click **Install**. If you want to watch the packages Miniconda is installing, click Show Details.

### 2.3. Download training materials
1. Open terminal window ("Anaconda Prompt" on Windows, "Terminal" on Mac)
![terminal](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/terminal.png)

2. Install git through terminal. This allows your computer to download the training materials hosted on Github:
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

The terminal should now the activated environment:

### 2.5. Test installation


## 3. Usage
TBD

## 4. Acknowledgements
These materials draw on previous trainings developed by the NASA Advanced Remote Sensing Training [(ARSET)](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset) Program. Special thanks to [Dr. Amita Mehta](https://sciences.gsfc.nasa.gov/sed/bio/amita.v.mehta), [Dr. Erika Podest](https://science.jpl.nasa.gov/people/podest/), [Dr. Ana Prados](https://jcet.umbc.edu/jcet-faculty/person/ed05369/) and the rest of the ARSET team for providing those materials!


<p align="center">
  <a href="#ISAT-Training-LaPlata">(Back to top)</a>
</p>
