## 1. Data acquisition (outdoor)

You can use this file as a check list in the field. 

---

### a) Build up UAV

- Requirements:
     - Camera   
          - iPad with DJI app
          - SD card
     - Multispectral camera:
          - Reference panel
          - Micro SD card

<br>

---

### b) Set fligth parameters

Set the fligth route via app and set the fligth parameters. The fligth parameters depend on the target area and objects.


Some variable depends on the object you want to map (*e.g. fligth parameters, path or the amount of GCPs*). 
* A good figure about the fligth parameters and their influence on further parameter can be found [here](https://www.researchgate.net/figure/Different-parameters-in-drone-flights-The-outer-box-represents-the-target-variables_fig1_333403653) 
* A comprehensive scientific paper by [Mesas-Carrascosa et al. (2016)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5134497/) cover the role of several fligth parameters including good examples

<br>

Here are some fligth parameters based on the experiences with monitoring orchards.
* Fligth heigth: 30m or with high trees 35m
* Image overlaps: 90% in fligth direction and 70% orthogonal to the fligth direction.

After landing, a check of the ligth on top of the multispectral camera is needed to eliminate potential failures.

<br>

---

### c) Create fligth path


<br>

---

### d) Ready for takeoff


<br>

---

### e) Measure Groud Control Points (GCP)

The GCP are important to georeference the processed data precisly. 
More information can be found [here](https://www.dronedeploy.com/blog/what-are-ground-control-points-gcps/).

The GCP can be exported and printed automatically with Agisoft Metashape.
Theoretically, with sufficient resolution of the GCP Agisoft Metashape should recognize the GCP in the data processing automatically. However, if this is not the case the GCP have to set manually.

THe GCP measurements to be exported as a csv file for every measurement and can be copied on a SD card in the 



<br>


<p align="center">
     <img src="https://raw.githubusercontent.com/GeowazM/Introduction_UAV/main/images/gcp.png?token=GHSAT0AAAAAAB6YWBWEXTC467URTELYZOHCY7WFP3A"
          alt="GNSS rover with tripod (Trimble Geo7x)" width=300/>
</p>

<p align="center">
     Source: <a href = "https://rgeo.de/en/p/streuobst/"> rgeo </a>
</p>

<br>


--- 
