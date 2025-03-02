# Stata schemes

In this folder are various new Stata schemes. The schemes have been programmed in three flavors: **white**, **black**, and **grey (gg)**. As the names suggest, these are the background colors, where the last one is inspired by the [ggplot2](https://ggplot2.tidyverse.org/) scheme in R.

These schemes are procedurally generated where the colors and other information is introduced in the schemes via scripts. The core white scheme is based on the [Cleanplots theme](https://www.trentonmize.com/software/cleanplots) (Mize 2018) that itself is derived from the [plainplots theme](https://www.stata.com/meeting/switzerland16/slides/bischof-switzerland16.pdf) (Bischof 2017). Most of the elements have been overwritten but the simple structure of the dotted grid lines and the axis colors is maintained. I really like these features! The colors have been passed on to the scheme using Ben Jann's [colorpalette](http://repec.sowi.unibe.ch/stata/palettes/index.html) package (Jann 2018).

Since the schemes are scripted, this folder will be filled up with various schemes over time. It is also likely some schemes go through minor adjustments since not all possible graph combinations have been tested. Names and installation paths might change. Please check here for the updates.

* The dofile contains the script to test the code.
* The graph folder contains the high resolution sample figures.

Link to the Medium article that describes these schemes: [Stata graph schemes by The Stata Guide](https://medium.com/the-stata-guide/stata-schemes-5ef99d099585)


## How to use the schemes:

The dofile in the folder can be copied and executed in Stata. Otherwise:

Check the installation:
```
net d tsg_schemes, from("https://raw.githubusercontent.com/asjadnaqvi/Stata-schemes/main/schemes/")
```

Install the schemes:
```
net install tsg_schemes, from("https://raw.githubusercontent.com/asjadnaqvi/Stata-schemes/main/schemes/") replace
```

You can try various graphs either using this test data set:
```
use "https://github.com/asjadnaqvi/Stata-schemes/blob/main/scheme_test.dta?raw=true", clear
```

or use your own dataset!

Please report errors or bugs or suggestions to improve the schemes. Several new schemes coming soon!

### Change log
* 16 April 2021: Very minor fixes to some colors. Histograms fixed and added to the graphs. Following schemes added: **brbg**, **piyg**, **ptol**, **jet**, **w3d**
* 08 April 2021: Repository created with pkg file and the following schemes added: **tableau**, **cividis**, **viridis**, **hue**


The figures drawn from various schemes are showcased below.


## Tableau color scheme

### white_tableau
<img src="./figures/scatter_white_tableau.png" height="200"><img src="./figures/line_white_tableau.png" height="200">
<img src="./figures/mlabel_white_tableau.png" height="200"><img src="./figures/bygraph_white_tableau.png" height="200">
<img src="./figures/bar_white_tableau.png" height="200"><img src="./figures/barh_white_tableau.png" height="200">
<img src="./figures/pie_white_tableau.png" height="200"><img src="./figures/density_white_tableau.png" height="200">
<img src="./figures/ci_white_tableau.png" height="200"><img src="./figures/rcap_white_tableau.png" height="200">
<img src="./figures/box_white_tableau.png" height="200"><img src="./figures/histogram_white_tableau.png" height="200">

### black_tableau
<img src="./figures/scatter_black_tableau.png" height="200"><img src="./figures/line_black_tableau.png" height="200">
<img src="./figures/mlabel_black_tableau.png" height="200"><img src="./figures/bygraph_black_tableau.png" height="200">
<img src="./figures/bar_black_tableau.png" height="200"><img src="./figures/barh_black_tableau.png" height="200">
<img src="./figures/pie_black_tableau.png" height="200"><img src="./figures/density_black_tableau.png" height="200">
<img src="./figures/ci_black_tableau.png" height="200"><img src="./figures/rcap_black_tableau.png" height="200">
<img src="./figures/box_black_tableau.png" height="200"><img src="./figures/histogram_black_tableau.png" height="200">

### gg_tableau
<img src="./figures/scatter_gg_tableau.png" height="200"><img src="./figures/line_gg_tableau.png" height="200">
<img src="./figures/mlabel_gg_tableau.png" height="200"><img src="./figures/bygraph_gg_tableau.png" height="200">
<img src="./figures/bar_gg_tableau.png" height="200"><img src="./figures/barh_gg_tableau.png" height="200">
<img src="./figures/pie_gg_tableau.png" height="200"><img src="./figures/density_gg_tableau.png" height="200">
<img src="./figures/ci_gg_tableau.png" height="200"><img src="./figures/rcap_gg_tableau.png" height="200">
<img src="./figures/box_gg_tableau.png" height="200"><img src="./figures/histogram_gg_tableau.png" height="200">


## Cividis color scheme

### white_cividis
<img src="./figures/scatter_white_cividis.png" height="200"><img src="./figures/line_white_cividis.png" height="200">
<img src="./figures/mlabel_white_cividis.png" height="200"><img src="./figures/bygraph_white_cividis.png" height="200">
<img src="./figures/bar_white_cividis.png" height="200"><img src="./figures/barh_white_cividis.png" height="200">
<img src="./figures/pie_white_cividis.png" height="200"><img src="./figures/density_white_cividis.png" height="200">
<img src="./figures/ci_white_cividis.png" height="200"><img src="./figures/rcap_white_cividis.png" height="200">
<img src="./figures/box_white_cividis.png" height="200"><img src="./figures/histogram_white_cividis.png" height="200">

### black_cividis
<img src="./figures/scatter_black_cividis.png" height="200"><img src="./figures/line_black_cividis.png" height="200">
<img src="./figures/mlabel_black_cividis.png" height="200"><img src="./figures/bygraph_black_cividis.png" height="200">
<img src="./figures/bar_black_cividis.png" height="200"><img src="./figures/barh_black_cividis.png" height="200">
<img src="./figures/pie_black_cividis.png" height="200"><img src="./figures/density_black_cividis.png" height="200">
<img src="./figures/ci_black_cividis.png" height="200"><img src="./figures/rcap_black_cividis.png" height="200">
<img src="./figures/box_black_cividis.png" height="200"><img src="./figures/histogram_black_cividis.png" height="200">

### gg_cividis
<img src="./figures/scatter_gg_cividis.png" height="200"><img src="./figures/line_gg_cividis.png" height="200">
<img src="./figures/mlabel_gg_cividis.png" height="200"><img src="./figures/bygraph_gg_cividis.png" height="200">
<img src="./figures/bar_gg_cividis.png" height="200"><img src="./figures/barh_gg_cividis.png" height="200">
<img src="./figures/pie_gg_cividis.png" height="200"><img src="./figures/density_gg_cividis.png" height="200">
<img src="./figures/ci_gg_cividis.png" height="200"><img src="./figures/rcap_gg_cividis.png" height="200">
<img src="./figures/box_gg_cividis.png" height="200"><img src="./figures/histogram_gg_cividis.png" height="200">

## Viridis color scheme

### white_viridis
<img src="./figures/scatter_white_viridis.png" height="200"><img src="./figures/line_white_viridis.png" height="200">
<img src="./figures/mlabel_white_viridis.png" height="200"><img src="./figures/bygraph_white_viridis.png" height="200">
<img src="./figures/bar_white_viridis.png" height="200"><img src="./figures/barh_white_viridis.png" height="200">
<img src="./figures/pie_white_viridis.png" height="200"><img src="./figures/density_white_viridis.png" height="200">
<img src="./figures/ci_white_viridis.png" height="200"><img src="./figures/rcap_white_viridis.png" height="200">
<img src="./figures/box_white_viridis.png" height="200"><img src="./figures/histogram_white_viridis.png" height="200">

### black_viridis
<img src="./figures/scatter_black_viridis.png" height="200"><img src="./figures/line_black_viridis.png" height="200">
<img src="./figures/mlabel_black_viridis.png" height="200"><img src="./figures/bygraph_black_viridis.png" height="200">
<img src="./figures/bar_black_viridis.png" height="200"><img src="./figures/barh_black_viridis.png" height="200">
<img src="./figures/pie_black_viridis.png" height="200"><img src="./figures/density_black_viridis.png" height="200">
<img src="./figures/ci_black_viridis.png" height="200"><img src="./figures/rcap_black_viridis.png" height="200">
<img src="./figures/box_black_viridis.png" height="200"><img src="./figures/histogram_black_viridis.png" height="200">

### gg_viridis
<img src="./figures/scatter_gg_viridis.png" height="200"><img src="./figures/line_gg_viridis.png" height="200">
<img src="./figures/mlabel_gg_viridis.png" height="200"><img src="./figures/bygraph_gg_viridis.png" height="200">
<img src="./figures/bar_gg_viridis.png" height="200"><img src="./figures/barh_gg_viridis.png" height="200">
<img src="./figures/pie_gg_viridis.png" height="200"><img src="./figures/density_gg_viridis.png" height="200">
<img src="./figures/ci_gg_viridis.png" height="200"><img src="./figures/rcap_gg_viridis.png" height="200">
<img src="./figures/box_gg_viridis.png" height="200"><img src="./figures/histogram_gg_viridis.png" height="200">


## Hue color scheme (default ggplot2 colors)

### white_hue
<img src="./figures/scatter_white_hue.png" height="200"><img src="./figures/line_white_hue.png" height="200">
<img src="./figures/mlabel_white_hue.png" height="200"><img src="./figures/bygraph_white_hue.png" height="200">
<img src="./figures/bar_white_hue.png" height="200"><img src="./figures/barh_white_hue.png" height="200">
<img src="./figures/pie_white_hue.png" height="200"><img src="./figures/density_white_hue.png" height="200">
<img src="./figures/ci_white_hue.png" height="200"><img src="./figures/rcap_white_hue.png" height="200">
<img src="./figures/box_white_hue.png" height="200"><img src="./figures/histogram_white_hue.png" height="200">

### black_hue
<img src="./figures/scatter_black_hue.png" height="200"><img src="./figures/line_black_hue.png" height="200">
<img src="./figures/mlabel_black_hue.png" height="200"><img src="./figures/bygraph_black_hue.png" height="200">
<img src="./figures/bar_black_hue.png" height="200"><img src="./figures/barh_black_hue.png" height="200">
<img src="./figures/pie_black_hue.png" height="200"><img src="./figures/density_black_hue.png" height="200">
<img src="./figures/ci_black_hue.png" height="200"><img src="./figures/rcap_black_hue.png" height="200">
<img src="./figures/box_black_hue.png" height="200"><img src="./figures/histogram_black_hue.png" height="200">

### gg_hue
<img src="./figures/scatter_gg_hue.png" height="200"><img src="./figures/line_gg_hue.png" height="200">
<img src="./figures/mlabel_gg_hue.png" height="200"><img src="./figures/bygraph_gg_hue.png" height="200">
<img src="./figures/bar_gg_hue.png" height="200"><img src="./figures/barh_gg_hue.png" height="200">
<img src="./figures/pie_gg_hue.png" height="200"><img src="./figures/density_gg_hue.png" height="200">
<img src="./figures/ci_gg_hue.png" height="200"><img src="./figures/rcap_gg_hue.png" height="200">
<img src="./figures/box_gg_hue.png" height="200"><img src="./figures/histogram_gg_hue.png" height="200">


## brbg color scheme 

### white_brbg
<img src="./figures/scatter_white_brbg.png" height="200"><img src="./figures/line_white_brbg.png" height="200">
<img src="./figures/mlabel_white_brbg.png" height="200"><img src="./figures/bygraph_white_brbg.png" height="200">
<img src="./figures/bar_white_brbg.png" height="200"><img src="./figures/barh_white_brbg.png" height="200">
<img src="./figures/pie_white_brbg.png" height="200"><img src="./figures/density_white_brbg.png" height="200">
<img src="./figures/ci_white_brbg.png" height="200"><img src="./figures/rcap_white_brbg.png" height="200">
<img src="./figures/box_white_brbg.png" height="200"><img src="./figures/histogram_white_brbg.png" height="200">

### black_brbg
<img src="./figures/scatter_black_brbg.png" height="200"><img src="./figures/line_black_brbg.png" height="200">
<img src="./figures/mlabel_black_brbg.png" height="200"><img src="./figures/bygraph_black_brbg.png" height="200">
<img src="./figures/bar_black_brbg.png" height="200"><img src="./figures/barh_black_brbg.png" height="200">
<img src="./figures/pie_black_brbg.png" height="200"><img src="./figures/density_black_brbg.png" height="200">
<img src="./figures/ci_black_brbg.png" height="200"><img src="./figures/rcap_black_brbg.png" height="200">
<img src="./figures/box_black_brbg.png" height="200"><img src="./figures/histogram_black_brbg.png" height="200">

### gg_brbg
<img src="./figures/scatter_gg_brbg.png" height="200"><img src="./figures/line_gg_brbg.png" height="200">
<img src="./figures/mlabel_gg_brbg.png" height="200"><img src="./figures/bygraph_gg_brbg.png" height="200">
<img src="./figures/bar_gg_brbg.png" height="200"><img src="./figures/barh_gg_brbg.png" height="200">
<img src="./figures/pie_gg_brbg.png" height="200"><img src="./figures/density_gg_brbg.png" height="200">
<img src="./figures/ci_gg_brbg.png" height="200"><img src="./figures/rcap_gg_brbg.png" height="200">
<img src="./figures/box_gg_brbg.png" height="200"><img src="./figures/histogram_gg_brbg.png" height="200">


## piyg color scheme

### white_piyg
<img src="./figures/scatter_white_piyg.png" height="200"><img src="./figures/line_white_piyg.png" height="200">
<img src="./figures/mlabel_white_piyg.png" height="200"><img src="./figures/bygraph_white_piyg.png" height="200">
<img src="./figures/bar_white_piyg.png" height="200"><img src="./figures/barh_white_piyg.png" height="200">
<img src="./figures/pie_white_piyg.png" height="200"><img src="./figures/density_white_piyg.png" height="200">
<img src="./figures/ci_white_piyg.png" height="200"><img src="./figures/rcap_white_piyg.png" height="200">
<img src="./figures/box_white_piyg.png" height="200"><img src="./figures/histogram_white_piyg.png" height="200">

### black_piyg
<img src="./figures/scatter_black_piyg.png" height="200"><img src="./figures/line_black_piyg.png" height="200">
<img src="./figures/mlabel_black_piyg.png" height="200"><img src="./figures/bygraph_black_piyg.png" height="200">
<img src="./figures/bar_black_piyg.png" height="200"><img src="./figures/barh_black_piyg.png" height="200">
<img src="./figures/pie_black_piyg.png" height="200"><img src="./figures/density_black_piyg.png" height="200">
<img src="./figures/ci_black_piyg.png" height="200"><img src="./figures/rcap_black_piyg.png" height="200">
<img src="./figures/box_black_piyg.png" height="200"><img src="./figures/histogram_black_piyg.png" height="200">

### gg_piyg
<img src="./figures/scatter_gg_piyg.png" height="200"><img src="./figures/line_gg_piyg.png" height="200">
<img src="./figures/mlabel_gg_piyg.png" height="200"><img src="./figures/bygraph_gg_piyg.png" height="200">
<img src="./figures/bar_gg_piyg.png" height="200"><img src="./figures/barh_gg_piyg.png" height="200">
<img src="./figures/pie_gg_piyg.png" height="200"><img src="./figures/density_gg_piyg.png" height="200">
<img src="./figures/ci_gg_piyg.png" height="200"><img src="./figures/rcap_gg_piyg.png" height="200">
<img src="./figures/box_gg_piyg.png" height="200"><img src="./figures/histogram_gg_piyg.png" height="200">


## ptol color scheme

### white_ptol
<img src="./figures/scatter_white_ptol.png" height="200"><img src="./figures/line_white_ptol.png" height="200">
<img src="./figures/mlabel_white_ptol.png" height="200"><img src="./figures/bygraph_white_ptol.png" height="200">
<img src="./figures/bar_white_ptol.png" height="200"><img src="./figures/barh_white_ptol.png" height="200">
<img src="./figures/pie_white_ptol.png" height="200"><img src="./figures/density_white_ptol.png" height="200">
<img src="./figures/ci_white_ptol.png" height="200"><img src="./figures/rcap_white_ptol.png" height="200">
<img src="./figures/box_white_ptol.png" height="200"><img src="./figures/histogram_white_ptol.png" height="200">

### black_ptol
<img src="./figures/scatter_black_ptol.png" height="200"><img src="./figures/line_black_ptol.png" height="200">
<img src="./figures/mlabel_black_ptol.png" height="200"><img src="./figures/bygraph_black_ptol.png" height="200">
<img src="./figures/bar_black_ptol.png" height="200"><img src="./figures/barh_black_ptol.png" height="200">
<img src="./figures/pie_black_ptol.png" height="200"><img src="./figures/density_black_ptol.png" height="200">
<img src="./figures/ci_black_ptol.png" height="200"><img src="./figures/rcap_black_ptol.png" height="200">
<img src="./figures/box_black_ptol.png" height="200"><img src="./figures/histogram_black_ptol.png" height="200">

### gg_ptol
<img src="./figures/scatter_gg_ptol.png" height="200"><img src="./figures/line_gg_ptol.png" height="200">
<img src="./figures/mlabel_gg_ptol.png" height="200"><img src="./figures/bygraph_gg_ptol.png" height="200">
<img src="./figures/bar_gg_ptol.png" height="200"><img src="./figures/barh_gg_ptol.png" height="200">
<img src="./figures/pie_gg_ptol.png" height="200"><img src="./figures/density_gg_ptol.png" height="200">
<img src="./figures/ci_gg_ptol.png" height="200"><img src="./figures/rcap_gg_ptol.png" height="200">
<img src="./figures/box_gg_ptol.png" height="200"><img src="./figures/histogram_gg_ptol.png" height="200">


## jet color scheme

### white_jet
<img src="./figures/scatter_white_jet.png" height="200"><img src="./figures/line_white_jet.png" height="200">
<img src="./figures/mlabel_white_jet.png" height="200"><img src="./figures/bygraph_white_jet.png" height="200">
<img src="./figures/bar_white_jet.png" height="200"><img src="./figures/barh_white_jet.png" height="200">
<img src="./figures/pie_white_jet.png" height="200"><img src="./figures/density_white_jet.png" height="200">
<img src="./figures/ci_white_jet.png" height="200"><img src="./figures/rcap_white_jet.png" height="200">
<img src="./figures/box_white_jet.png" height="200"><img src="./figures/histogram_white_jet.png" height="200">

### black_jet
<img src="./figures/scatter_black_jet.png" height="200"><img src="./figures/line_black_jet.png" height="200">
<img src="./figures/mlabel_black_jet.png" height="200"><img src="./figures/bygraph_black_jet.png" height="200">
<img src="./figures/bar_black_jet.png" height="200"><img src="./figures/barh_black_jet.png" height="200">
<img src="./figures/pie_black_jet.png" height="200"><img src="./figures/density_black_jet.png" height="200">
<img src="./figures/ci_black_jet.png" height="200"><img src="./figures/rcap_black_jet.png" height="200">
<img src="./figures/box_black_jet.png" height="200"><img src="./figures/histogram_black_jet.png" height="200">

### gg_jet
<img src="./figures/scatter_gg_jet.png" height="200"><img src="./figures/line_gg_jet.png" height="200">
<img src="./figures/mlabel_gg_jet.png" height="200"><img src="./figures/bygraph_gg_jet.png" height="200">
<img src="./figures/bar_gg_jet.png" height="200"><img src="./figures/barh_gg_jet.png" height="200">
<img src="./figures/pie_gg_jet.png" height="200"><img src="./figures/density_gg_jet.png" height="200">
<img src="./figures/ci_gg_jet.png" height="200"><img src="./figures/rcap_gg_jet.png" height="200">
<img src="./figures/box_gg_jet.png" height="200"><img src="./figures/histogram_gg_jet.png" height="200">


## w3d color scheme

### white_w3d
<img src="./figures/scatter_white_w3d.png" height="200"><img src="./figures/line_white_w3d.png" height="200">
<img src="./figures/mlabel_white_w3d.png" height="200"><img src="./figures/bygraph_white_w3d.png" height="200">
<img src="./figures/bar_white_w3d.png" height="200"><img src="./figures/barh_white_w3d.png" height="200">
<img src="./figures/pie_white_w3d.png" height="200"><img src="./figures/density_white_w3d.png" height="200">
<img src="./figures/ci_white_w3d.png" height="200"><img src="./figures/rcap_white_w3d.png" height="200">
<img src="./figures/box_white_w3d.png" height="200"><img src="./figures/histogram_white_w3d.png" height="200">

### black_w3d
<img src="./figures/scatter_black_w3d.png" height="200"><img src="./figures/line_black_w3d.png" height="200">
<img src="./figures/mlabel_black_w3d.png" height="200"><img src="./figures/bygraph_black_w3d.png" height="200">
<img src="./figures/bar_black_w3d.png" height="200"><img src="./figures/barh_black_w3d.png" height="200">
<img src="./figures/pie_black_w3d.png" height="200"><img src="./figures/density_black_w3d.png" height="200">
<img src="./figures/ci_black_w3d.png" height="200"><img src="./figures/rcap_black_w3d.png" height="200">
<img src="./figures/box_black_w3d.png" height="200"><img src="./figures/histogram_black_w3d.png" height="200">

### gg_w3d
<img src="./figures/scatter_gg_w3d.png" height="200"><img src="./figures/line_gg_w3d.png" height="200">
<img src="./figures/mlabel_gg_w3d.png" height="200"><img src="./figures/bygraph_gg_w3d.png" height="200">
<img src="./figures/bar_gg_w3d.png" height="200"><img src="./figures/barh_gg_w3d.png" height="200">
<img src="./figures/pie_gg_w3d.png" height="200"><img src="./figures/density_gg_w3d.png" height="200">
<img src="./figures/ci_gg_w3d.png" height="200"><img src="./figures/rcap_gg_w3d.png" height="200">
<img src="./figures/box_gg_w3d.png" height="200"><img src="./figures/histogram_gg_w3d.png" height="200">




