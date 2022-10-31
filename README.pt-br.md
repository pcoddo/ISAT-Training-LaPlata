<!-- Header -->
![Header](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/header.png)

# **ISAT-Training-LaPlata**
<!-- Badges -->
[![Español](https://img.shields.io/badge/Traducir-Espa%C3%B1ol-orange)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.es.md)
[![English](https://img.shields.io/badge/Translate-English-blue)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.md)

## Resumo
Contém instruções de instalação, agenda e materiais de treinamento para o workshop do Interagency Water Working Group (ISAT) realizado em Buenos Aires, Argentina, em novembro de 2022. Workshop organizado em parceria com a Organização dos Estados Americanos (OEA) e o Comitê Intergubernamental Coordinador de los Países de la Cuenca del Plata (CIC).

---
## O Índice Analítico
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

## 2. Instruções de Instalação
### 2.1. Requisitos
Sistema operacional: 
* Windows 8 ou mais recente, 64-bits 
* macOS 10.13+
* Mínimo de 5 GB de espaço em disco para baixar e instalar

### 2.2. Instalar Miniconda
*Conda* é um pacote de código aberto e sistema de gerenciamento de ambiente que é executado no Windows, macOS e Linux. O Conda instala, executa e atualiza rapidamente os pacotes e suas dependências. Ele também cria, salva, carrega e alterna facilmente entre ambientes em seu computador local. Ele foi criado para programas Python, mas pode empacotar e distribuir software para qualquer linguagem. Este treinamento usará uma instalação simplificada chamada *Miniconda*.

1. Navegue até a [página de instalação](https://docs.conda.io/en/latest/miniconda.html) e baixe o instalador para seu sistema operacional.

[Instaladores do Windows](https://docs.conda.io/en/latest/miniconda.html#windows-installers)
![windows-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/windows-installer.png)

[Instaladores do Mac OS](https://docs.conda.io/en/latest/miniconda.html#macos-installers)
![mac-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-installer.png)

2. Vá para a pasta *Downloads* e clique duas vezes no instalador para iniciar.
3. Leia os termos de licenciamento e clique em **I Agree**.
4. Selecione o Tipo de Instalação. É recomendável que você instale o **Just Me**, pois isso não requer direitos de administrador.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-type.PNG" width="400">
</p>

5. Selecione uma pasta de destino para instalar o Anaconda e clique em *Avançar*.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-location.PNG" width="400">
</p>

6. Escolha se deseja adicionar o Anaconda à sua variável de ambiente PATH ou registrar o Anaconda como seu Python padrão. Nós **não recomendamos** adicionar o Anaconda à sua variável de ambiente PATH, pois isso pode interferir em outros softwares.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-path.PNG" width="400">
</p>

7. Clique em **Instalar**. Se você quiser ver os pacotes que o Miniconda está instalando, clique em Mostrar detalhes.

### 2.3. Baixe os materiais de treinamento
1. Abra a janela do terminal ("Prompt do Anaconda" no Windows, "Terminal" no Mac)
![terminal](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/terminal.png)

2. Instale o *git* pelo terminal. Isso permite que seu computador baixe os materiais de treinamento hospedados no Github:
```shell
conda config --add channels conda-forge
conda install -c conda-forge git
```
Quando solicitado a continuar, digite **"y"**


3. Navegue até o diretório de trabalho desejado (por exemplo, "C:\Users\Name\Documents\Training_materials"):
```shell
cd Documents/
cd Training_materials/
```

4. Clonar o repositório para o diretório de trabalho:
```shell
git clone https://github.com/pcoddo/ISAT-Training-LaPlata.git
```

### 2.4. Criar ambiente conda
Crie um ambiente conda usando o arquivo `environment.yml` fornecido:
```shell
conda env create -f environment.yml
```

Este ambiente deve instalar todos os softwares e pacotes necessários para o treinamento. Dependendo da velocidade da Internet e do processador, **isso pode levar vários minutos.**

Ativar novo ambiente:
```shell
conda activate plata
```

O terminal agora deve exibir o ambiente ativado:
<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/plata-activated.PNG" width="400">
</p>

### 2.5. Testar a instalação


## 3. Usage
TBD

## 4. Reconhecimentos
Esses materiais baseiam-se em treinamentos anteriores desenvolvidos pelo Programa NASA Advanced Remote Sensing Training [(ARSET)](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset). Agradecimentos especiais ao [Dr. Amita Mehta](https://sciences.gsfc.nasa.gov/sed/bio/amita.v.mehta), [Dr. Erika Podest](https://science.jpl.nasa.gov/people/podest/), [Dr. Ana Prados](https://jcet.umbc.edu/jcet-faculty/person/ed05369/) e o restante da equipe ARSET por fornecer esses materiais!


<p align="center">
  <a href="#ISAT-Training-LaPlata">(Back to top)</a>
</p>
