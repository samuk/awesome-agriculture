> [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re) A curated list of awesome open source technology for agriculture, farming and gardening. [Pull requests welcome!](https://github.com/beaorn/awesome-agriculture)

[Agriculture](https://en.wikipedia.org/wiki/Agriculture) is the science and art of cultivating plants and livestock for food and materials. This list covers open source robotics, hardware, data, modelling and software for farms and growers.

Contributions welcome! Please follow the [contributing guidelines](https://github.com/beaorn/awesome-agriculture/blob/master/contributing.md).

## Contents

| Section | Subsections |
| :--- | :--- |
| [Automation and Robotics](#automation-and-robotics) | |
| [Calculators](#calculators) | |
| [Climate, Environment and Weather](#climate-environment-and-weather) | |
| [Crop Modelling, Phenotyping and Pathology](#crop-modelling-phenotyping-and-pathology) | |
| [Datasets](#datasets) | |
| [Data Standardisation, Interoperability and APIs](#data-standardisation-interoperability-and-apis) | [AgStack](#agstack) |
| [Farm Management Systems and Record Keeping](#farm-management-systems-and-record-keeping) | |
| [Geospatial and GIS](#geospatial-and-gis) | [GIS Resources](#gis-resources) · [GIS Platforms](#gis-platforms) · [Shapefiles](#shapefiles) |
| [IoT, Hardware](#iot-hardware) | |
| [Knowledgebases and Learning Resources](#knowledgebases-and-learning-resources) | |
| [Machine Learning and AI](#machine-learning-and-ai) | |
| [Remote Sensing and Imagery](#remote-sensing-and-imagery) | |

## Automation and Robotics

> Star and commit badges are only shown for single repositories. Organisation links and non-GitHub projects have none.

| Project Name | Description |
| :--- | :--- |
| [Acorn Rover](https://github.com/Twisted-Fields) | Precision farming rover, ODrive, Python. |
| [Ant Robotics](https://antrobotics.de/) | Development from the EcoTerra Bot. |
| [Earth Rover](https://github.com/earthrover) | Agricultural AGV, ROS 1 precision farming rover. |
| [EcoTerra Bot](https://ecoterrabot.com/) | Delta and rover. |
| [FarmBot](https://github.com/farmbot) | Open source precision gardening project. |
| [FarmBot-ROS](https://github.com/farmbot-ros/) | Open source farming robot. |
| [Field Friend](https://github.com/zauberzeug/field_friend) ![GitHub Repo stars](https://img.shields.io/github/stars/zauberzeug/field_friend?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/zauberzeug/field_friend) | Development platform for autonomous weeding. |
| [Fields2Cover](https://github.com/Fields2Cover/Fields2Cover) ![GitHub Repo stars](https://img.shields.io/github/stars/Fields2Cover/Fields2Cover?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Fields2Cover/Fields2Cover) | Robust and efficient coverage paths for autonomous agricultural vehicles. |
| [Romi project](https://media.romi-project.eu/documents/index.html) | Europe-funded research project. |
| [ROS Agriculture](http://rosagriculture.org/) | Open source community using the Robot Operating System to give farmers robotics tools. |
| [Sowbot](https://github.com/Agroecology-Lab/feldfreund_devkit_ros) ![GitHub Repo stars](https://img.shields.io/github/stars/Agroecology-Lab/feldfreund_devkit_ros?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Agroecology-Lab/feldfreund_devkit_ros) | Line-following sowing and weeding robot with some web UI tools. |
| [Weedinator](https://hackaday.io/project/53896-weedinator-2019) | Line-following weeding robot. |
| [Zauberzeug](https://github.com/zauberzeug/) | Feldfreund weeding robot, complete open software stack published. |

## Calculators

| Project Name | Description |
| :--- | :--- |
| [farm-calculators](https://github.com/brycejohnston/farm-calculators) ![GitHub Repo stars](https://img.shields.io/github/stars/brycejohnston/farm-calculators?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/brycejohnston/farm-calculators) | WordPress plugin for calculating various farming and crop related information. |

## Climate, Environment and Weather

| Project Name | Description |
| :--- | :--- |
| [agroclimatology](https://github.com/brycejohnston/agroclimatology) ![GitHub Repo stars](https://img.shields.io/github/stars/brycejohnston/agroclimatology?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/brycejohnston/agroclimatology) | Ruby client for the NASA POWER Agroclimatology web resource. |
| [evapotranspiration](https://github.com/brycejohnston/evapotranspiration) ![GitHub Repo stars](https://img.shields.io/github/stars/brycejohnston/evapotranspiration?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/brycejohnston/evapotranspiration) | Ruby library for calculating reference crop evapotranspiration (ETo). |
| [frostline](https://github.com/waldoj/frostline) ![GitHub Repo stars](https://img.shields.io/github/stars/waldoj/frostline?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/waldoj/frostline) | Dataset, API and Python parser for USDA plant hardiness zones. |
| [GSODR](https://github.com/ropensci/GSODR) ![GitHub Repo stars](https://img.shields.io/github/stars/ropensci/GSODR?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ropensci/GSODR) | Global summary daily weather data in R. |
| [iem](https://github.com/akrherz/iem) ![GitHub Repo stars](https://img.shields.io/github/stars/akrherz/iem?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/akrherz/iem) | Code that makes the Iowa Environmental Mesonet run. |
| [PyETo](https://github.com/woodcrafty/PyETo) ![GitHub Repo stars](https://img.shields.io/github/stars/woodcrafty/PyETo?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/woodcrafty/PyETo) | Python package for calculating reference and potential evapotranspiration (ETo). |
| [pyTSEB](https://github.com/hectornieto/pyTSEB) ![GitHub Repo stars](https://img.shields.io/github/stars/hectornieto/pyTSEB?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/hectornieto/pyTSEB) | Python two-source energy balance model for estimating evapotranspiration from remote sensing data. |
| [soilDB](https://github.com/ncss-tech/soilDB) ![GitHub Repo stars](https://img.shields.io/github/stars/ncss-tech/soilDB?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ncss-tech/soilDB) | R library for simplified access to NCSS soil databases. |

## Crop Modelling, Phenotyping and Pathology

| Project Name | Description |
| :--- | :--- |
| [Open Plant Pathology](https://www.openplantpathology.org/) | Community for open data and computational tools in epidemiology and pathogen population biology and ecology. |

## Datasets

| Project Name | Description |
| :--- | :--- |
| [Agriculture Datasets Collection](https://lacunafund.org/datasets/agriculture/) | Curated machine learning datasets addressing food security in developing regions. |
| [CEAOD](https://ceaod.github.io/) | Controlled Environment Agriculture Open Data: standardised greenhouse and indoor farming datasets with analysis tools. |
| [CropHarvest](https://github.com/nasaharvest/cropharvest) ![GitHub Repo stars](https://img.shields.io/github/stars/nasaharvest/cropharvest?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/nasaharvest/cropharvest) | Remote sensing dataset for global crop type mapping, 95,186 labelled datapoints from satellite imagery. |
| [CWFID](https://github.com/cwfid/dataset) ![GitHub Repo stars](https://img.shields.io/github/stars/cwfid/dataset?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/cwfid/dataset) | Field images, vegetation segmentation masks and crop/weed plant type annotations. |
| [FAO/NASA Harvest Crop Type Dataset](https://data.harvestportal.org/dataset/fao-bha-nasa-harvest-public-crop-type-datasets) | Ground truth crop type observations with geolocated field data for training and validating cropland classification models. |
| [Growstuff](https://www.growstuff.org/crops) | Record keeping and crop database with a good API. |
| [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease) | Leaf images of healthy and diseased plants, 38 disease classes across 14 crops. |
| [SoybeanYield](https://github.com/saeedkhaki92/CNN-RNN-Yield-Prediction) ![GitHub Repo stars](https://img.shields.io/github/stars/saeedkhaki92/CNN-RNN-Yield-Prediction?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/saeedkhaki92/CNN-RNN-Yield-Prediction) | Multimodal soybean yield forecasting dataset: yield, management practices, weather and soil parameters. |
| [TERRA REF](https://terraref.org) | 1 PB of public domain, high resolution sensor data from sorghum breeding trials. [Data publication](https://doi.org/10.5061/dryad.4b8gtht99), with large files on [Globus](https://app.globus.org/file-manager?origin_id=e8feaff4-96cd-11ea-bf90-0e6cccbb0103&origin_path=%2F) (ncsa#terra-public). |

## Data Standardisation, Interoperability and APIs

| Project Name | Description |
| :--- | :--- |
| [AgGateway ADAPT Toolkit](https://adaptframework.org) | Open source tools to simplify communication between growers, their machines and their partners. |
| [Agstack](https://github.com/agstack) | Open source digital infrastructure for the agriculture ecosystem. See [AgStack](#agstack) below for its projects. |
| [API-Code-Samples](https://github.com/aWhereAPI/API-Code-Samples) ![GitHub Repo stars](https://img.shields.io/github/stars/aWhereAPI/API-Code-Samples?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/aWhereAPI/API-Code-Samples) | aWhere API platform code samples. |
| [Botanica](https://github.com/Michael-A-Kuykendall/botanica) ![GitHub Repo stars](https://img.shields.io/github/stars/Michael-A-Kuykendall/botanica?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Michael-A-Kuykendall/botanica) | Rust crate for botanical data management with taxonomic hierarchy, cultivation tracking and Darwin Core compliance. |
| [ClearAg-API-Examples](https://github.com/IterisClearAg/ClearAg-API-Examples) ![GitHub Repo stars](https://img.shields.io/github/stars/IterisClearAg/ClearAg-API-Examples?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/IterisClearAg/ClearAg-API-Examples) | Code examples using the ClearAg APIs. |
| [Fiware AgriFood](https://www.fiware.org/community/smart-agrifood/) | Open source data standards and IoT framework for connecting farm systems, part of the larger Fiware.org project. |
| [JDLinkMachineDataAPI-OAuth2-CSharp-Example](https://github.com/JohnDeere/JDLinkMachineDataAPI-OAuth2-CSharp-Example) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnDeere/JDLinkMachineDataAPI-OAuth2-CSharp-Example?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JohnDeere/JDLinkMachineDataAPI-OAuth2-CSharp-Example) | C# JDLink Machine Data API client example. |
| [MyJohnDeereAPI-OAuth2-Java-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-Java-Example) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnDeere/MyJohnDeereAPI-OAuth2-Java-Example?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JohnDeere/MyJohnDeereAPI-OAuth2-Java-Example) | Java MyJohnDeere API client example. |
| [MyJohnDeereAPI-OAuth2-NodeJS-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-NodeJS-Example) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnDeere/MyJohnDeereAPI-OAuth2-NodeJS-Example?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JohnDeere/MyJohnDeereAPI-OAuth2-NodeJS-Example) | Node.js MyJohnDeere API client example. |
| [MyJohnDeereAPI-OAuth2-Python-Example](https://github.com/JohnDeere/MyJohnDeereAPI-OAuth2-Python-Example) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnDeere/MyJohnDeereAPI-OAuth2-Python-Example?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JohnDeere/MyJohnDeereAPI-OAuth2-Python-Example) | Python MyJohnDeere API client example. |
| [Open Ag Data Alliance](https://github.com/oada) | Open project for interoperability, security and privacy of agricultural data (OADA). |
| [OpenTeam](https://openteam.community/) | Open technology ecosystem for agricultural management. |
| [SampleData](https://github.com/JohnDeere/SampleData) ![GitHub Repo stars](https://img.shields.io/github/stars/JohnDeere/SampleData?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JohnDeere/SampleData) | Sample datacards, shapefiles and other files for testing. |
| [SencropAPI-JavaScript-Client](https://github.com/sencrop/sencrop-js-api-client) ![GitHub Repo stars](https://img.shields.io/github/stars/sencrop/sencrop-js-api-client?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/sencrop/sencrop-js-api-client) | JavaScript client to read and manage Sencrop weather stations. |

### AgStack

> Selected repositories from the [AgStack Foundation](https://github.com/agstack), a Linux Foundation project. Governance, meeting, website, artwork and stale messaging repos are left out.

#### Asset Registry

| Project Name | Description |
| :--- | :--- |
| [asset-registry](https://github.com/agstack/asset-registry) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/asset-registry?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/asset-registry) | Registers a geospatial asset (typically a polygon) and returns a unique GeoID; Flask, AR 1.0. |
| [ar2](https://github.com/agstack/ar2) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/ar2?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/ar2) | Asset Registry 2: hub and spoke model. |
| [ar2-hub](https://github.com/agstack/ar2-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/ar2-hub?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/ar2-hub) | Hub component for Asset Registry 2. |
| [user-registry](https://github.com/agstack/user-registry) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/user-registry?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/user-registry) | User accounts, JWT issuance and API keys for AR 1.0. |
| [asset-registry-fe](https://github.com/agstack/asset-registry-fe) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/asset-registry-fe?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/asset-registry-fe) | Web frontend for the Asset Registry. |
| [autogeobound](https://github.com/agstack/autogeobound) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/autogeobound?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/autogeobound) | Automatic field boundary detection from satellite imagery. |
| [pancake](https://github.com/agstack/pancake) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/pancake?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/pancake) | AI-native geospatial datastore and DPI services: field ownership grants as SD-JWT credentials, signed audit ledger, scheduled vendor data ingestion. |
| [jupyter-notebooks](https://github.com/agstack/jupyter-notebooks) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/jupyter-notebooks?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/jupyter-notebooks) | Demo notebooks showing API usage. |

#### INATrace

| Project Name | Description |
| :--- | :--- |
| [inatrace](https://github.com/agstack/inatrace) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/inatrace?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/inatrace) | Meta repository linking the INATrace backend, frontend, mobile and blockchain components; blockchain-based track and trace for supply chains. |
| [inatrace-backend](https://github.com/agstack/inatrace-backend) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/inatrace-backend?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/inatrace-backend) | Java/Spring backend. |
| [inatrace-frontend](https://github.com/agstack/inatrace-frontend) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/inatrace-frontend?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/inatrace-frontend) | Angular frontend. |
| [inatrace-mobile](https://github.com/agstack/inatrace-mobile) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/inatrace-mobile?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/inatrace-mobile) | Mobile app for farmer data collection. |
| [inatrace-coffee-network](https://github.com/agstack/inatrace-coffee-network) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/inatrace-coffee-network?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/inatrace-coffee-network) | Blockchain smart contracts for the coffee supply chain. |

#### OpenAgri

| Project Name | Description |
| :--- | :--- |
| [OpenAgri-Bootstrap-Deployment](https://github.com/agstack/OpenAgri-Bootstrap-Deployment) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-Bootstrap-Deployment?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-Bootstrap-Deployment) | Modular configuration and deployment of all OpenAgri services. |
| [OpenAgri-GateKeeper](https://github.com/agstack/OpenAgri-GateKeeper) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-GateKeeper?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-GateKeeper) | JWT-based authentication and access proxy. |
| [OpenAgri-FarmCalendar](https://github.com/agstack/OpenAgri-FarmCalendar) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-FarmCalendar?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-FarmCalendar) | Digital farm calendar for operations, observations, parcels and assets. |
| [OpenAgri-WeatherService](https://github.com/agstack/OpenAgri-WeatherService) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-WeatherService?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-WeatherService) | Weather forecasts and critical agricultural indicators. |
| [OpenAgri-IrrigationManagement](https://github.com/agstack/OpenAgri-IrrigationManagement) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-IrrigationManagement?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-IrrigationManagement) | Evapotranspiration calculations and soil moisture analysis. |
| [OpenAgri-PestAndDiseaseManagement](https://github.com/agstack/OpenAgri-PestAndDiseaseManagement) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-PestAndDiseaseManagement?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-PestAndDiseaseManagement) | Pest and disease monitoring and management. |
| [OpenAgri-ReportingService](https://github.com/agstack/OpenAgri-ReportingService) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-ReportingService?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-ReportingService) | PDF report generation for agricultural data visualisation. |
| [OpenAgri-UserDashboard](https://github.com/agstack/OpenAgri-UserDashboard) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-UserDashboard?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-UserDashboard) | Web UI exposing all OpenAgri services. |
| [OpenAgri-OCSM](https://github.com/agstack/OpenAgri-OCSM) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/OpenAgri-OCSM?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/OpenAgri-OCSM) | OpenAgri Common Semantic Model. |

#### Farm and Field Apps

| Project Name | Description |
| :--- | :--- |
| [AgriOS](https://github.com/agstack/AgriOS) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/AgriOS?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/AgriOS) | Odoo 18 farm management addons: farmers, plots, trade and training (AGPL-3). |
| [TerraTrac-field-app](https://github.com/agstack/TerraTrac-field-app) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/TerraTrac-field-app?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/TerraTrac-field-app) | Offline-capable mobile app for recording plot points and polygons, with CSV/GeoJSON export; for EUDR compliance. |
| [TerraTrac-validator-portal](https://github.com/agstack/TerraTrac-validator-portal) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/TerraTrac-validator-portal?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/TerraTrac-validator-portal) | Uploads plot data, runs deforestation risk assessment via the WHisp API and generates reports. |
| [tracefoodchain](https://github.com/agstack/tracefoodchain) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/tracefoodchain?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/tracefoodchain) | Flutter app and web app for tracing goods along food production chains. |
| [ag-rec](https://github.com/agstack/ag-rec) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/ag-rec?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/ag-rec) | Agriculture recommendations from Cooperative Extension Services. |

#### Weather, Climate and Pests

| Project Name | Description |
| :--- | :--- |
| [weather-server](https://github.com/agstack/weather-server) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/weather-server?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/weather-server) | Julia data ingest, pre-processing and serving pipeline for weather data. |
| [weather-forecast](https://github.com/agstack/weather-forecast) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/weather-forecast?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/weather-forecast) | Global weather forecast from NOAA NCEP/NOMADS data. |
| [opensource-pestmodels](https://github.com/agstack/opensource-pestmodels) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/opensource-pestmodels?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/opensource-pestmodels) | Hierarchical pest and disease modelling framework (13 models, 19 crops, 54 threats) with Python wheel, FastAPI and MCP server. |
| [field-carbon-model](https://github.com/agstack/field-carbon-model) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/field-carbon-model?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/field-carbon-model) | Field-specific carbon model using SMAP L4C. |

#### AI and Knowledge Graphs

| Project Name | Description |
| :--- | :--- |
| [palefire](https://github.com/agstack/palefire) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/palefire?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/palefire) | LLM and knowledge graph integration framework. |
| [semantic-croissant](https://github.com/agstack/semantic-croissant) ![GitHub Repo stars](https://img.shields.io/github/stars/agstack/semantic-croissant?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/agstack/semantic-croissant) | Semantic Croissant infrastructure, forked from codata/semantic-croissant. |

## Farm Management Systems and Record Keeping

| Project Name | Description |
| :--- | :--- |
| [Ekylibre](https://github.com/ekylibre/ekylibre) ![GitHub Repo stars](https://img.shields.io/github/stars/ekylibre/ekylibre?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/ekylibre/ekylibre) | Farm management information system for farmers and small enterprises, Ruby on Rails and PostgreSQL/PostGIS. |
| [farmOS](https://github.com/farmOS/farmOS) ![GitHub Repo stars](https://img.shields.io/github/stars/farmOS/farmOS?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/farmOS/farmOS) | Web-based farm record keeping application built with Drupal and PHP. |
| [GrowGood](https://gitlab.com/growgood) | Farm management platform using open standards such as ValueFlows and JSON-LD to track and share interoperable data across farms and marketplaces. |
| [LiteFarm](https://github.com/LiteFarmOrg/LiteFarm) ![GitHub Repo stars](https://img.shields.io/github/stars/LiteFarmOrg/LiteFarm?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/LiteFarmOrg/LiteFarm) | Community-led, not-for-profit farm management system. |
| [Soil Mate](https://github.com/Open-Source-Agriculture/soil_mate) ![GitHub Repo stars](https://img.shields.io/github/stars/Open-Source-Agriculture/soil_mate?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Open-Source-Agriculture/soil_mate) | Helper app for collecting soil data. |
| [Tania](https://github.com/Tanibox/tania-core) ![GitHub Repo stars](https://img.shields.io/github/stars/Tanibox/tania-core?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Tanibox/tania-core) | Free and open source farming management system built with Go and Vue.js. |

## Geospatial and GIS

### GIS Resources

| Project Name | Description |
| :--- | :--- |
| [Awesome GIS](https://github.com/sshuair/awesome-gis) ![GitHub Repo stars](https://img.shields.io/github/stars/sshuair/awesome-gis?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/sshuair/awesome-gis) | Curated list of GIS related sources. |

### GIS Platforms

| Project Name | Description |
| :--- | :--- |
| [QGIS](https://qgis.org) | Free, open source, cross-platform (Linux, Windows, macOS) geographic information system. |

### Shapefiles

| Project Name | Description |
| :--- | :--- |
| [pyshp](https://github.com/GeospatialPython/pyshp) ![GitHub Repo stars](https://img.shields.io/github/stars/GeospatialPython/pyshp?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/GeospatialPython/pyshp) | Reads and writes ESRI Shapefiles in pure Python. |
| [rgeo-shapefile](https://github.com/rgeo/rgeo-shapefile) ![GitHub Repo stars](https://img.shields.io/github/stars/rgeo/rgeo-shapefile?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/rgeo/rgeo-shapefile) | Optional RGeo module for reading geospatial data from ESRI shapefiles in Ruby. |

## IoT, Hardware

| Project Name | Description |
| :--- | :--- |
| [AgOpenGPS](https://github.com/farmerbriantee/AgOpenGPS) ![GitHub Repo stars](https://img.shields.io/github/stars/farmerbriantee/AgOpenGPS?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/farmerbriantee/AgOpenGPS) | Precision mapping and section control software. |
| [Farm-Data-Relay-System](https://github.com/timmbogner/Farm-Data-Relay-System) ![GitHub Repo stars](https://img.shields.io/github/stars/timmbogner/Farm-Data-Relay-System?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/timmbogner/Farm-Data-Relay-System) | Transports sensor data in remote areas over ESP-NOW, LoRa and other protocols, without WiFi. |
| [Farm Hack](https://farmhack.org/tools) | Worldwide community of farmers who build and modify their own tools. |
| [Open Agriculture Foundation](https://github.com/OpenAgricultureFoundation) | Open source technologies for transparency, networked experimentation, education and hyper-local production. |
| [Open hydroponics](https://openhydroponics.com/) | Fully automated hydroponic OS. |
| [OpenMinder](https://github.com/autogrow/openminder) ![GitHub Repo stars](https://img.shields.io/github/stars/autogrow/openminder?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/autogrow/openminder) | Open source rootzone monitoring, API and Raspberry Pi hat. |
| [OpenWeedLocator](https://github.com/geezacoleman/OpenWeedLocator) ![GitHub Repo stars](https://img.shields.io/github/stars/geezacoleman/OpenWeedLocator?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/geezacoleman/OpenWeedLocator) | Low-cost, image-based weed detection device for in-crop and fallow scenarios. |
| [Simplesteer](https://github.com/matmis/simplesteer) ![GitHub Repo stars](https://img.shields.io/github/stars/matmis/simplesteer?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/matmis/simplesteer) | RTK GPS tractor autosteer with a web interface controllable from a smartphone; runs on a Raspberry Pi. |
| [Smart Farming ThingsBoard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) ![GitHub Repo stars](https://img.shields.io/github/stars/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) | Demo project using ThingsBoard to collect sensor data and show real-time dashboards. |

## Knowledgebases and Learning Resources

| Project Name | Description |
| :--- | :--- |
| [Harvest Helper](https://github.com/damwhit/harvest_helper) ![GitHub Repo stars](https://img.shields.io/github/stars/damwhit/harvest_helper?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/damwhit/harvest_helper) | Growing, harvesting and recipe information for 45 plants, with a JSON API. |
| [OpenFarm](https://github.com/openfarmcc/OpenFarm) ![GitHub Repo stars](https://img.shields.io/github/stars/openfarmcc/OpenFarm?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/openfarmcc/OpenFarm) | Free and open database of farming and gardening knowledge, Ruby on Rails. |

## Machine Learning and AI

| Project Name | Description |
| :--- | :--- |
| [AgML](https://github.com/Project-AgML/AgML) ![GitHub Repo stars](https://img.shields.io/github/stars/Project-AgML/AgML?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Project-AgML/AgML) | Centralised framework for agricultural machine learning. |
| [agridat](https://github.com/kwstat/agridat) ![GitHub Repo stars](https://img.shields.io/github/stars/kwstat/agridat?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/kwstat/agridat) | R package with an extensive collection of datasets from agricultural experiments. |
| [Crop Yield Prediction](https://github.com/JiaxuanYou/crop_yield_prediction) ![GitHub Repo stars](https://img.shields.io/github/stars/JiaxuanYou/crop_yield_prediction?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/JiaxuanYou/crop_yield_prediction) | Deep Gaussian process for crop yield prediction from remote sensing data. |
| [Deep Learning for Biologists with Keras](https://github.com/totti0223/deep_learning_for_biologists_with_keras) ![GitHub Repo stars](https://img.shields.io/github/stars/totti0223/deep_learning_for_biologists_with_keras?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/totti0223/deep_learning_for_biologists_with_keras) | Deep learning tutorials, mainly on biologically relevant themes. |
| [FarmVibes.AI](https://github.com/microsoft/farmvibes-ai) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/farmvibes-ai?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/microsoft/farmvibes-ai) | Multimodal geospatial ML models for agriculture and sustainability. |
| [PlantCV](https://github.com/danforthcenter/plantcv) ![GitHub Repo stars](https://img.shields.io/github/stars/danforthcenter/plantcv?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/danforthcenter/plantcv) | Plant phenotyping software using computer vision. |

## Remote Sensing and Imagery

| Project Name | Description |
| :--- | :--- |
| [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel) ![GitHub Repo stars](https://img.shields.io/github/stars/Fernerkundung/awesome-sentinel?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Fernerkundung/awesome-sentinel) | Tools, tutorials and APIs for Copernicus Sentinel satellite data. |
| [Awesome Vegetation Index](https://github.com/px39n/Awesome-Vegetation-Index) ![GitHub Repo stars](https://img.shields.io/github/stars/px39n/Awesome-Vegetation-Index?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/px39n/Awesome-Vegetation-Index) | References and applications of common vegetation indices for multispectral, hyperspectral and UAV imagery. |
| [Raster Vision](https://github.com/azavea/raster-vision) ![GitHub Repo stars](https://img.shields.io/github/stars/azavea/raster-vision?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/azavea/raster-vision) | Deep learning for aerial and satellite imagery. |
| [Sen2Agri](https://github.com/Sen2Agri/Sen2Agri-System) ![GitHub Repo stars](https://img.shields.io/github/stars/Sen2Agri/Sen2Agri-System?style=social)<br>![GitHub last commit](https://img.shields.io/github/last-commit/Sen2Agri/Sen2Agri-System) | System for processing high resolution satellite images for agriculture. |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Bryce Johnston](https://github.com/brycejohnston) has waived all copyright and related or neighbouring rights to this work.

<a id="home-button" href="#contents">Home</a>

<script>
document.querySelectorAll('a[href]').forEach(function (a) {
  if (a.getAttribute('href').charAt(0) === '#') return;
  a.target = '_blank';
  a.rel = 'noopener noreferrer';
});
</script>
