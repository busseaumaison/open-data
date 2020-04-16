[En français](changelog_rdaqa_fr.md)

![ECCC logo](../../img_eccc-logo.png)

[TOC](../../readme_en.md) > [MSC data](../readme_en.md) > [RDAQA](readme_rdaqa_en.md) > RDAQA Changelog

# Chronology of changes to the Regional Deterministic Air Quality Analysis (RDAQA)

## Tuesday January 21, 2020

### Upgrade to Version 1.3.0 of the RDAQA adapted to the New High Performance Computing Infrastructure.

See details [at this link](../changelog_multisystems_en.md)

## Thursday April 16, 2015

### The Canadian Meteorological Centre (CMC) updates version 1.0.0 of the Regional Deterministic Air Quality Analysis (RDAQA) with version 1.1.0

Since February 2013, surface analyses have been generated by the RDAQA for ozone (O3) and fine particulate matter (PM2.5). The CMC, in collaboration with the Air Quality Research Division of the Atmospheric Science and Technology Branch, are hereby proceeding with an upgrade to add three new pollutants to the RDAQA: nitrogen dioxide (NO2), particulate matter with a diameter of less than 10um (PM10), and sulfur dioxide (SO2). Also, a new product will become available. A geographical mapping of the Air Quality Health Index (AQHI) for the entire Regional Air Quality Deterministic Prediction System (RAQDPS) model domain (covering most of Canada and the USA).

Initially products generated by the RDAQA system will be available only to internal Environment Canada clients via the AQHI forecast resource web site and via the internal Vizaweb interface. In the future however, these products will also be available via the Environment Canada's [public data portal referred to as the datamart](https://dd.weather.gc.ca/).

A copy of the official note describing these changes and the verification work leading up to this implementation is available [here](https://dd.meteo.gc.ca/doc/genots/2015/04/13/NOCN03_CWAO_132005___00001).

The technical note associated with the implementation is available [at this link](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/lib/op_systems/doc_opchanges/RDAQA_v110_Technical_note_EN.pdf).

## Thursday February 28, 2013

### The Canadian Meteorological Centre (CMC) implements version 1.0.0 of the new Regional Deterministic Air Quality Analysis (RDAQA)

On Thursday Feburary 28, 2013 the Canadian Meteorological Centre (CMC) will start producing a Regional Deterministic Air Quality Analysis (RDAQA) for air quality species at the surface. Initially surface analyses will be generated for ozone (O3) and fine particulate matter (PM2.5). Research continues with respect to the production of a surface analysis for nitrogen dioxide (NO2) with the goal of implementing this product later in 2013.

The RDAQA system ingests surface observations of O3 and PM2.5 from the Canadian provincial and municipal air quality monitoring networks, the Canadian air and precipitation monitoring network (CAPMoN), and the [U.S. EPA/AIRNOW program](https://airnow.gov/). The trial fields for the analyses are supplied by the operational Regional Air Auality Deterministic Prediction System (RAQDPS), which generates forecast guidance out to 48 hours on a grid with 10-km horizontal grid spacing and 80 vertical levels.

Two analyses are generated every hour of the day. The "early analysis" is generated approximately one hour after the valid hour and it exploits close to 98% and 80% of the Canadian and U.S. stations, respectively. The "final analysis" is generated approximately two hours after the valid hour and it ingests close to 99% and 95% of the Canadian and U.S. stations respectively.

Objective verification scores have been computed for O3 and PM2.5 over winter and summer seasons. These scores indicate that the analysis provides a substantial reduction in standard deviation and the bias is largely eliminated for all analysis hours. A categorical score called the frequency correct within a factor of two (FC2) shows that the analysis is more reliable than the model for all hours of the day.

During an experimental run of the RDAQA system carried out during the fall of 2012, a subjective evaluation was performed by members of Environment Canada's regional forecast offices. Conclusions of the evaluation are presented in the official notice at the link available below.

Initially products generated by the RDAQA system will be available only to internal Environment Canada clients via the AQHI forecast resource web site and via the internal Vizaweb interface. In the future however, these products will also be available via the Environment Canada's [public data portal referred to as the datamart](https://dd.weather.gc.ca/).

A copy of the official note describing these changes and the verification work leading up to this implementation is available [here](https://dd.weather.gc.ca/doc/genots/2013/02/26/NOCN03_CWAO_262215___00276).

A technical note with more details on this change is available [at this link](https://collaboration.cmc.ec.gc.ca/cmc/CMOI/product_guide/docs/lib/op_systems/doc_opchanges/technote_rdaqa100_20130228_e.pdf).