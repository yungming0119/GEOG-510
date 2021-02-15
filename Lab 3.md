# Curriculum Vitae
## **Yung-Ming Tsai** [![image](https://img.shields.io/badge/email-ytsai5%40vols.utk.edu-blue)](mailto:ytsai5@vols.utk.edu)

### Education
* Bachelor Degree: National Taiwan Normal University, Geography (2013-2017)
* Master Degree: Natioanl Taiwan Normal University, Geography (2017-2020)
* University of Tennessee, Knoxville, Geography (present)

### Research Interest
* Space-time Geographic Data Mining
* Human Dynamics

### Projects
1. *An Unsupervised Machine Learning Approach for Multi-Dimensional Network Data Mining*

`
<iframe src="https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211407424&authkey=AFy-5svVYhknhKA&em=2" width="402" height="327" frameborder="0" scrolling="no"></iframe>
`

2. *Landslide Detection from Satellite Imagery Using a Deep Learning Technique*

`
<iframe src="https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211419584&authkey=ALEOOOtP2bKzpp8&em=2" width="402" height="327" frameborder="0" scrolling="no"></iframe>
`

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
`<iframe src="https://onedrive.live.com/embed?cid=B30494012EB6EC6A&resid=B30494012EB6EC6A%211447911&authkey=APNjvsXe8tl1tX8" width="320" height="180" frameborder="0" scrolling="no" allowfullscreen></iframe>`
