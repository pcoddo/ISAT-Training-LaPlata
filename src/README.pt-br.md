<!-- Header -->
![Header](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/header.png)

# **Dados e ciência para a tomada de decisões em águas transfronteiriças na América Latina e no Caribe (ALC)**
<!-- Badges -->
[![Español](https://img.shields.io/badge/Traducir-Espa%C3%B1ol-orange)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/main/src/README.es.md)
[![English](https://img.shields.io/badge/Translate-English-blue)](https://github.com/pcoddo/ISAT-Training-LaPlata/blob/master/README.md)

## Resumo
Este repositório contém a agenda, instruções de instalação e materiais de treinamento para o workshop do Grupo de Trabalho Interagências sobre Água (ISAT), *Capacitação em ferramentas e metodologias cientificamente sólidas para GIRH na Bacia do Prata: Acesso a dados.* Este workshop foi realizado em Buenos Aires em novembro de 2022, e foi organizado em parceria com a Organização dos Estados Americanos (OEA) e o Comité Intergubernamental Coordinador de los Países de la Cuenca del Plata (CIC).

---
## O Índice Analítico
<div id="user-content-toc">
  <ul>
    <li><a href="#1-agenda-de-treinamento">1. Agenda de Treinamento</a>
    <li><a href="#2-instruções-de-Instalação">2. Instruções de Instalação</a>
      <ul>
        <li><a href="#21-requisitos">2.1. Requisitos</a></li>
        <li><a href="#22-instalar-miniconda">2.2. Instalar Miniconda</a></li>
        <li><a href="#23-baixe-os-materiais-de-treinamento">2.3. Baixe os materiais de treinamento</a></li>
        <li><a href="#24-criar-ambiente-conda">2.4. Criar ambiente conda</a></li>
        <li><a href="#25-testar-a-instalação">2.5. Testar a instalação</a></li>
        <li><a href="#26-atualizando-o-software-conda">2.6. Atualizando o software Conda
      </ul>
    <li><a href="#3-recursos-úteis">3. Recursos Úteis
    <li><a href="#4-reconhecimentos">4. Reconhecimentos</a>
    </li>
  </ul>
</div>

---
## 1. Agenda de Treinamento
<details open>
  <summary>Clique para ocultar a agenda</summary>
  
#### Dia 1: Segunda-feira, 14 de Novembro
<table style="text-align:left">
    <tr>
        <td colspan="4">Apresentações</th>
    </tr>
    <tr>
        <th>Hora</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-10:30</td>
        <td>Sessão de abertura</td>
        <td>Discussão</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>10:30-11:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>11:00-12:00</td>
        <td>Introdução à parceria ISAT</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:00-1:00</td>
        <td colspan="3">Almoço</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_1"><b>Sessão 1: Introdução ao Sensoriamento Remoto Hidrológico</b></a></th>
    </tr>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td>Fundamentos de Sensoriamento Remoto</td>
        <td>Apresentação</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>2:00-3:00</td>
        <td>Visão geral do sensoriamento remoto de cobertura do solo</td>
        <td>Apresentação</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>3:00-3:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>3:30-4:30</td>
        <td>Acessando e Examinando a Cobertura da Terra</td>
        <td>Exercício</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Discussão de fim de dia</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>5:30-6:15</td>
        <td>Recepção de boas-vindas no dia de abertura</td>
        <td>Evento</td>
        <td>CIC</td>
    </tr>
</table>

#### Dia 2: Terça-feira, 15 de Novembro</td>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2A"><b>Sessão 2A: precipitação</b></a></th>
    </tr>
    <tr>
        <th>Hora</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Bem-vindo/Agenda</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>Visão geral da missão do GPM</td>
        <td>Apresentação</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>Análise e discussão de precipitação</td>
        <td>Exercício</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introdução ao MODIS</td>
        <td>Apresentação</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>12:00-1:00</td>
        <td>Acessar &amp; Análise do MODIS NDVI</td>
        <td>Exercício</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td colspan="3">Almoço</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_2B"><b>Sessão 2B: Umidade do Solo &amp; Evapotranspiração</b></a></th>
    </tr>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>2:00-2:30</td>
        <td>Introdução ao SMAP</td>
        <td>Apresentação</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>2:30-3:30</td>
        <td>Acesso a dados SMAP &amp; Análise</td>
        <td>Exercício</td>
        <td>NASA</td>
    </tr>
    <tr>
        <td>3:30-4:00</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>4:00-4:30</td>
        <td>Introdução ao acesso à evapotranspiração</td>
        <td>Apresentação</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Acessar ET baseado em Landsat</td>
        <td>Exercício</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>5:00-5:30</td>
        <td>Perguntas/Discussão de fim de dia</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
</table>

#### Dia 3: Quarta-feira, 16 de Novembro
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3A"><b>Sessão 3A: Altura da água / Extensão aérea</b></a></th>
    </tr>
    <tr>
        <th>Hora</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>09:00-09:15</td>
        <td>Bem-vindo/Agenda</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>09:15-10:00</td>
        <td>Introdução ao MOGWAI</td>
        <td>Apresentação</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>10:00-11:00</td>
        <td>Exemplo MOGWAI</td>
        <td>Exercício</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>11:00-11:30</td>
        <td>Pausa</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>11:30-12:00</td>
        <td>Introdução à AWS</td>
        <td>Apresentação</td>
        <td>AWS</td>
    </tr>
    <tr>
        <td>12:00-12:30</td>
        <td>Perguntas e respostas</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>12:30-1:30</td>
        <td colspan="3">Almoço</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_3B"><b>Sessão 3B: Qualidade da Água</b> </a></th>
    </tr>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
         <td>1:30-2:00</td>
         <td>Índice de Saúde de Água Doce (FHI)</td>
         <td>Apresentação</td>
         <td>CI</td>
     </tr>
     <tr>
         <td>2:00-2:30</td>
         <td>Introdução ao Sensoriamento Remoto da Qualidade da Água</td>
         <td>Apresentação</td>
         <td>NASA</td>
     </tr>
     <tr>
         <td>2:30-3:00</td>
         <td colspan="3">Pausa</td>
     </tr>
     <tr>
         <td>3:00-4:00</td>
         <td>Aplicativos de sensoriamento remoto da qualidade da água</td>
         <td>Exercício</td>
         <td>NASA</td>
    </tr>
    <tr>
        <td>4:00-4:30</td>
        <td>Perguntas e respostas</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
    <tr>
        <td>4:30-5:00</td>
        <td>Perguntas/Discussão de fim de dia</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
</table>

#### Dia 4: Quinta-feira, 17 de Novembro
<table style="text-align:left">
    <tr>
        <td colspan="4">Visita de campo</th>
    </tr>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>08:00-12:00</td>
        <td>Laboratório e visita de campo da INA</td>
        <td>Visita de campo</td>
        <td>CIC</td>
    </tr>
    <tr>
        <td>1:00-2:00</td>
        <td colspan="3">Almoço</td>
    </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_4"><b>Sessão 4: Introdução à modelagem de superfície terrestre</b></a></th>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
        <td>2:00-2:45</td>
        <td>Visão geral da assimilação global de dados terrestres (GLDAS)</td>
        <td>Apresentação</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>2:45-3:30</td>
        <td>Resumo dos componentes do orçamento de águas superficiais</td>
        <td>Apresentação</td>
        <td>UVA</td>
    </tr>
    <tr>
        <td>3:30-4:00</td>
        <td colspan="3">Pausa</td>
    </tr>
    <tr>
        <td>4:00-5:00</td>
        <td>Acessar &amp; Análise do escoamento GLDAS </td>
        <td>Exercício</td>
        <td>USAR</td>
    </tr>
    <tr>
        <td>5:00-5:30</td>
        <td>Perguntas/Discussão de fim de dia</td>
        <td>Discussão</td>
        <td>ISAT</td>
    </tr>
</table>

#### Dia 5: Sexta-feira, 18 de Novembro
<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5A"><b>Sessão 5A: Introdução às estruturas de modelagem</b></a></th>
    </tr>
    <tr>
        <th>Hora</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
         <td>09:00-10:30</td>
         <td>Sistema de Apoio à Decisão La Plata (SSTD)</td>
         <td>Discussão</td>
         <td>Deltares</td>
     </tr>
     <tr>
         <td>10:30-11:00</td>
         <td colspan="3">Pausa</td>
     </tr>
     <tr>
         <td>11:00-12:00</td>
         <td>Introdução ao SWAT-Online &amp; Acesso NASA</td>
         <td>Apresentação</td>
         <td>NASA</td>
     </tr>
     <tr>
         <td>12:00-1:00</td>
         <td>Introdução ao Sistema de Modelagem Hidrológica (HEC-HMS) e ao Sistema de Informação de Terras (LIS)</td>
         <td>Apresentação</td>
         <td>USACE/NASA</td>
     </tr>
     <tr>
         <td>1:00-2:00</td>
         <td colspan="3">Almoço</td>
     </tr>
</table>

<table style="text-align:left">
    <tr>
        <td colspan="4"><a href="https://github.com/pcoddo/ISAT-Training-LaPlata/tree/main/Sessions/Session_5B"><b>Sessão 5B: Debrief &amp; Direções futuras</b></a></th>
    </tr>
    <tr>
        <th>Hora&emsp;&emsp;&emsp;</th>
        <th>Título e tópicos&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;</th>
        <th>Tipo&emsp;&emsp;&emsp;&emsp;</td>
        <th>Apresentador&emsp;&emsp;</th>
    </tr>
    <tr>
         <td>2:00-3:00</td>
         <td>Estudo de caso DSS: Lima, Peru</td>
         <td>Apresentação</td>
         <td>RTI</td>
     </tr>
     <tr>
         <td>3:00-4:00</td>
         <td>Debrief de treinamento (reflexões sobre a semana, instruções para treinamentos futuros)</td>
         <td>Discussão</td>
         <td>ISAT/CIC</td>
     </tr>
     <tr>
         <td>4:00</td>
         <td>Fechar</td>
         <td>Discussão</td>
         <td>ISAT/CIC</td>
     </tr>
</table>
</details>

## 2. Instruções de Instalação
### 2.1. Requisitos
Sistema operacional: 
* Windows 8 ou mais recente, 64-bits 
* macOS 10.13+
    * Se você não tiver certeza de qual chip você possui (Intel vs. M1), verifique [aqui](https://support.apple.com/en-us/HT211814).
* Mínimo de 5 GB de espaço em disco para baixar e instalar

### 2.2. Instalar Miniconda
*Anaconda* é um pacote de código aberto e sistema de gerenciamento de ambiente que é executado no Windows, macOS e Linux. O Conda instala, executa e atualiza rapidamente os pacotes e suas dependências. Ele também cria, salva, carrega e alterna facilmente entre ambientes em seu computador local. Ele foi criado para programas Python, mas pode empacotar e distribuir software para qualquer linguagem. Este treinamento usará uma instalação simplificada chamada *Miniconda*.

1. Navegue até a [página de instalação](https://docs.conda.io/en/latest/miniconda.html) e baixe o instalador para seu sistema operacional.

[Instaladores do Windows](https://docs.conda.io/en/latest/miniconda.html#windows-installers)
![windows-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/windows-installer.png)

[Instaladores do Mac OS](https://docs.conda.io/en/latest/miniconda.html#macos-installers). Para usuários do Mac OS, escolha a opção do instalador **pkg**.
![mac-installer](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/mac-installer.png)

2. Vá para a pasta *Downloads* e clique duas vezes no instalador para iniciar.
3. Leia os termos de licenciamento e clique em **I Agree**.
4. Selecione o Tipo de Instalação. No Windows, é recomendável que você instale o **Just Me**, pois isso não requer direitos de administrador. Para usuários do Mac OS, escolha a opção "Standard Install":

![install-type](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/install-type.PNG)

5. Para instalações do Windows, selecione uma pasta de destino para instalar o Miniconda e clique em *Avançar*.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-location.PNG" width="400">
</p>

6. Escolha se deseja adicionar o Miniconda à sua variável de ambiente PATH ou registrar o Miniconda como seu Python padrão. Nós **não recomendamos** adicionar o Miniconda à sua variável de ambiente PATH, pois isso pode interferir em outros softwares.

<p align="center">
  <img src="https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/win-install-path.PNG" width="400">
</p>

7. Clique em **Instalar**. Se você quiser ver os pacotes que o Miniconda está instalando, clique em Mostrar detalhes.

### 2.3. Baixe os materiais de treinamento
1. Abra a janela do terminal ("Anaconda Prompt" no Windows, "Terminal" no Mac)

![terminal](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/terminal.png)

2. Instale o *git* pelo terminal. Isso permite que seu computador baixe os materiais de treinamento hospedados no Github:
```shell
conda config --add channels conda-forge
conda install -c conda-forge git
```
Quando solicitado a continuar, digite **"y"**


3. Navegue até o diretório de trabalho desejado (por exemplo, "C:\Users\Name\Documents"):
```shell
cd Documents
```

4. Clonar o repositório para o diretório de trabalho:
```shell
git clone https://github.com/pcoddo/ISAT-Training-LaPlata.git
```

### 2.4. Criar ambiente Conda
Crie um ambiente conda usando o arquivo `environment.yml` fornecido:
```shell
cd ISAT-Training-LaPlata

conda env create -f environment.yml
```

Este ambiente deve instalar todos os softwares e pacotes necessários para o treinamento. Dependendo da velocidade da Internet e do processador, **isso pode levar vários minutos.**

Ativar novo ambiente:
```shell
conda activate plata
```

O terminal agora deve exibir o ambiente ativado:

![plata-activated](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/plata-activated.PNG)

### 2.5. Testar a instalação
Verifique se o QGIS foi instalado com sucesso:
```shell
qgis
```

O aplicativo deve abrir em uma nova janela. Feito isso, tente abrir o arquivo de mapa `Cuenca-del-Plata_Map.qgz`:

![test-map](https://raw.githubusercontent.com/pcoddo/ISAT-Training-LaPlata/main/img/install/test-map.PNG)

### 2.6. Atualizando o software Conda
Os apresentadores podem fazer atualizações neste repositório à medida que o workshop avança. Para garantir que você tenha a versão mais recente dos materiais, talvez seja necessário atualizar seus arquivos locais com as alterações recentes.

1. Primeiro, certifique-se de que o ambiente "plata" esteja ativado:
```shell
conda activate plata
```

2. Em seguida, navegue até a pasta de treinamento (por exemplo, "C:\Users\Name\Documents\ISAT-Training-LaPlata") e baixe os arquivos mais recentes:
```shell
cd Documents
cd ISAT-Training-LaPlata
```

3. Por fim, baixe os arquivos mais recentes:
```shell
git pull
```

## 3. Recursos Úteis
### <u>Fontes de dados diretas</u>
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
     
### <u>Visualizadores de dados e Imagens</u>
* [**NASA Worldview**](https://worldview.earthdata.nasa.gov/)
	* Satellite data
* [**NOAA View**](https://www.nnvl.noaa.gov/view/globaldata.html)
	* Ocean, land and atmospheric data
* [**Resource Watch**](https://resourcewatch.org/data/explore)
	* Hundreds of data sets on the state of the planet’s resources and citizens
* [**Global Forest Watch**](https://www.globalforestwatch.org/map)
	* Data, technology and tools tobetter protect forests

### <u>Fontes de imagens Comercial</u>
* [**Google Earth Engine**](https://developers.google.com/earth-engine/datasets/)
  * Cloud-based implementation with dozens of available datasets
* [**Planet**](https://www.planet.com/)
  * High temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution
* [**Maxar**](https://www.maxar.com/)
	* High resolution RGB and synthetic-aperture radar data.
* [**Iceye**](https://www.iceye.com/)
	* High spatial and temporal resolution synthetic-aperture radar data
* [**Airbus**](https://www.intelligence-airbusds.com/optical-and-radar-data/)
 	* High resolution RGB and synthetic-aperture radar imagery. 
* [**Blacksky**](https://www.blacksky.com/)
  * Plan for high temporal resolution
  * Relatively high spatial resolution
  * Relatively low spectral resolution

<sup>Algumas das fontes acima foram extraídas do repositório [nicar20-imagery-sources](https://github.com/timwallace/nicar20-imagery-sources) por [Tim Wallace](https://github.com /timwallace)<sub>


## 4. Reconhecimentos
Esses materiais baseiam-se em treinamentos anteriores desenvolvidos pelo Programa NASA Advanced Remote Sensing Training [(ARSET)](https://appliedsciences.nasa.gov/what-we-do/capacity-building/arset). Agradecimentos especiais ao [Dr. Amita Mehta](https://sciences.gsfc.nasa.gov/sed/bio/amita.v.mehta), [Dr. Erika Podest](https://science.jpl.nasa.gov/people/podest/), [Dr. Ana Prados](https://jcet.umbc.edu/jcet-faculty/person/ed05369/) e o restante da equipe ARSET por fornecer esses materiais! Obrigado também a Aarti Arora por ajudar a desenhar a agenda da reunião.


<p align="center">
  <a href="#ISAT-Training-LaPlata">(Back to top)</a>
</p>
