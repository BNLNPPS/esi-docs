---
title: "Technical Notes"
layout: base5
name: technotes
---

{{ site.HR }}


#### General Technical Notes
##### About this page

This page is used to keep brief technical notes of general interest.
<hr/>

##### pyvista

A simple way to test out the graphics, including problematic cases like GL on a Mac:

```bash
python -c "import pyvista as pv; pv.examples.load_airplane().plot()" 
```


<hr/>

##### Mitsuba 3

###### Initial testing

A [sandbox repo](https://github.com/BNLNPPS/esi-mitsuba-test){:target="_blank"} has been created to test out various modalities of rendering
using the Mitsuba 3 package.

###### Papers and resources

* [Mitsuba Renderer](https://www.mitsuba-renderer.org/){:target="_blank"}
* [Mitsuba RTD](https://mitsuba.readthedocs.io/en/latest/index.html){:target="_blank"}
* [Optical Photon Simulation with Mitsuba3](https://arxiv.org/abs/2309.12496){:target="_blank"}
* [Wavefront .OBJ file format](https://en.wikipedia.org/wiki/Wavefront_.obj_file){:target="_blank"}