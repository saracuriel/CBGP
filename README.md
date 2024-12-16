Jupyter notebooks with Python 3 scripts with different aims:

1- "get_author_publications.ipynb" gets information for a certain researcher, in a way that only their ORCID is needed. 
Information about the author's works is retrieved using the ORCID API and saved to a JSON file in the local directory ("works.json"). 
That file is then parsed to obtain information about the year of publication, DOI and title of each work and save it to a CSV file ("publications.csv").

2A- "get_affiliation_scopus.ipynb" gets affiliation data from the publications data obtained with script 1. 
Not much info is retrieved. It saves the data to a CSV file ("affiliation_data.csv"). 

2B- "get_affiliation_openaire_ror.ipynb" also gets information about affiliations for the data retrieved with script 1. 
This path gets much more information than the script 2A. Also, a second part is implemented to get the ROR IDs for the different institutions, using the ROR API. 
General information about the institutions is saved in CSV format ("affiliations.csv"), while the ROR IDs, latitude and longitude are saved to another CSV file ("affiliation_ror.csv")






   
   
