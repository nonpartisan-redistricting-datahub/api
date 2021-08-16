# API
This repo contains two files:

1. Jupyter notebook with API retrieval script (RDH_API.ipynb).
2. README from GreenInfo (our web developers) with additional information on the WordPress API (Download_API.txt).

The jupyter notebook in this repo can be used to extract data from the RDH API. Designated API users can "Run All" and fill out the prompts as needed (e.g. username, password, states of interest, filtering paramters, etc.). The script uses pandas, requests, io, numpy, and getpass libraries. If you do not have these on your system, you may need to install them. You should not have to modify any of the code to retrieve data from the API, which will be extracted to the directory in which this script is housed on your system. You must be a designated API user by RDH in order for the script to work, this is a different status than a normal, verified account. Due to limitations of WordPress API, you can only download data by ~4 states at a time at most, as the the API will only pull a list of 1,000 potential datasets for download at a time.

The notebook uses pandas version 1.2.4, requests version 2.25.1, and numpy version 1.20.1. The script may run on different versions, but if you are receiving an import error, try installing these versions.

 Please note that there is additional information about datasets on our website: redistrictingdatahub.org. Should you be interested in this information, please navigate to your state(s) of interest and then desired dataset(s).

If you have any questions or requests about/for the script, accessing RDH data, or becoming a designated API user, please contact info@redistrictingdatahub.org. 
