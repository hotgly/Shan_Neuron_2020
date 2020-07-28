# Raw data depository for Yongli_Shan_et_al_Neuron2020

This repository contains raw data that was used in the research paper: <br>
Yongli Shan, John H. Abel, Yan Li, Mariko Izumo, Kimberly H. Cox, Byeongha Jeong, Seung-Hee Yoo, David P. Olson, Francis J. Doyle III, Joseph S. Takahashi. (2020) Dual-Color Single-Cell Imaging of the Suprachiasmatic Nucleus Reveals a Circadian Role in Network Synchrony. Neuron.

## Part1: SCN Imaging Data:
Includes five folders for the five genotypes analyzed in the article: VIP-Cre, VIP-<em>Bmal1<sup>-/-</sup></em>, AVP-Cre, AVP-<em>Bmal1<sup>-/-</sup></em> and VIP/AVP-<em>Bmal1<sup>-/-</sup></em>. And every subfolder contains imaging results of each SCN imaging experiment.

A dataset includes 14 files of three types:
| File Name suffix | Raw Data |
|----------------------|------------------------|
|`_signal.csv`|Bioluminescence signals of single cells|
|`_XY.csv`|X,Y locations of single cells |
|`_polygon.csv`|Contours of an SCN slice, left and right lobe|



Data analysis tools and code are available through another repository: <br>
Code for per2py data analysis https://github.com/johnabel/per2py


## Part2: Mouse behaviroal Data:
Includes four folders for the four categories of genotypes analyzed in the article: VIP-<em>Bmal1<sup>-/-</sup></em>, AVP-<em>Bmal1<sup>-/-</sup></em>, VIP/AVP-<em>Bmal1<sup>-/-</sup></em> and control. 

Behaviroal records were acquired with Clocklab and analyzed with Clocklab Analysis: https://www.actimetrics.com/products/clocklab/
