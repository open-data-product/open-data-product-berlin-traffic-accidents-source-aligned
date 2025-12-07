
# Data Product Canvas - Berlin Traffic Accidents source-aligned

## Metadata

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-traffic-accidents-source-aligned
* license: CC-BY 4.0
* updated: 2025-11-10

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-traffic-accidents-2018-00
name: Strassenverkehrsunfälle nach Unfallort in Berlin 2018
* owner: Amt für Statistik Berlin-Brandenburg
* url: https://daten.berlin.de/datensaetze/strassenverkehrsunfalle-nach-unfallort-in-berlin-2018
* license: CC-BY-3.0-Namensnennung
* updated: 2021-08-13

**Files**

* [AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2018_Datensatz.csv](https://download.statistik-berlin-brandenburg.de/102d8fde949519f6/d99e618a1ec6/AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2018_Datensatz.csv)


### berlin-traffic-accidents-2019-00
name: Strassenverkehrsunfälle nach Unfallort in Berlin 2019
* owner: Amt für Statistik Berlin-Brandenburg
* url: https://daten.berlin.de/datensaetze/strassenverkehrsunfalle-nach-unfallort-in-berlin-2019
* license: CC-BY-3.0-Namensnennung
* updated: 2020-11-10

**Files**

* [AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2019_Datensatz.csv](https://download.statistik-berlin-brandenburg.de/8b666106e2a7b528/7c0c3db5ab9c/AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2019_Datensatz.csv)


### berlin-traffic-accidents-2020-00
name: Strassenverkehrsunfälle nach Unfallort in Berlin 2020
* owner: Amt für Statistik Berlin-Brandenburg
* url: https://daten.berlin.de/datensaetze/strassenverkehrsunfalle-nach-unfallort-in-berlin-2020
* license: CC-BY-3.0-Namensnennung
* updated: 2021-08-13

**Files**

* [AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2020_Datensatz.csv](https://download.statistik-berlin-brandenburg.de/8a7423663f039221/892d24383b99/AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2020_Datensatz.csv)


### berlin-traffic-accidents-2021-00
name: Strassenverkehrsunfälle nach Unfallort in Berlin 2021
* owner: Amt für Statistik Berlin-Brandenburg
* url: https://daten.berlin.de/datensaetze/strassenverkehrsunfalle-nach-unfallort-in-berlin-2021
* license: CC-BY-3.0-Namensnennung
* updated: 2020-11-10

**Files**

* [AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2021_Datensatz.csv](https://download.statistik-berlin-brandenburg.de/c2b6d25afa19b607/8d9164595b8b/AfSBBB_BE_LOR_Strasse_Strassenverkehrsunfaelle_2021_Datensatz.csv)


## Transformation Steps

* [Data extractor](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/extract/data_extractor.py) extracts data from inout ports
* [Data copier](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_converter.py) converts Excel files to CSV format

## Output Ports

### berlin-traffic-accidents-2018-00-csv
name: Berlin Traffic Accidents 2018 00 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2018-00-csv
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2018-00-details.csv](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2018-00-csv/berlin-traffic-accidents-2018-00-details.csv)


### berlin-traffic-accidents-2018-00-parquet
name: Berlin Traffic Accidents 2018 00 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2018-00-parquet
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2018-00-details.parquet](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2018-00-parquet/berlin-traffic-accidents-2018-00-details.parquet)


### berlin-traffic-accidents-2019-00-csv
name: Berlin Traffic Accidents 2019 00 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2019-00-csv
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2019-00-details.csv](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2019-00-csv/berlin-traffic-accidents-2019-00-details.csv)


### berlin-traffic-accidents-2019-00-parquet
name: Berlin Traffic Accidents 2019 00 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2019-00-parquet
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2019-00-details.parquet](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2019-00-parquet/berlin-traffic-accidents-2019-00-details.parquet)


### berlin-traffic-accidents-2020-00-csv
name: Berlin Traffic Accidents 2020 00 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2020-00-csv
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2020-00-details.csv](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2020-00-csv/berlin-traffic-accidents-2020-00-details.csv)


### berlin-traffic-accidents-2020-00-parquet
name: Berlin Traffic Accidents 2020 00 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2020-00-parquet
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2020-00-details.parquet](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2020-00-parquet/berlin-traffic-accidents-2020-00-details.parquet)


### berlin-traffic-accidents-2021-00-csv
name: Berlin Traffic Accidents 2021 00 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2021-00-csv
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2021-00-details.csv](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2021-00-csv/berlin-traffic-accidents-2021-00-details.csv)


### berlin-traffic-accidents-2021-00-parquet
name: Berlin Traffic Accidents 2021 00 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/tree/main/data/03-gold/berlin-traffic-accidents-2021-00-parquet
* license: CC-BY 4.0
* updated: 2025-11-10

**Files**

* [berlin-traffic-accidents-2021-00-details.parquet](https://raw.githubusercontent.com/open-data-product/open-lifeworlds-data-product-berlin-traffic-accidents-source-aligned/main/data/03-gold/berlin-traffic-accidents-2021-00-parquet/berlin-traffic-accidents-2021-00-details.parquet)


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).