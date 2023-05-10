# czid-amr-heatmap
Prototype code for creating CZID-esque heatmap using AMR pipeline data

The current CZ ID AMR pipeline does not include heatmap functionality. This repository contains supporting scripts to generate heatmaps similar to those accessible in CZ ID, for AMR results.

The main functionality is `Make_AMR_Heatmap.ipynb`, which takes as input the  CZ ID `Combined AMR Report` for a particular pfoject (downloaded using bulk download functionality) and generates a heatmap with the options for filtering that mimic that of the CZ ID heatmaps.

There are 2 options for running the notebook...

1. Run locally, using jupyter notebooks; this requires local installation of jupyter and the associated packages

```
git clone https://github.com/katrinakalantar/czid-amr-heatmap.git
cd czid-amr-heatmap
jupyter notebook  # will open a notebook server
```

Then, select Make_AMR_Heatmap.ipynb to run, then run each cell of the notebook

2. Run via Google colab; this requires no dependency set-up on your part

* Navigate to https://colab.research.google.com/ (while signed into a Google chrome account)
* Select the option to access via "GitHub"
* Paste the GitHub link (https://github.com/katrinakalantar/czid-amr-heatmap) in the **Enter a GitHub URL** option
* Click `Make_AMR_Heatmap.ipynb` when the option is given
* Note: you will need to follow the "Google colab" instructions in the script for how to download data from CZ ID for access within the colab environment

