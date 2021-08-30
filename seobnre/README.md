# Eccentric GWTC-2
We construct eccentricity posteriors for GWTC-2 events using `SEOBNRE` ([Zhoujian Cao and Wen-Biao Han, 2017](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.96.044028)) waveforms with aligned spin and eccentricity. 
We reweight PE ([Ethan Payne et al, 2019](https://arxiv.org/abs/1905.05477)) performed with non-eccentric IMRPhenomD ([Sebastian Khan et al, 2015](https://arxiv.org/abs/1508.07253)) waveforms. 
We construct eccentricity-marginalised likelihoods to use in the weights calculation, and use the full cumulative likelihood computed with SEOBNRE to reconstruct eccentricity posteriors.

Corner plots in this repository show posteriors for our base waveform IMRPhenomD in teal, and reweighted eccentric posteriors using SEOBNRE in grey.
