# FLIMimage_Matlab_ScanImage
This is a FLIM sofware for Matlab based on ScanImage.
Should run on Matlab 2014 or earlier on Windows 7 or XP. 

* The software has been used in the Yasuda lab, but the lab has switched to C# based software: 
https://github.com/ryoheiyasuda/FLIMage_public

* Developed in the Yasuda lab (Max Planck Florida Institute), 
and its variants are also used in James McNamara's lab (Duke) Bernardo Sabatini's lab (Harvard), Haining Zhong's lab (Vollum), 
Karen Zito's lab (UC Davis).

* To use this software, download ScanImage 3.8.1 from Vidrio Technologies 
https://vidriotechnologies.com/download-scanimage/

* This software is distributed "as is" and we will not take any responsibility. The patch was tested on our computer, and it worked. The software is no longer actively maintained.

* You can apply the patch in a Unix-like shell (like Mingw for Windows http://mingw-w64.org/doku.php): 

  >> cd SCANIMAGE_r3.8.1

  >> patch -p1 -i <PATH>\flimage_patch.patch

* To run the software, after opening scanimage, type:

  >> spc_drawInit

* FLIM setup can be edited in

  >> spc_init

* Most recent FLIM DLL needs to be in the spc folder.

* The code is in the public domain (CC0). 

* References
  
Harward et al. (2016) Autocrine BDNF-TrkB signalling within a single dendritic spine. Nature 538:99–103. DOI: 
https://doi.org/10.1038/nature19766

Hedrick et al. (2016) Rho GTPase complementation 
underlies BDNF-dependent homo- and heterosynaptic plasticity. Nature 538:104–108. DOI: https://doi.org/10.
1038/nature19784

Wang et al. (2025) Rab10 inactivation promotes AMPAR trafficking and spine enlargement during long-term potentiation. eLife. https://doi.org/10.7554/eLife.103879.3
   
