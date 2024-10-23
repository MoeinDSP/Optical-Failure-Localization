# Optical-Failure-Localization

This project aims to localize soft failures in an optical network comprising four nodes connected in
series, creating three links (Figure 1.1). Each node has a monitor at its input port that provides OSNR
(Optical Signal-to-Noise Ratio) samples. A fault can happen at any of the three links, and our objective
is to determine the faulty link. Hence, we use the OSNR values to determine key features, and train
machine-learning algorithms to localize the fault. Moreover, to be aware of the correctness of ML-based
decisions, we used Explainable AI (XAI). XAI techniques allow uncovering the reasoning behind the ML
model to a human expert, making ML models more trustable and, hence, more likely to be adopted
practically.


This repository contains in-class activities for the "Network Measurement and Data Analysis" course taught by [Prof. Redondi](https://scholar.google.com/citations?user=8ka5NmUAAAAJ&hl=en) and [Prof. Musumeci](https://scholar.google.it/citations?user=RsM0KB0AAAAJ&hl=it) at Politecnico di Milano.
