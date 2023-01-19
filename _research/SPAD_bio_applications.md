---
title: "Investigating the dynamics of bio-molecular condensates and organelles by spectroscopy tools and super-resolution imaging"
shortd: "A critical aspect of all biological processes is their temporal organization at all biological levels, ranging from embryo development, cell/tissue homeostasis, and, in general, all biomolecular functions. Despite the massive improvements in optical resolution, studying temporal processes and biomolecular dynamics is still challenging. We are working towards shining new light into the complex behaviors of single biomolecules and organelles by applying a comprehensive class of novel microscopy methods based on the high throughput of single-photon avalanche diode (SPAD) array detectors."
quote: "One man’s noise is another man’s signal (Edward W Ng)."
type: "SPAD bio app"
collection: research
date: 2023-01-19
author_profile: true
header:
  teaser: SPAD_app.png
layout: archive
---

<div style="text-align: justify">
A critical aspect of all biological processes is their temporal organization at all biological levels, ranging from embryo development, cell/tissue homeostasis, and, in general, all biomolecular functions. Despite the massive improvements in optical resolution, studying temporal processes and biomolecular dynamics is still challenging. We are working towards shining new light into the complex behaviors of single biomolecules and organelles by applying a comprehensive class of novel microscopy methods based on the high throughput of single-photon avalanche diode (SPAD) array detectors.  

The project consists of two main applications of interest. 

<br>
<br>

<h2>Cellular trafficking of membrane-coated organelles investigated by single-particle tracking</h2>

At a cellular level, the regulation of biochemical processes in space and time is implemented with several strategies, such as the confinement of the molecules involved in the reactions inside compartments. The recruitment generally occurs in membrane-bounded organelles, which result from incorporating cellular material into a lipid bilayer membrane. 

Known as cellular garbage disposals, lysosomes are intracellular membrane-bounded organelles essential for homeostasis maintenance. Lysosomes exchange metabolites and signaling molecules by interacting and fusing with other organelles. Indeed, by dragging across cytoskeleton filaments, lysosomes can rapidly move in different cellular areas, allowing cell signaling and molecule exchange. Protein mutations associated with diseases such as amyotrophic lateral sclerosis (ALS) can impair transport through lysosomes. Investigation of motility and trafficking of lysosomes inside living cells is crucial to elucidate the molecular processes behind disease etiology.  

We are investigating the motion of lysosomes across the cytoskeleton using real-time single-particle tracking (RT-SPT). We implemented this technique in a novel way by equipping a conventional laser-scanning microscope with a 5x5 SPAD array detector and an astigmatic detection. In first approximation, this matrix detector behaves as a small camera producing a 5x5 image of the fluorescence emission (we call it “micro-image”) which directly contains the position information of the particle with respect to the center of the illumination volume. Since each pixel is independent, the detection is not framerate, and the estimation of the position can be performed in real-time, allowing the re-positioning of the illumination system.  

<br>

<h2>Molecular dynamics inside membrane-less organelles investigated by fluorescence fluctuation spectroscopy</h2>

For a long time, membrane-coated organelles have been considered the unique way to confine molecules involved in cellular reactions. Recently, the scientific community has accepted the idea of compartmentalization processes driven by membrane-less organelles (MLOs).  While membrane-coated organelles confine molecules in a specific region enclosing them in a membrane, MLOs concentrate molecules through the so-called liquid-liquid phase separation (LLPS) process. LLPS is a reversible thermodynamic phenomenon that consists of de-mixing a uniformly liquid system into two distinct liquid phases, which differ by concentration: in the cellular environment, the cytoplasm (or nucleoplasm), and the MLOs.  

The driving forces of LLPS are weak multivalent interactions between molecules. At the cellular level, two biomolecules are involved in the phase separation process: proteins with intrinsically disordered domains and RNA molecules. Changes in the interaction network or protein mutations can promote the transition of liquid-like condensates, such as MLOs, from liquid to solid, commonly associated with cellular toxicity. 

On one side, how RNA molecules affect the LLPS of proteins remains unclear; on the other side, there is a lack of methodology to explore the role of RNAs in phase transitions both in vitro and in cells. We propose to fill the gap by exploiting the augmented single-photon information provided by the SPAD array detector to perform fluorescence fluctuation spectroscopy (FFS) techniques to investigate the early stage of the LLPS transition of proteins and RNAs.  

Thanks to the introduction of the 5x5 pixel SPAD array detector in a confocal laser-scanning microscope, we can now temporally tag each photon and simultaneously detect the position of each detected photon. SPAD array detector can provide information about diffusion modes (by performing, e.g., Spot-variation FCS), structural changes (e.g., with fluorescence lifetime and time-lapse ISM imaging), and functional changes (e.g., FRET measurements or dual-color Fluorescence Cross-Correlation Spectroscopy) of molecules in biological samples. 

<h3>in vitro</h3>

The synaptic protein alpha-synuclein can undergo LLPS in a crowded environment, but the kinetics and dynamics behind the process need to be still clarified. Taking advantage of FFS with the SPAD array detector, we investigate the phase transition from the monomeric state to the liquid-like state of the alpha-synuclein, mainly focusing on the effect that RNA and nucleic acids may have in the process.  

<h3>living cells</h3> 

When subjected to stress, cells deploy several strategies to accumulate misfolded proteins, repair damaged molecules or protect still non-damaged molecules. One approach consists of the confinement of proteins and RNA molecules inside MLOs known as stress granules. Accumulation of the stress granules inside cells is linked to several neurodegenerative diseases.  

An ongoing project focuses on unraveling the molecular dynamics of two proteins, G3BP1 and FUS, during the formation of stress granules. Taking advantage of FFS with the SPAD array detector, we are quantifying the interactions between the two protein partners before and after stress, as well as the kinetics of the recruitment of both proteins inside stress granules of living cells and the changes in the cellular structure. The combination of dynamic information with changes in the micro-environment and structural changes of the molecules allows the investigation of stress granule formation and the disassembly at a single-molecule level inside living cells.  

</div>

<br>

{% include theme-team-members.html %}
{% include publication-list-theme.html %}
