---
title: "Single-Photon Laser-Scanning Microscopy with SPAD Array Detector"
quote: "When you consider humans on the average, we have one brain, one heart, two lungs, two kidneys,....one ovary, one testicle (Prof. Steven M. Block)."
shortd: "Typically, laser scanning microscopy provides a single averaging intensity value for each pixel/position of the sample, i.e., a value for each detection volumes. Surely, this averaging/integrating process discards inportant information, such as the temporal dynamics, and the spatial distribution of detection volume image. To overcoem this limitation, we have recently introdued a single-photon detector array able to register photon one at a time. In short, the detector allows to tag photons temporally (with picoseconds preciosion) and spatially (with nanometres precision). The aims of this set of projects is to open to a new imaging paradigma able to take advantags of this new single-photon dataset. We call this paradigma single-photon microscopy." 
type: LSM with SPAD array
collection: research
date: 2016-04-01
author_profile: true
header:
  teaser: LSM_with_SPADarray.jpg
layout: archive
---

<div style="text-align: justify">
Laser-scanning microscopy (LSM) is one of the most popular optical microscopy architectures in Life Sciences. This popularity is due to the possibility to combine LSM with the fluorescence mechanism and with many advanced microscopy techniques: confocal microscopy, which provides three-dimensional imaging; two-photon excitation (TPE) microscopy, which offers deep imaging; fluorescence lifetime, which offers functional imaging; fluorescence fluctuation spectroscopy (FFS), which allows deciphering molecular dynamics, to mention a few. This synergy results in a  microscope system with a unique combination of spatial and temporal characteristics and a strong ability to provide a vast pool of information about the sample investigated.
<br>
<br>  
However, the performance of current fluorescence LSM can be tremendously improved by changing the image recording process. In conventional fluorescence LSM, the so-called detection/probing volume is raster scanned across the specimen. For each specimen position, a single-element detector (e.g., a photo-multiplier tube (PMT)) samples the fluorescence signal in time, but spatial integrates across its sensitive area. Successively, the data-acquisition system temporally integrates the signal along the pixel-dwell time (in the range of microseconds) and produces a single intensity value per position/pixel. Finally, a computer build-up the digital image. In short, for each sample position (i.e., detection volume), the induced fluorescence photons are integrated regardless of their spatial and temporal distribution; thus, the information potentially encoded in the dynamic and image of each probing volume are lost. Similar information loss occurs in a single-point fluorescence correlation spectroscopy (FCS) experiment, where, since the detection volume is stationary, the photons are not integrated along the pixel-dwell time, but along the bin of the time-trace (in the range of microseconds).
<br>
<br>
To solve this limitation, we have introduced a series of asynchronous read-out single-photon avalanche diode (SPAD) array detectors able to fully preserve the spatial and temporal information encoded in the probing volume of the fluorescence laser-scanning microscope. In particular, the SPAD array detectors are composed of a small number (e.g., 5 by 5) of micro-sized element/pixel able to independently deliver a digital signal, with a precision of a few hundred picoseconds, every time that a photon is registered. Thanks to the micron size of the elements, a zoom-lens system allows it to quickly obtain a sub-Nyquist sampling of the detection volume image. Simultaneously, a time-resolved data-acquisition system, synchronized with a pulse laser beam, allows recording the fluorescence signal with a temporal resolution compatible with most of the photo-physical phenomena relevant to Life science experiments, such as the excited-state fluorescence lifetime. As a mother of fact, these SPAD array detectors allow implementing an LSM architecture where the image (more in general data) recording process does not introduce any information lost described above.

<figure style="width: 50%" class="align-center">
<img src='/images/SinglePhotonsMicroscopy.jpg'>
<figcaption>Comparison between laser-scanning microscopy with typical single-element detecor and with SPAD array detector.</figcaption>
</figure>

Scope of this project is to use this new set of spatiotemporal single-photon information to improve the performance of many different advanced LSM-based techniques. We called this new LSM architecture single-photon microscopy because the data recording occurs at the photon level, i.e., every single-photon is registered together with a series of spatial and temporal tags.
</div>
<br>
| Resourse | Description | Link |
| --- | --- | --- |
| Twitter | #singlephotonmicroscope (hashtag on twitter) | <a href="https://twitter.com/hashtag/singlephotonmicroscopy?src=hashtag_click"><span style="color:blue">here</span></a> |

<h2> Videos: </h2>
<video width="480" height="320" controls="controls" class="align-center">
<source src="/videos/VicidominiG_SIF_2020_max_compression.mp4" type="video/mp4">
</video>

{% include theme-team-members.html %}
{% include publication-list-theme.html %}

