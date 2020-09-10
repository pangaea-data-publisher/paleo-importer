# Paleoenvironmental Standard Terms (PaST) Thesaurus Importer
A python script that imports 'method' controlled vocabularies from https://www.ncdc.noaa.gov/paleo-search/cvterms, and then insert/update the terms into the pangaea database.

## Usage
To run the importer, please execute the following from the root directory. Please update config/import_template.ini with the pangaea database settings (username, password, host, port).
```
pip3 install -r requirements.txt
python3 harvester.py
```
