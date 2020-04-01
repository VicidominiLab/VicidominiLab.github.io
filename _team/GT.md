---
title: "Giorgio Tortarolo"
authorname: "Giorgio Tortarolo"
collection: team
header:
  teaser: GT.jpg
tags: post-doc
tagline: PostDoc Fellow
subject: "Super-Resolution Microscopy, Control System, Single-Molecule Tracking"
date: 2016-02-01
email: 'giorgio.tortarolo@iit.it'
cv: https://vicidominilab.github.io/files/TortaroloG__CV_2020_03_31.pdf
twitter: 'GTortarolo'
googlescholar: "https://scholar.google.com/citations?user=oZX62_AAAAAJ&hl=en"
supervisors: "Dr. Giuseppe Vicidomini (IIT)"
theme: "BrightEyes, Img Proc Anal, LSM with SPAD array, TR-STED microscopy"
# orcid: "https://orcid.org/0000-0002-1182-2478"
# collaborators: "Coll1, Coll2"

---

<h2>ShortBio</h2>
<p align= "justify">
Giorgio Tortarolo studied engineering at the Dipartimento di Informatica, Bioingegneria, Robotica e Ingegneria dei Sistemi (DIBRIS) of the University of Genoa. In 2015, he obtained the M.Sc. degree (110/110 cum laude, right of publication) for the thesis titled "Modular integration of a STED imaging system into a custom confocal microscope", later awarded from Società Italiana di Ottica e Fotonica (SIOF). After the graduation, Giorgio joined IIT as a  fellow student, under the supervisions of Dr. Giuseppe Vicidomini and Prof. Alberto Diaspro. During the six-months fellowship period, he contributed to develop the Fourier Ring Correlation Analysis, a quantitative criterium to assess the effective spatial resolution of any point-scanning microscopy image. At the end of the fellowship, Giorgio spent two months in Illinois, USA, collaborating with a well established microscopy company, ISS, to introduce in their product line a novel STED microscope.
<br>
In November 2016, Giorgio obtained the Ph.D. scholarship in Engineering at the University of Genoa, to join the Molecular Microscopy and Spectroscopy group. He focused on the realisation of an innovative image scanning microscopy (ISM) platform, leveraging the single-photon-avalanche-diode (SPAD) array detector to increase the spatial resolution and the signal to noise ratio of conventional confocal and fluorescence lifetime imaging measurements. Later, he implemented a real-time, feedback based single molecule tracking system based on the SPAD array, to follow individual molecules with high spatio-temporal precision. These projects resulted in his Ph.D. degree, obtained in March 2020 with the thesis "Laser Scanning Microscopy with SPAD Array Detector: Towards a New Class of Fluorescence Microscopy Techniques". After his graduation, Giorgio had the chance to continue his work as a Post-Doctoral Fellow in the Molecular Microscopy and Spectroscopy group, where he is currently focusing on the single molecule tracking project.

<h2>Projects Description</h2>

**Image Scanning Microscopy**: Confocal laser scanning microscopy (CLSM) has been the first microscopy technique to overcome the diffraction limit, but the resolution improvement over traditional microcopy is rarely exploited: it is theoretically achieved only if the pinhole in front of the detector is extremely closed. In this configuration, only few photons actually reach the detector, resulting in a heavy reduction of the signal to noise ratio of the recorded image. As a consequence, users usually open the pinhole to achieve a satisfactory contrast, but doing so gradually decreases - and eventually nullifies - the super-resolution effect. To overcome the tradeoff between spatial resolution and signal to noise ratio, we developed an image scanning microscopy platform, leveraging a fast, frame-rate free pixellated detection hardware: the SPAD array detector. The platform exploits the spatial and temporal distributions of the fluorescence emission light, opportunely sampled by the SPAD array detector and by the custom-made acquisition architecture, to improve traditional confocal and fluorescence lifetime imaging.

**Single Molecule Tracking**: Single molecule experiments have several advantages over ensemble experiments, including the detection of sub-populations, the investigation of the sample heterogeneity and the direct visualisation of dynamic processes. We are working on a novel, real-time, feedback-based single molecule tracking implementation, based on the SPAD array detector. In brief, each sensitive element acts as a confocal pinhole, and the recorded intensity distribution mirrors the position of the particle with respect to the center of the excitation volume. For example, if the particle lies at the center of the confocal laser spot, the maximum signal is recorded by the central element. Any displacement of the particle leads to a variation of the distribution of the recorded signal, thus allowing to estimate the particle position. Notably, the high count rates allowed by the SPAD array (up to 20 Mcount/s), combined with the asynchronous implementation of both the detector and the data acquisition electronics, allows to potentially combine real-time SMT with spectroscopy analysis, such as Fluorescence Correlation Spectroscopy (FCS). Most importantly, the single-photon timing capabilities of the SPAD array detector would allow for the combination of the SMT with time-resolved assays, such as fluorescence lifetime and single molecule Förster resonance energy transfer (smFRET), greatly increasing the information content of the recorded data.

<!---{% include author-research-themes.html %}--->
<!---{% include team-member-collaborators.html %}--->
{% include publication-list.html %}
