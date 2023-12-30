## DRPD dataset
DRPD dataset contained 5,372 RGB sub-images cropped from raw aerial imagery taken at three different altitudes, i.e. GSD7m, GSD12m, and GSD20m. In total, DRPD included 259,498 labeled rice panicles with varied morphological features collected at four key growth stages: heading (1,903 sub-images), flowering (1,676 sub-images), early grain filling (1,235 sub-images), and middle grain filling (558 sub-images). 


•   The DRPD dataset consisted of: 

|   GSD | Images | Labels | panicles per sub-image |
| :----: | :----: | :----: | :----: |
| GSD<sub>7m</sub> | 3,810 | 106,878 | 27-30 | 
| GSD<sub>12m</sub> | 1004 | 71,404 | 65-70 |
| GSD<sub>20m</sub> | 558 | 81,216 | 140-150 |


## Install Python, Anaconda and Libraries
If you wish to run Panicle-AI from source code, you will need to set up Python on your operating system. 

1. Install Python releases:
   
   •	Read the beginner’s guide to Python if you are new to the language: 
   https://wiki.python.org/moin/BeginnersGuide
   
   •	For Windows users, Python 3 release can be downloaded via: 
   https://www.python.org/downloads/windows/
   
   •	Panicle-AI only supports Python 3 onwards

2. Install Anaconda Python distribution:
   
   •	Read the install instruction using the URL: https://docs.continuum.io/anaconda/install
   
   •	For Windows users, a detailed step-by-step installation guide can be found via: 
   https://docs.continuum.io/anaconda/install/windows 
   
   •	An Anaconda Graphical installer can be found via: 
   https://www.continuum.io/downloads

   •	We recommend users install the latest Anaconda Python distribution

3. Install packages:

   •  Panicle-AI uses a number of 3rd-party libraries that you may need to add to your conda environment.
   
         matplotlib>=3.2.2
         numpy>=1.18.5
         opencv-python>=4.1.2
         Pillow>=7.1.2
         PyYAML>=5.3.1
         requests>=2.23.0
         scipy>=1.4.1
         torch>=1.7.0
         torchvision>=0.8.1
         tqdm>=4.41.0
         tensorboard>=2.4.1
         pandas>=1.1.4
         seaborn>=0.11.0
    •  You can get the required environment through the following :

         pip install requirement.txt

   
