# Data science, cosmology, physics


I am a Senior Scientist at [ETH Zurich](https://www.cosmology.ethz.ch) and a Senior Data Scientist at the [Swiss Data Science Center](https://www.datascience.ch) at the [Paul Scherrer Institute](https://www.psi.ch). I obtained my PhD in Physics and Astronomy from the University College London, as well as previously a MSc in Machine Learning from the same university.
My focus is applications of novel machine learning and high-performance computing to solve outstanding problems in physics, cosmology, and climate science.

<br>
# Recent papers
---

- *CosmoGridV1: a simulated 𝗐CDM theory prediction for map-level cosmological inference*, with data available at [www.cosmogrid.ai](www.cosmogrid.ai), published in [JCAP 2, 50, 2023](https://iopscience.iop.org/article/10.1088/1475-7516/2023/02/050),

- *DeepLSS: breaking parameter degeneracies in large scale structure with deep learning analysis of combined probes*, published in Physical Review X, [Phys. Rev. X 12 031029, 2022](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.12.031029), and promoted in the [APS Physics Magazine](https://physics.aps.org/articles/v15/s111),

- *Dark Energy Survey Year 3 results: Cosmology with peaks using an emulator approach*, published in [MNRAS 511, 2, 2075-2104, 2022](https://academic.oup.com/mnras/article-abstract/511/2/2075/6511572),

- *Full wCDM analysis of KiDS-1000 weak lensing maps using deep learning*, published in [Phys. Rev. D 105, 083518, 2022](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.105.083518).


<br>
# Projects
---

###  Cosmology and artificial intelligence
Artificial Intelligence methods, such as deep convolutional neural networks, have the capacity to model the complex patterns contained in the cosmic web. I have introduced the deep learning approaches to constraining cosmological parameters and generating large scale structure simulations. I demonstrated that the AI-based analysis can achieve 40% improvement in measurement precision, a gain equivalent to using 2x more survey data with conventional methods.

- I performed the first cosmological analysis with deep learning, on KiDS-450 dataset ([Phys. Rev. D 2019, 100, 063514](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.100.063514), with Janis Fluri), which was promoted by [ETH News (18/09/2019)](https://ethz.ch/en/news-and-events/eth-news/news/2019/09/artificial-intelligence-probes-dark-matter-in-the-universe.html) and [MIT Techology Review (19/09/2019)](https://www.technologyreview.com/2019/09/19/446/facial-recognition-algorithms-can-be-deployed-to-hunt-for-dark-matter/). 

- I was the PI of the production project "Measuring Dark Energy with Deep Learning" at the Swiss Supercomputing Center (CSCS), producing the CosmoGrid simulations, available at [www.cosmogrid.ai](http://www.cosmogrid.ai).

- I was the PI of the ["Deep Learning for Observational Cosmology"](https://datascience.ch/project/dloc/) programme at the Swiss Data Science Center (SDSC).

- I was the lead organizer for the workshop ["Artificial Intelligence Methods in Cosmology"](https://sites.google.com/site/aicosmo2019/), held in Monte Verita, Ascona, 9-12 June 2019.

### Machine learning for applied physics

At PSI, I work on a number of projects advancing the applications of machine learning to applied physics and climate simulations.
By applying novel machine learning methods, (deep learning, generative models), and utilizing latest high-performance computing hardware (A100 GPS, the Alps cluster), I enable achieving scientific objectives that are unattainable with classical methods.

- I lead the collaborative project "Robust and scalable Machine Learning algorithms for Laue 3-Dimensional Neutron Diffraction Tomography" at the PSI. Our novel approach to indexing of polycrystalline diffraction patterns from neutron tomography is capable of analyzing 10x larger samples with 100x gain in speed, compared to previous methods. The paper [Laue Indexing with Optimal Transport](https://arxiv.org/abs/2404.06478) is under review in IEEE PAMI. The upcoming package LaueOT will avalilable at [Github](https://github.com/LaueOT/laueotx).

- I am the lead data scientist for the collaborative project between SDSC and the PSI Center for Neutron and Muon Research, called "Smart Analysis of MUonic x-Rays with Artificial Intelligence". This project analyses muonicy spectra obtained by the state-of-the-art moun-induced X-ray emmission instrument [MIXE](https://www.psi.ch/en/smus/muon-induced-x-ray-emission-mixe-project) to infer the chemical composition of various samples, such as alloys, batteries, archeological artifacts.

### Dark Energy Survey

I am a Builder of the [Dark Energy Survey](http://www.darkenergysurvey.org), the largest ground-based cosmological observational survey to date. This program has delivered the most precise cosmological parameter measurements from large scale structure of the universe to date.
I have been involved in DES since 2012, with the following contributions:

- As the Simulations Working Group coordinator and a memeber of the Science Committee (2022-), I organize new projects and collaboration in the area of simulation-based inference and provide CosmoGridV1 simulations, where we aim to further increase the precision of measurements from the expensive DES dataset with simulations-based inference, as well as making it more robust to systematic errors.

- I led the first simulation-based inference cosmology measurement with DES, using shear peaks and the Science Verification dataset ([MNRAS 2016, 463, 4](https://academic.oup.com/mnras/article/463/4/3653/2646308)), followed by the full survey area analysis in DES Year 3 ([MNRAS 2022, 511, 2](https://academic.oup.com/mnras/article-abstract/511/2/2075/6511572)). This analysis improved on the main DES measurement by 30%, while using low-resolution maps.

- I worked extensively on galaxy shape measurements for weak gravitational lensing, image simulations, and noise biases in shear calibrations, and contributed significantly to DES Science Verification (SV) weak lensing analysis ([MNRAS 2016, 460, 2](https://academic.oup.com/mnras/article/460/2/2245/2609178)). This work enabled reliable shape measurements for DES-SV cosmology.


### Simulations-based inference in cosmology and astronomy

In photometric surveys, the distances to galaxies are inferred from galaxy colors by matching them to galaxies found in previous spectroscopic surveys.
While this approach has many successes for closeby galaxies, where spectroscopic data is available in abundance, it can be difficult to reliably apply to far-away galaxies.
This is due to our lack of understanding of the population these high-redshift galaxies, as well as their evolution over cosmic time. 
Difficulties with modelling selection functions for spectroscopic surveys further complicates this problem.
An alternative is to use a Monte Carlo Control Loop (MCCL) approach, inspired by approaches in particle physics.
MCCL uses physically-motivated parametric models for galaxy properties evolution, as well as very precise simulations of the telescope and its selection functions.
This allows us to achieve the same precision of redshift measurement without using spectroscopy of high-redshift galaxies.

- I developed first forward-modelling, simulations-based approach to measuring redshifts of galaxy samples from wide-band photometry alone ([JCAP 2017, 08, 035](https://iopscience.iop.org/article/10.1088/1475-7516/2017/08/035), with Joerg Herbel), which uses Approximate Bayesian Computation (ABC) and utilizes high-performance computing platforms. 

 - I led the team at the ETH Zurich that applied the simulations-based inference methodology to the Dark Energy Survey Year 1 cosmology.  We performed first simulation-based joint measurement of cosmological lensing shear power spectra and the redshift distributions of the galaxy samples. The ETH team created a full analysis pipeline, from image pixels to cosmology parameter constraints ([Phys. Rev. D 2020, 101, 082003](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.101.082003)).


<br>
# Talks
---

I gave >20 invited talks at international conferences, workshops, and university colloquia. Some of them are available online.

Invited keynote talk at *Bayesian deep learning for cosmology and time domain astrophysics*, Paris, France, June 20-24 2022 (AstroDeep22)

{% include youtube.html id="X0Uk8gB-dF4" %}

<br>

Other recorded talks include:
- ICS Theoretical Astrophysics & Computational Science, University of Zurich, Switzerland, 2022, [youtube](https://www.youtube.com/watch?v=0HihsVz_b9I).
- Institute of Space Sciences (ICE-CSIC), Barcelona, Spain, 2022, [youtube](https://www.youtube.com/watch?v=2E7ys35x3Rw).
- Cosmic Connections: A ML X Astrophysics Symposium at Simons Foundation, Flatiron Institute, New York, USA, [video: day 2 session 2](https://www.simonsfoundation.org/event/cosmic-connections-a-ml-x-astrophysics-symposium/).


<br>
# Datasets and software
---

I am producing and maintaining a number of datasets and software packages.

- I am the leader of the CosmoGridV1 simulation project, which produces cosmological simulations suited for analyses with artificial intelligence. 
The data from CosmoGridV1 is available at [www.cosmogrid.ai](www.cosmogrid.ai).

{% include youtube.html id="_7NP7s_0d7E" %}

<br>

- I co-created [DeepSphere](https://github.com/deepsphere), a graph-based neural network architecture for analysing data on the sphere ([Astr. Comp. 2019, 27](https://www.sciencedirect.com/science/article/abs/pii/S2213133718301392?via%3Dihub)).

- I published the [DeepLSS code](https://github.com/tomaszkacprzak/DeepLSS) from the PRX paper [Phys. Rev. X 12 031029, 2022](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.12.031029).

- I am developing the [LaueOT package](https://github.com/LaueOT/laueotx), a toolbox for fast analysis of tomographic diffraction patters from polycrystalline samples.


<br>
# Teaching
---

I taught a number of courses on machine learning and data science, cosmology, and astrophysics:

- *Statistical Methods and Analysis in Experimental Physics* (2019, 2020), MSc course, ETHZ Physics
- *Advanced Statistical Methods in Cosmology* (2016, 2017), MSc course, ETHZ Physics
- *Cosmological Probes* (2017), MSc course, ETHZ Physics
- Guest lecturer for UG course *Introduction to Data Science* (2019, 2020), University of Zurich


<br>
# Contact
---


- Email at ETH Zurich: tomaszk at phys dot ethz dot ch
- Email at PSI: tomasz dot kacprzak at psi dot ch


<br>
# New projects
---

If you are a masters student in cosmology, computer science or statistics, and are interested in a project, please send me an email.


