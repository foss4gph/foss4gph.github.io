
## About FOSS4G-PH

OSGeo Philippines (OSGeo-PH) and the University of Philippines Department of Geodetic Engineering (UPD-GE) FOSSLab will organize a series of workshops and technical presentations showcasing free and open source for geospatial (FOSS4G) as part of the PhilGEOS 2017 on May 24, 2017 at the University of the Philippines Diliman, Quezon City.

## Setup
1. Create and activate virtualenv:
```
virtualenv env
. env/bin/activate
```
2. Install python libraries:
```
pip install -r requirements.txt
```
3. Go into foss4gph lektor:
```
cd foss4gph
```
4. Run lektor server:
```
lektor server
```

## Building the Site
Run the following commands to build the site:
```
cd foss4gph/
sh clean_up.sh
sh build_site.sh
```
