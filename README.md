# hierarchical-bootstrap-practice

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stephprince/hierarchical-bootstrap-practice/70d3b04?filepath=hierarchical-bootstrap-ripple-abundance-test.ipynb)

Press the Binder button above to launch the jupyter notebook!

This repository uses the code from the [Sober Lab Hierarchical Bootstrap Paper](https://github.com/soberlab/Hierarchical-Bootstrap-Paper) to test applying this analysis to Singer Lab 5XFAD electrophysiology data.

NOTE: this is in progress, and I need to verify that I'm using this approach correctly.

The main updates I've made can be found below:
  * uploading the long data format table of ripple abundance in 5XFAD and WT mice
  * changing the bootstrapping functions to be used with data stored in the long format 
  * adding a recursive function to perform the bootstrapping across any number of levels of hierarchical data
  * removing figures and simulation code that was in the paper but not necessary for applying the analysis to my data
