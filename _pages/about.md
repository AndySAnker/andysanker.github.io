---
permalink: /
title: "Academic biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Throughout my university career at the [Nanostructure Group UPCH](https://nanostructure-cph.com/) supervised by [Kirsten Marie Ørnsbjerg Jensen](https://scholar.google.com/citations?user=0LD11kYAAAAJ&hl=da&oi=ao), I have worked with material chemistry, where my main interest has been to study nanoparticles and structures in solution with Total X-ray Scattering with Pair Distribution Function (PDF) and Small-Angle X-ray Scattering (SAXS). I have applied advanced computer modelling, in Python, to combine information of both the local order from PDF and the particle order from SAXS, which overcome problems that the methods cannot overcome individually. 
During my career, the research focus has converged towards developing machine learning (ML) methods to analyse chemical data; especially PDF & SAXS, after I met Assistant Professor [Raghavendra Selvan](https://raghavian.github.io/) who I had collaborated with since 2019. I have furthermore spent 6 months during my PhD working at Rutherford Appleton Laboratory with Senior Lecturer [Keith Tobias Butler](https://www.sems.qmul.ac.uk/staff/k.butler) and the [Scientific Machine Learning Group](https://www.scd.stfc.ac.uk/Pages/Scientific-Machine-Learning.aspx) to develope an general approach to match simulated and experimental data in materials chemistry.
During the last period of my PhD, I will especially focus on using generative models to analyse a range of data used to analyse chemistry as scattering-, spectroscopy- and imaging data.


Research projects
=======

**Using X-ray scattering to study the structure of nanomaterials during reaction** <br>
Designing new functional materials relies on understanding the fundamental chemical reactions that govern material formation and growth. In inorganic and materials chemistry, we are still challenged in describing these processes on an atomic scale, as studies of nucleation and growth phenomena are challenging. Pair distribution function (PDF) analysis and small-angle X-ray scattering (SAXS) enables analysis of the formation mechanism of metal oxido nanoclusters and cluster–solvent interactions as they take place. 
I have a range of research projects using PDF and SAXS to understand the formation mechanism of nanomaterials and I have been especially interested to create new modelling approaches of PDF and SAXS data. <br>
**Collaborators:** I collaborated with Martin Schmiele and Erik Brok from the [Linx project](https://linxassociation.com/) for a few years doing SAXS. 

**Papers:** 
1. [Structural Changes during the Growth of Atomically Precise Metal Oxido Nanoclusters from Combined Pair Distribution Function and Small‐Angle X‐ray Scattering Analysis](https://onlinelibrary.wiley.com/doi/full/10.1002/anie.202103641)
2. [Size-induced amorphous structure in tungsten oxide nanoparticles](https://pubs.rsc.org/en/content/articlelanding/2021/nr/d1nr05991b/unauth)
3. [Formation and growth mechanism for niobium oxide nanoparticles: atomistic insight from in situ X-ray total scattering](https://pubs.rsc.org/en/content/articlehtml/2021/nr/d0nr08299f)

<br>

**Using explainable machine learning to automate the analysis of scattering data** <br>
While we can analytically calculate the scattering pattern from a material, we are not able to straightforwardly determine the structure from a scattering pattern. This is called the inverse problem and is the reason I have spend enourmous amounts of time analysing scattering data. We can tackle the inverse problem by training machine learning (ML) based methods on large databases of structures and their calculated scattering pattern. By using explainable ML approaches, we can learn from the ML algorithms how they determine the chemical structure from a scattering pattern and thereby understand the underlying physics and chemistry. <br>
**Collaborators:** I collaborated with Professor [Simon J. L. Billinge](https://scholar.google.com/citations?user=dRmx8foAAAAJ&hl=en) from Columbia University and Assistant Professor [Raghavendra Selvan](https://raghavian.github.io/) from Department of Computer Science, UCPH. 

**Papers:** <br>
1. [Extracting structural motifs from pair distribution function data of nanostructures using explainable machine learning](https://www.nature.com/articles/s41524-022-00896-3) <br>
2. [Characterisation of intergrowth in metal oxide materials using structure-mining: the case of γ-MnO<sub>2</sub>](https://pubs.rsc.org/en/content/articlehtml/2022/dt/d2dt02153f) <br>
3. [Atomic structural changes in the formation of transition metal tungstates: the role of polyoxometalate structures in material crystallization](https://chemrxiv.org/engage/chemrxiv/article-details/62ebefdcd131b71fc70c4ef2) <br>

<br>

**Using generative models for structure solution from pair distribution function data** <br>
Crystallographic methods, such as single crystal and powder diffraction, allow establishing the links between material structure and properties that are at the heart of materials development. However, other approaches for atomic-scale structure determination are needed for nanostructured materials that have limited long-range order. Over the past decades, Pair Distribution Function (PDF) analysis has become a core tool for analysis of nanomaterial structure. Currently, PDF analysis is mainly done by fitting a known starting model to an experimental PDF to extract quantitative structural information. However, identifying a model or solving a structure de novo, from a PDF, is still an enormous challenge. I develop generative models that can solve a simple nanoparticle structure directly from a PDF. <br>
**Collaborators:** I collaborated with Professor [Simon J. L. Billinge](https://scholar.google.com/citations?user=dRmx8foAAAAJ&hl=en) from Columbia University and [Assistant Professor Raghavendra Selvan](https://raghavian.github.io/) from Department of Computer Science, UCPH. <br>
**Papers:** 
1. [DeepStruc: Towards structure solution from pair distribution function data using deep generative models](https://pubs.rsc.org/en/content/articlehtml/2022/dd/d2dd00086e)
2. [Characterising the atomic structure of mono-metallic nanoparticles from x-ray scattering data using conditional generative models](https://par.nsf.gov/biblio/10300745)

<br>

**Using generative adversarial networks to match simulated and experimental inelastic neutron scattering data** <br>
Supervised machine learning (ML) models are frequently trained on large datasets of physics-based simulations with the aim of being applied to experimental data. However, ML models trained on simulated data often struggle to perform on experimental data, because there is a shift in the data caused by experimental artefacts that might be challenging to simulate. We introduce Exp2SimGAN, an unsupervised image-to-image ML model to match simulated and experimental data. To train, Exp2SimGAN only requires a set of experimental data and a set of (not necessarily corresponding) simulated data. Once trained, it can convert a simulated dataset into one that resembles an experiment, and vice versa. We demonstrate that Exp2SimGAN can be used to match simulated and experimental two- and three-dimensional inelastic neutron scattering (INS) spectra, enabling the analysis of experimental INS data using supervised ML. Finally, we provide a domain of application measure for Exp2SimGAN, allowing us to assess the likelihood that Exp2SimGAN will be successful on a specific dataset. Exp2SimGAN is a step towards analysis of experimental data using supervised ML models trained on physics-based simulations. <br>
**Collaborators:** I collaborated with Senior Lecturer [Keith Tobias Butler](https://www.sems.qmul.ac.uk/staff/k.butler), the  [Scientific Machine Learning Group](https://www.scd.stfc.ac.uk/Pages/Scientific-Machine-Learning.aspx) and [Dr. Duc Le](https://www.isis.stfc.ac.uk/Pages/Dr-Duc-Le.aspx) and Professor [Toby Perring](https://www.isis.stfc.ac.uk/Pages/Prof-Toby-Perring.aspx) from ISIS.

**Papers:**
1. [Using generative adversarial networks to match experimental and simulated inelastic neutron scattering data](https://chemrxiv.org/engage/chemrxiv/article-details/63a15e21a53ea6c3c751564f)