# Deconvolution-algorithms-for-3D-quantitative-Raman-microspectroscopy

Here are some of the machine learning algorithms, data augmentation and validation (cross-validation) Python scripts that I developed as part of my master thesis at
The Stevens Lab @ Imperial College London Department of Bioengineering. 

The main body of my work was the performance comparison of several algorithms in terms of hyperspectral Raman data deconvolution and biochemical quantification accuracy results.
Using as benchmark the commonly used but problematic Ordinary Least Squares (OLS) -- default go-to algorithm in Chemometrics for Raman.

I deployed and adapted Python classes for Hybrid Least Squares (HLA), Partial Least squares Regression(PLSR), Multivariate Curve Resolution - Alternative Least Squares (MCR-ALS) from their original papers.

These implementations showed state-of-the-art performance first in phantom data as validation (we know the ground truth across the 3D volume), but also in brain and endometrial organoids 3D scans. These algorithms will set the computational basis towards a platform technology that will enable biologists and clinicians to quantify the biochemical composition of any 3D biospecimen with submicron resolution, in a non-invasive and label-free manner.

The final goal of this technology is to analyze the drug metabolism of different organoids in devices such as organism and organ on a chip.

As part of this work, I also developed a novel algorithm (Not yet disclossed) that performed comparably and in some scenarios better than the rest of the models hereby described. 

This work is currently (as of Christmas 2022-2023) under review in ACS Central Science.
