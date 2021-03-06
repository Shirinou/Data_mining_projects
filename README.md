# Data  Mining projects  (Python)

------------------------------------------------------------------------------
### 1. Crime rates in São Paulo state, Brazil

The aim is to obtain crime data in São Paulo state , Brazil.

Data is available at Civil state Police statistics site:  http://www.ssp.sp.gov.br/Estatistica/Pesquisa.aspx   

Obs.: Crime type interpretation manual available (only in brazilian  portuguese) at: http://www.ssp.sp.gov.br/Estatistica/download/manual.pdf

Since there is no API or JSON file available in the website, I scrapped data and created 3 complete datasetsin Python.

Part 1 - Data extraction via webscrapping  using Selenium library, to navigate through the pages and extract data, and Pandas library to create and deal with dataframes from the scrapped data, including the crime types, year, city and region.
 Data available until march 2020. see project folder. 
 
 <img width="956" alt="ssp-fig" src="https://user-images.githubusercontent.com/52055874/80321175-6c2d5600-87f1-11ea-9642-dbb6e8671ee3.png">
 
Part 2 (to be released soon) - maps


-----------------------------------------------------------------------------
### 1b) IBGE data tables   
(to be used in Part 2)

If you want to gather any table from the Brazilian Institute of Geography and Statistics - IBGE - site , I suggest using the PyIBGE module, developed by Renan Birck: https://github.com/renanbirck/pyibge

This module accesses the API from IBGe website:  http://api.sidra.ibge.gov.br/ 

After you download the module PyIBGE in a local folder, you have to add the folder path into the sys.path of your computer. So Python can identify this module via 'import' command as you work with it.

Command lines in Python:
      import sys
      sys.path.append(r'yourpath\pyIBGE')
      import pyIBGE

-----------------------------------------------------------------------------
### 2) FIPE table (Tabela FIPE)   

Webscrapping of Tabela FIPE data (no official  API available) , containing  average value of cars, trucks and motocycles. Values in brazilian Reais (BRL or R$).

-----------------------------------------------------------------------------


