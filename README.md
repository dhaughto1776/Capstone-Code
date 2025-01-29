# Burn Scar Geospatial Foundation Model

## Description
This projects purpose was to analyse the light curve and spectral properties of 2 subtypes of type Ia Supernova, 03fg and 02es, in an attempt to link their elusive and poorly understood explosion mechanisms.
Using Zwicky Transient Facility and Asteroid Terrestrial Impact last alert system (ATLAS) data, along with George GP regression, Piscola supernova light curve fitting, and self deveopled Gaussian fitting 
processes, the light curves were analysed:

1) To see if they possessed an excess in their flux prior to explosion, a defining characteristic of the two subtypes, and one unique to them so far,
   indicative of an interaction with a circumstellar carbon envelope.
2) To then find the Δm₁₅, or luminosity decline rate, how much the luminosity declines after 15 days
3) To find the pEW, or pesudo equivalent width, of Carbon II at 6580 Å
4) To then investigate a potential relationship between these 2 parameters through plotting, to see if there is a link in their explosion mechanisms
5) 
## Installation
This project was done on Jupyter Notebooks in Google Colab, and as such, simply downloading the .ipynb file and uploading to Google colab will allow for full use of the code shown. Further 
information and the source code can be found on the ZTF, George and Piscola pages:

George: https://github.com/dfm/george/blob/main/docs/tutorials/first.rst

Piscola: https://piscola.readthedocs.io/en/latest/further_information/supernova.html

ZTF data: https://github.com/MickaelRigault/ztfidr

All of this is open source.

### Use
As stated, by downloading the .ipynb file and uploading it to Colab, it can be used. However, data from ZTF as a zip file needs to be downloaded from the above page.
Furthermore, for using Piscola, ATLAS data is needed. By taking the ZTF name of the SN of interest, its RA (ight Ascension), and its Declination, and going to:

https://fallingstar-data.com/forcedphot/

you can get this data, and use the 'File Maker code'
Some points to note about using this specific file:

Sometimes an error message will appear pertaining to u.deg units. By simply re-running the 'imports' tab, this will be fixed
 

Thanks to my supervisor, Professor Kate Maguire, for all her help throughout the project. Thanks also to Tomás E. Müller, for all his help in the use of Piscola, his light curve fitting module.
