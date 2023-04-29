# 2023 ASNR AI workshop - Data annotation and curation
## 3D-Slicer customized GUI for annotation

<p align="center">
  <img src="https://user-images.githubusercontent.com/48111184/145217094-d4f5716e-d110-4d1f-aa96-9cc9669aca35.jpg" />
</p>

# Useful 3D Slicer Documentation
## Python programing in Slicer
- [Slicer Programming Tutorial](https://spujol.github.io/SlicerProgrammingTutorial/)
- [Beyond the basics programming](https://www.slicer.org/w/img_auth.php/7/79/SlicerModulesProgrammingBeyondBasics.pdf)
- [Python script repository](https://slicer.readthedocs.io/en/latest/developer_guide/script_repository.html)

## Slicer Jupyter
- [Overview on github](https://github.com/Slicer/SlicerJupyter)
- [Jupyter notebook examples](https://github.com/Slicer/SlicerNotebooks)
- [Other segmentation examples](https://gist.github.com/lassoan)

## Slicer module 
- [Basic Python module (Hello python)](https://www.slicer.org/w/img_auth.php/c/c0/Slicer4_ProgrammingTutorial_Slicer4.5.pdf)
- [Robarts lab documentation](https://www.robarts.ca/computerassistedsurgery/create_your_own/index.html) including well documented [example](https://github.com/lgroves6/SlicerIGTDevelopment/blob/master/YourModuleName.py) 
- [PerkLab python module development tutorial (includes Qt designer)](https://www.slicer.org/wiki/Documentation/Nightly/Training#Tutorials_for_software_developers)
- [Developing and contributing extensions for 3D Slicer](https://docs.google.com/presentation/d/1JXIfs0rAM7DwZAho57Jqz14MRn2BIMrjB17Uj_7Yztc/edit#slide=id.g41f90baec_028)

## Videos and other ressources
- [Short series showing basic python programming and module development (in German with subtitles)](https://youtube.com/playlist?list=PLJWCUXz3GeAfmYLiFcKus_c0jcsMnVsgb)
- [Homemade videos and example](https://www.dropbox.com/sh/rukkctbdxa9ctra/AADr2e8T8X69Y1dAXxeNmBtba?dl=0)

## Python module examples
- [Robarts lab good baseline code (without .ui file)](https://github.com/lgroves6/SlicerIGTDevelopment/blob/master/YourModuleName.py)
- [Slicer Case Iterator](https://github.com/JoostJM/SlicerCaseIterator): iterate through cases 
- [HCC Slicer Case Iterator (long code !)](https://github.com/bsmarine/SlicerHCCMRICaseIterator)


# TODO
- Create a module for initial annotations +/- using CNN predictions (e.g. 2D UNet), similar to [BRaTs 2021 methodology](https://arxiv.org/abs/2107.02314)
- Create a module for segmentation review, create a new version of corrected segmentation to be used as groundthruth