# FLIMimage_Matlab_ScanImage
This is a FLIM sofware for Matlab based on ScanImage.

* The software has been used in the Yasuda lab, but the lab switched to C# based software: 
https://github.com/ryoheiyasuda/FLIMage_public

* Developed in the Yasuda lab (Max Planck Florida Institute), 
and its variants are also used in James McNamara's lab (Duke) Bernardo Sabatini's lab (Harvard), Haining Zhong's lab (Vollum), 
Karen Zito's lab (UC Davis).

* To use this software, download ScanImage 3.8.1 from Vidrio Technologies 
https://vidriotechnologies.com/download-scanimage/

* Then apply patch like: 

  >> cd SCANIMAGE_r3.8.1

  >> patch -p1 -i <PATH>\flimage_patch.patch
