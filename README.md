# UpdateGNSSMetadata
Python script to update GNSS metadata fields

Intructions to run the script.
1. Install ArcGIS API for Python using Conda (https://developers.arcgis.com/python/guide/install-and-set-up/).
2. Once installed start command prompt (with adminstrator rights). 
3. Navigate to the directory where Anaconfa was installed to as part of step1.
4. Once under Anaconda directory type python keyword to check if python has been installed correctly.
5. To run the script type (Example)
6. C:\Continuum\Anaconda3>python C:\Continuum\Anaconda3\Scripts\UpdateGNSSSMetadata.py -u nitroadmin -p nitroadmin -url https://nitro.maps.arcgis.com GNSSMetadataFields
7. Followed by the python keyword is the script location then there are the following optional parameters (but marked as required) -u username -p password -url org url and finally the search string.
8. help can be accessed via -h flag.


9. C:\Continuum\Anaconda3>python C:\Continuum\Anaconda3\Scripts\UpdateGNSSSMetadata.py -h
usage: Generate domains for GNSS metadata fields (FixType, StationId, Number of Satellites

positional arguments:
  itemId                List of ItemId

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        AGOL username
  -p PASSWORD, --password PASSWORD
                        AGOL password
  -url URL, --url URL   AGOL url
  -r REMOVE, --remove REMOVE
                        Set true if GNSS metadata fields need to be removed
