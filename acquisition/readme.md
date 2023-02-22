## Acquisition

#### The data acquisition includes mainly two parts
1. UAV fligth itself and 
2. the acquisition of the ground control points (GCP).


<br>

Source: [itsfourland](https://its4land.com/fly-and-create)

<br>

The data acquisition includes the UAV fligth itself and the measureing of the ground control points (GCP).
<br>



#### 1. UAV fligth

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
