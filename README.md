# Speeding-up-functional-network-analysis-on-fMRI-data-with-distributed-in-memory-computation-using-A
Speeding up functional network analysis on fMRI data with distributed, in-memory computation using Apache Spar

Network analysis on functional MRI imaging involves many computationally intensive steps like registration to high resolution brain templates, extraction of brain and correlated voxels and parcellation of brain regions. Rapid processing of individual brains will facilitate new applications of network analysis i.e. performing neurofeedback with fMRI systems, interactive neuroimaging to adaptively assess brain dynamics and personalized analysis of brain function. Processing speedup may be achieved by distributing computation over many nodes or parallelization on a GPU.

In this work, our focus will first be on the distributed computation approach with particular attention to in-memory computation strategies. If there is sufficient interest, the applicant is invited to propose optimizations that could be more efficiently implemented on GPU. The ideal outcome will be a hybrid software system of both GPU and virtual machines which may adaptively combine and manage available resources to the processing task at hand.


**Aims**

Design and implement in-memory data partitioning algorithm for fMRI processing
Implement critical path algorithms in fMRI processing like correlation, registration into Resilient Distributed Dataset functions on Spark
Integrate the Spark code on cluster management platform with neuroimaging management software (XNAT)
skhskdk
