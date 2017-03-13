# psd_neutron_gamma

This project was created to demonstrate the possibility of using popular Machine Learning (ML) tools in Python Scikit-learn Library for nuclear science research. 

A long-standing step in the development of radiation detectors is the discrimination of photon (ie. gamma) particles from neutrons among the total particles detected by the detectors. Radioactive neutron sources often emit both neutrons and gammas. Neutron sources can be identified based on the energy of the emitted neutrons; however gamma emission is also detected and can mask the actual count of neutron events. A neutron detector must have a good way of distinguishing neutrons from gammas.
"Pulse shape discrimination" (PSD) is the general name of the process to distinguish neutron and gamma events. As a post-processing approach, PSD takes advantage of the different shapes of the detector output signal pulse for neutrons and gammas. The classification of particles can benefit from Machine Learning tools given the binary nature of the problem. 

In this project, the raw detector data are provided in files with extension ".h5". A training dataset is also provided, which contains neutron and gamma events identified via experiments. An unknown dataset is given which contains a mixture of neutron and gamma events. 

The demonstration code was written in Python2. 

To run the demonstration, download all files onto local hard-drive, and open the file "Helium-4 PSD using Machine Learning.ipynb" in Anaconda Jupyter2. 

NOTE: Due to large file size, the raw data file named "Cf_VG10_g2_t100_5min_1.h5" (used in "Helium-4 PSD using Machine Learning.ipynb") cannot be uploaded.
