## 1. Data acquisition (outdoor)

You can use this file as a check list in the field. 

---

### a) Assemble UAV

- Requirements:
     - Camera   
          - iPad with DJI app
          - SD card
     - Multispectral camera:
          - Reference panel
          - Micro SD card

<br>

---

### b) Set flight parameters

Set the flight route via app and set the flight parameters. The flight parameters depend on the target area and objects.


Some variable depends on the object you want to map (*e.g. fligth parameters, path or the amount of GCPs*). 
* A good figure about the flight parameters and their influence on further parameter can be found [here](https://www.researchgate.net/figure/Different-parameters-in-drone-flights-The-outer-box-represents-the-target-variables_fig1_333403653) 
* A comprehensive scientific paper by [Mesas-Carrascosa et al. (2016)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5134497/) cover the role of several flight parameters including good examples

<br>

Here are some fligth parameters based on the experiences with monitoring orchards.
* Fligth heigth: 30m or with high trees 35m
* Image overlaps: 90% in fligth direction and 70% orthogonal to the fligth direction.

After landing, a check of the ligth on top of the multispectral camera is needed to eliminate potential failures.

<br>

---

### c) Create flight path

...in progress

<br>

---

### d) Ready for takeoff

...in progress

<br>

---

### e) Measure Groud Control Points (GCP)

The GCP are important to georeference the processed data precisly. 
More information can be found [here](https://www.dronedeploy.com/blog/what-are-ground-control-points-gcps/).
For another good explanation have a look [here](https://www.groundcontrolpoints.com/mapping-contour-lines-using-gcps).
Some background information about cartography principles can be found [here](https://www.groundcontrolpoints.com/).


Theoretically, with sufficient geometric resolution of the imagery Agisoft Metashape should recognize the GCP in an imagery analysis process automatically. However, if this is not the case the GCP have to set manually.



<br>


<p align="center">
     <img src="https://github.com/GeowazM/Short_introduction_to_UAV_mapping/blob/main/images/gcp.png?raw=true"
          alt="GNSS rover with tripod (Trimble Geo7x)" width=300/>
</p>

<p align="center">
     Source: <a href = "https://rgeo.de/en/p/streuobst/"> rgeo </a>
</p>

<br>


--- 
