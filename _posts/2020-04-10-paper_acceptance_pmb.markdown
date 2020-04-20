---
layout: post
title:  "Paper on Scatter Correction for CBCT accepted for publication"
date:   2020-04-10 10:00:00 +0100
categories: publications
---

## Good News

Our paper *"A Monte Carlo based scatter removal method for non-isocentric cone-beam CT acquisitions using a deep convolutional autoencoder"* got accepted for publication with the Journal of Physics in Medicine & Biology.

After a long journey, this is my first paper and my first as a (shared) first author.

### Abstract

The primary cone-beam computed tomography (CBCT) imaging beam scatters inside the patient and produces a contaminating photon fluence that is registered by the detector. Scattered photons cause artifacts in the image reconstruction, and are partially responsible for the inferior image quality compared to diagnostic fan-beam CT. In this work, a deep convolutional autoencoder (DCAE) and projection-based scatter removal algorithm were constructed for the ImagingRingTM system on rails (IRr), which allows for non-isocentric acquisitions around virtual rotation centers with its independently rotatable source and detector arms. A Monte Carlo model was developed to simulate (i) a non-isocentric training dataset of ~1200 projection pairs (primary + scatter) from 27 digital head-and-neck cancer patients around five different virtual rotation centers (DCAENONISO), and (ii) an isocentric dataset existing of ~1200 projection pairs around the physical rotation center (DCAEISO). The scatter removal performance of both DCAE networks was investigated in two digital anthropomorphic phantom simulations and due to superior performance only the DCAENONISO was applied on eight real patient acquisitions. Measures for the quantitative error, the signal-to-noise ratio, and the similarity were evaluated for two simulated digital head-and-neck patients, and the contrast-to-noise ratio (CNR) was investigated between muscle and adipose tissue in the real patient image reconstructions. Image quality metrics were compared between the uncorrected data, the currently implemented heuristic scatter correction data, and the DCAE corrected image reconstruction. The DCAENONISO corrected image reconstructions of two digital patient simulations showed superior image quality metrics compared to the uncorrected and corrected image reconstructions using a scatter removal heuristic. The proposed DCAENONISO scatter correction in this study was successfully demonstrated in real non-isocentric patient CBCT acquisitions and achieved statistically significant higher CNRs compared to the uncorrected or the heuristic corrected image data. This paper presents a projection-based scatter removal algorithm for CBCT imaging using a deep convolutional autoencoder trained on Monte Carlo composed datasets. The algorithm was successfully applied to real patient data.


### Reference
[A Monte Carlo based scatter removal method for non-isocentric cone-beam CT acquisitions using a deep convolutional autoencoder](https://doi.org/10.1088/1361-6560/ab8954){:target="_blank"}

Brent van der Heyden¹, __Martin Uray¹__, Gabriel Paiva Fonseca, Philipp Huber, Defne Us, Ivan Messner, Adam Law, Anastasiia Parii, Niklas Reisz, Ilaria Rinaldi, Gloria Vilches-Freixas, Heinz Deutschmann, Frank Verhaegen, Philipp Steininger

Physics in Medicine & Biology, 2020

¹ contributed equally
