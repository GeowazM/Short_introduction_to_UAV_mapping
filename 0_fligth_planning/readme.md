## 0. Fligth planning or rather preparations (indoor)

Some stuff should be checked before going into the field. E.g. equipment, software, charging etc.

---

### Technical requirements
  * **UAV incl. equipment** 
    * Controller (*charged*)
    * Battery (*charged*)
    * Smartphone or rather tablet (*charged*) incl. software to fly (*e.g. DJI Fly, DJI ???*)
    * Cable to connect controller to smartphone/tablet (*e.g. USB to USB-C, USB to Lightning*)
    * SD card (*e.g. 128GB*)
 
<br>

  * **Multispectral camera** (*if needed*)
    *  MicaSense RedEdge-M (Legacy) incl. GPS and radiation sensor (*or similar*)
    *  Micro SD card (*max. 32GB*)

<br>

  * **GNSS equipment**
    *  Base station 
        * EMLID Reach RS+ unit (*or similar*)
        * Tripod
        * Antenna (*LoRa or similar*)
        * Cable to conntect USB to Micro-USB
        * Smartphone with software *EMLID Flow*
          * conntect via Wifi
    * Rover
      * Terrestrial Rover
        * Trimble Geo7x unit (*or similar*)
        * Antenna (*Zephyr M2 or similar*)
        * Pole
      * Airborne rover
        * EMLID Reach M+ unit (*or similar*)
        * Mounting equipment

<br>

--- 

### Administrative requirements
* [Geo Zone Map](https://www.dji.com/flysafe/geo-map)
    * Select Area 
      * *Continent* 
      * *Country* 
      * *UAV model* 

<br>

* If fligth permission is necessary contact
  * Municipality or
  * Federal province

---

### Environmental requirements
* Weather
  * Precipitation
  * Wind speed

<br>

* Useful for pilots
  * [DWD products for UAV pilots](https://www.dwd.de/DE/fachnutzer/luftfahrt/teaser/luftsportberichte/luftsportberichte_node.html) 
  * UAV weather apps [(e.g. UAV-Vorhersage für Drohnen)](https://play.google.com/store/apps/details?id=com.uavforecast&hl=de&gl=US)


---




- Requirements:
     - Camera   
          - iPad with DJI app
          - SD card
     - Multispectral camera:
          - Reference panel
          - Micro SD card
     
Set the fligth route via app and set the fligth parameters. The fligth parameters depend on the target area and objects.

Here are some fligth parameters based on the experiences with monitoring orchards.
* Fligth heigth: 30m or with high trees 35m
* Image overlaps: 90% in fligth direction and 70% orthogonal to the fligth direction.

After landing, a check of the ligth on top of the multispectral camera is needed to eliminate potential failures.


     
![Example of a tablet](images/ipad.webpg "Tablet")

<br>   
<br>
<br>

#### 2. Measureing Groud Control Points (GCP)
- Requirements:
     - [TrimbleGeo7xGNSS](https://geospatial.trimble.com/products-and-solutions/geo-7x-gnss)

The GCP are important to georeference the processed data precisly. 
More information can be found [here](https://www.dronedeploy.com/blog/what-are-ground-control-points-gcps/).

The GCP can be exported and printed automatically with Agisoft Metashape.
Theoretically, with sufficient resolution of the GCP Agisoft Metashape should recognize the GCP in the data processing automatically. However, if this is not the case the GCP have to set manually.

THe GCP measurements to be exported as a csv file for every measurement and can be copied on a SD card in the 



<br>

![GNSS measruement](images/gcp.png "GNSS measurement")

     
<br>

--- 
