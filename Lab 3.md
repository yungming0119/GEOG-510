# Curriculum Vitae
## **Yung-Ming Tsai** [![image](https://img.shields.io/badge/email-ytsai5%40vols.utk.edu-blue)](mailto:ytsai5@vols.utk.edu)

### Education
* Bachelor Degree: National Taiwan Normal University, Geography (2013-2017)
* Master Degree: Natioanl Taiwan Normal University, Geography (2017-2020)
* University of Tennessee, Knoxville, Geography (present)

### Research Interest
* Space-time Geographic Data Mining
* Human Dynamics

Publication
* Shih, H. C., Stow, D. A., Tsai, Y. M., & Roberts, D. A. (2020). Estimating the starting time and identifying the type of urbanization based on dense time series of landsat-derived Vegetation-Impervious-Soil (VIS) maps–A case study of North Taiwan from 1990 to 2015. International Journal of Applied Earth Observation and Geoinformation, 85, 101987.

### Projects
1. *An Unsupervised Machine Learning Approach for Multi-Dimensional Network Data Mining*
[![image](https://github.com/yungming0119/GEOG-510/blob/main/project1.png)](https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211407424&authkey=AFy-5svVYhknhKA&em=2)

2. *Landslide Detection from Satellite Imagery Using a Deep Learning Technique*
[![image](https://github.com/yungming0119/GEOG-510/blob/main/project2.png)](https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211419584&authkey=ALEOOOtP2bKzpp8&em=2")
### Labs
* Interactive Map with Python
```python
import geemap
Map = geemap.Map(center=[40,-100],zoom=4)
Map.add_basemap('SATELLITE')
wms_uri = "https://www.mrlc.gov/geoserver/NLCD_Land_Cover/wms?SERVICE=WMS&REQUEST=GetCapabilities"
Map.add_wms_layer(url=wms_uri, layers='CONUS_Land_Cover', name='NLCD_Land_Cover', format='image/png', shown=True)
Map
```
[![image](https://github.com/yungming0119/GEOG-510/blob/main/LAB2.png)](https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211447911&authkey=APNjvsXe8tl1tX8")
