# FLIMimage_Matlab_ScanImage
This is a FLIM sofware for Matlab based on ScanImage.
Should run on Matlab 2014 or earlier. 

* The software has been used in the Yasuda lab, but the lab has switched to C# based software: 
https://github.com/ryoheiyasuda/FLIMage_public

* Developed in the Yasuda lab (Max Planck Florida Institute), 
and its variants are also used in James McNamara's lab (Duke) Bernardo Sabatini's lab (Harvard), Haining Zhong's lab (Vollum), 
Karen Zito's lab (UC Davis).

* To use this software, download ScanImage 3.8.1 from Vidrio Technologies 
https://vidriotechnologies.com/download-scanimage/

* This software is distributed "as is" and we will not take any responsibility. The patch was tested in our computer and it worked. 

* You can apply patch in unix-like shell (like Mingw for Windows http://mingw-w64.org/doku.php): 

  >> cd SCANIMAGE_r3.8.1

  >> patch -p1 -i <PATH>\flimage_patch.patch
