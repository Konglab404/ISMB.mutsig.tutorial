# ISMB.mutsig.tutorial

Welcome to the ISMB2020 Online Mutational Signature Analysis Tutorial, July 11 and 12, 2020 (https://www.iscb.org/ismb2020-program/tutorials#tut1)

## Please do before the tutorial

1. Please have R >= 4.0.0 installed on your computer.

2. Please install the CRAN package ICAMS and its prerequisites.
```
install.packages("ICAMS")
```

3. Please install BSgenome.Hsapiens.1000genomes.hs37d5 from Bioconductor:
```
install.packages("BiocManager")
BiocManager::install("BSgenome.Hsapiens.1000genomes.hs37d5")
```
4. Additional R libraries that will be needed:

4.1 CRAN packages philentropy, gplots, factoextra

4.2 GitHub packages:  
To install R packages from GitHub, you will need development tool to build the
package from source file.

**Windows:**   
Please download and install Rtools from CRAN: https://cran.rstudio.com/bin/windows/Rtools/.  

**macOS:**   
Please install the Command Line Tools for XCode. You can do this in one of two ways. 

Either:

1. Download and install XCode from the Mac AppStore:
http://itunes.apple.com/us/app/xcode/id497799835?mt=12 

2. Within XCode go to Preferences : Downloads and install the Command Line Tools

Or alternatively (for a smaller download size):

1. Register as an Apple Developer (free) here: https://developer.apple.com/programs/register/

2. Download the Command Line Tools for XCode appropriate for the version of macOS you are running from here: https://developer.apple.com/downloads/  

**Linux:**    
For Debian/Ubuntu, you can install the development utilities required by executing:

```
sudo apt-get install r-base-dev
```
For other versions of Linux please consult their documentation to determine how to install a basic GNU development tool chain.   

After you have installed the development tool, you can install the GitHub
packages with the R command line:
```
remotes::install_github("steverozen/mSigBG", ref = "1.0-branch", force = TRUE)
remotes::install_github("steverozen/PCAWG7", force = TRUE)
```

If you have difficulties contact Nanhai JIANG at nanhai.jiang@u.duke.nus.edu.

You will need R and the above packages for the practicum on July 11. 

The practicum inputs are at https://github.com/steverozen/ISMB.mutsig.tutorial/raw/master/ISMB.mutational.sigatures.practicum.zip. 

The slides are:

0. https://github.com/steverozen/ISMB.mutsig.tutorial/raw/master/Tut1.Lecture.0.short.intro.pptx
1. https://github.com/steverozen/ISMB.mutsig.tutorial/raw/master/Tut1.Lecture.1.Mutational-Signatures%202020_07_10.pptx
2. https://github.com/steverozen/ISMB.mutsig.tutorial/raw/master/Tut1.Lecture.2.data-mining.NMF.and.HPD.2020.07.10.pptx
3. https://github.com/steverozen/ISMB.mutsig.tutorial/raw/master/Tut1.lecture.3.landscape_tactics_20200710.pptx

