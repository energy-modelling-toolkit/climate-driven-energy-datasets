# Climate reanalysis datasets
This page contains a list of all the **freely available** datasets of energy variables (electricity demand, wind/solar/hydro-power) reconstructions based on climate reanalyses or climate change projections. 
 
The list is a work-in-progress, please reply to this post if you want to add a dataset or suggest a correction.

The acronym `CF` stands for "Capacity factor", the ratio between the energy output and the total installed capacity. 
 
## Historical period 
 
### Electricity demand
 
| Name            | Unit          | Period       | Domain | Spat. res. | Time res. | Meteo input(s) | data license                 | updates | URL                                                                        |
| --------------- | ------------- | ------------ | ------ | ---------- | --------- | ---------------- | ---------------------------- | ------- | -------------------------------------------------------------------------- |
| C3S Operational | Energy, Power | 1979-present | Europe | Country    | daily     | ERA5             | ECMWF Copernicus License 1.0 | yes | https://doi.org/10.24381/cds.4bd77450                                                     |
| ECEM            | Energy, Power | 1979-2016    | Europe | Country    | daily     | ERA-INTERIM      | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                                                |
| JRC 2020        | Power         | 1990-2015    | Europe | Country    | hourly    | ERA5             | CC BY 4.0                          | no      | https://data.jrc.ec.europa.eu/dataset/221c6cf4-98c0-4793-8e3a-78820377387f |
| UREAD Energy Reanalysis | Power                | 1980-2018    | Europe | Country                     | Hourly    | MERRA2           | CC Attributions 4.0          | no      | http://dx.doi.org/10.17864/1947.239                                        |
 
### Solar power
 
| Name                                                                                                                          | Unit              | Period       | Domain | Spat. res.                  | Time res. | Meteo input(s) | data license                 | updates | URL                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------ | ------ | --------------------------- | --------- | ---------------- | ---------------------------- | ------- | -------------------------------------------------------------------------- |
| C3S Operational                                                                                                               | CF, Energy, Power | 1979-present | Europe | 25km, NUTS0, NUTS2          | hourly    | ERA5             | ECMWF Copernicus License 1.0               | yes | https://doi.org/10.24381/cds.4bd77450                                   |
| ECEM                                                                                                                          | CF, Energy, Power | 1979-2016    | Europe | Country and eh2050 clusters | daily     | ERA-INTERIM      | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                                                |
| EMHIRES-Solar                                                                                                                 | CF                | 1986-2015    | Europe | NUTS2                       | Hourly    | CM-SAF SARAH     | European Commission Reuse    | no      | https://doi.org/10.5281/zenodo.4803353                                |
| ENTSO-E PECD                                                                                                                  | CF                | 1982-2016    | Europe | ENTSO-E Area                | hourly    |                  |                              |         | https://www.entsoe.eu/outlooks/midterm/ |
| ERA5 derived time series of European country-aggregate electricity demand, wind power generation and solar power generation   | CF                | 1979-2018    | Europe | Country                     | 3-hourly  | ERA5             | CC Attributions 4.0          | no      | http://dx.doi.org/10.17864/1947.227                                        |
| UREAD Energy Reanalysis ERA5 | CF                | 1950-2020    | Europe | Country                     | Hourly    | ERA5           | CC Attributions 4.0          | no      | https://researchdata.reading.ac.uk/321/                                        |
| UREAD Energy Reanalysis | CF                | 1980-2018    | Europe | Country                     | Hourly    | MERRA2           | CC Attributions 4.0          | no      | http://dx.doi.org/10.17864/1947.239                                        |
| Renewables.ninja                                                                                                              | CF                | 1980-2019    | Europe | NUTS2                       | Hourly    | SARAH, MERRA2    | CC-BY-4.0                    | yes     | https://www.renewables.ninja/                                              |
 
### Wind power
 
| Name                                                                                                                          | Unit              | Period       | Domain | Spat. res.                                    | Time res. | Meteo input(s) | data license                 | updates | URL                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------ | ------ | --------------------------------------------- | --------- | ---------------- | ---------------------------- | ------- | -------------------------------------------------------------------------- |
| C3S Operational                                                                                                               | CF, Energy, Power | 1979-present | Europe | 25km, NUTS0, NUTS2 (MAR0 & MAR1 for offshore) | hourly    | ERA5             | ECMWF Copernicus License 1.0                          | yes     | https://doi.org/10.24381/cds.4bd77450                                                     |
| ECEM                                                                                                                          | CF, Energy, Power | 1979-2016    | Europe | Country and eh2050 clusters                   | daily     | ERA-INTERIM      | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                                                |
| EMHIRES-Wind                                                                                                                  | CF                | 1986-2015    | Europe | NUTS2                                         | Hourly    | MERRA2           | European Commission Reuse    | no      | https://doi.org/10.5281/zenodo.4803353                                |
| ENTSO-E PECD                                                                                                                  | CF                | 1982-2016    | Europe | ENTSO-E Area                                  | hourly    |                  |                              |         | https://www.entsoe.eu/outlooks/midterm/ |
| ERA5 derived time series of European country-aggregate electricity demand, wind power generation and solar power generation   | CF                | 1979-2018    | Europe | Country                                       | 3-hourly  | ERA5             | CC Attributions 4.0          | no      | http://dx.doi.org/10.17864/1947.227                                        |
| UREAD Energy Reanalysis ERA5 | CF                | 1950-2020    | Europe | Country                     | Hourly    | ERA5           | CC Attributions 4.0          | no      | https://researchdata.reading.ac.uk/321/                                        |
| UREAD Energy Reanalysis | CF                | 1980-2018    | Europe | Country                                       | Hourly    | MERRA2           | CC Attributions 4.0          | no      | http://dx.doi.org/10.17864/1947.239                                        |
| Renewables.ninja                                                                                                              | CF                | 1980-2019    | Europe | NUTS2                                         | Hourly    | MERRA2           | CC-BY-4.0                    | yes     | https://www.renewables.ninja/   |
| WIND Toolkit | Power | 2007-2013 | US | 2x2 km | Hourly | ERA-INTERIM | | no | https://www.nrel.gov/grid/wind-toolkit.html | 
 
### Hydropower
| Name            | Unit               | Period       | Domain | Spat. res.                  | Time res. | Meteo input(s) | data license                 | updates | URL                                                                                                                      |
| --------------- | ------------------ | ------------ | ------ | --------------------------- | --------- | ---------------- | ---------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------ |
| C3S Operational | CF, Energy, Power  | 1979-present | Europe | Country                     | daily     | ERA5             | ECMWF Copernicus License 1.0                          | yes     | https://doi.org/10.24381/cds.4bd77450                                                                                                        |
| ECEM            | CF, Energy, Power  | 1979-2016    | Europe | Country and eh2050 clusters | daily     | ERA-INTERIM      | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                                                                                              |
| ENTSO-E PECD    | Inflow, reservoirs | 1982-2017    | Europe | ENTSO-E Area                | weekly    |                  |                              |         | https://www.entsoe.eu/outlooks/seasonal/                                                                                 |
| JRC 2020        | Inflow, reservoirs | 1990-2015    | Europe | Country                     | Hourly    | LISFLOOD         | CC Attributions 4.0          | no      | https://data.jrc.ec.europa.eu/dataset/221c6cf4-98c0-4793-8e3a-78820377387f/resource/fdb93cbc-703e-46b6-8cf7-02fba9a0ac38 |
| JRC-EFAS-Hydropower | Inflow, ror generation | 1991-2019 | Europe | Country | Weekly/daily | C3S EFAS | CC Attributions 4.0 | no | https://zenodo.org/record/4086004 |  

## Climate change projections
 
### Demand
 
| Name            | Unit          | Period    | Domain | Spat. res. | Time res. | climate input(s)                                                 | data license                 | updates | URL                         |
| --------------- | ------------- | --------- | ------ | ---------- | --------- | ---------------------------------------------------------------- | ---------------------------- | ------- | --------------------------- |
| C3S Operational | Energy, Power | 1970-2100 | Europe | Country    | 3-hourly  | 10 RCMs, RCPS 4.5, 2.8.5, 2.6 (no all scenarios for all models) | ECMWF Copernicus License 1.0                          | no     | https://doi.org/10.24381/cds.f6951a62      |
| ECEM            | Energy, Power | 1979-2100 | Europe | Country    | daily     | 10 RCMs. 3 scenarios                                              | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/ |
 
 
### Solar power
 
|                                                                                                                               | Unit              | Period    | Domain | Spat. res.                  | Time res. | Meteo input(s)                                                 | data license                 | updates | URL                                             |
| ----------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ------ | --------------------------- | --------- | ---------------------------------------------------------------- | ---------------------------- | ------- | ----------------------------------------------- |
| C3S Operational                                                                                                               | CF, Energy, Power | 1970-2100 | Europe | 25km, Country, NUTS2        | 3-hourly  | 10 RCMs, RCPS 4.5, 2.8.5, 2.6 (no all scenarios for all models) | ECMWF Copernicus License 1.0                          | no     |https://doi.org/10.24381/cds.f6951a62                          |
| ECEM                                                                                                                          | CF, Energy, Power | 1979-2100 | Europe | Country and eh2050 clusters | daily     | 10 RCMs, 3 scenarios                                              | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                     |
| Supplementary Data: 21st Century climate change impacts on key properties of a large-scale renewable-based electricity system | CF                | 1970-2100 | Europe | Country                     | 3-hourly  | 5 GCMs, 3 RCP scenarios                                          | CC-BY-4.0                    | no      | https://data.mendeley.com/datasets/zs55rrrvzw/1 |
 
### Wind power
| Name                                                                                                                          | Unit              | Period    | Start year | End year | Domain | Spat. res.                                      | Time res. | Meteo input(s)                                                 | data license                 | updates | URL                                             |
| ----------------------------------------------------------------------------------------------------------------------------- | ----------------- | --------- | ---------- | -------- | ------ | ----------------------------------------------- | --------- | ---------------------------------------------------------------- | ---------------------------- | ------- | ----------------------------------------------- |
| C3S Operational                                                                                                               | CF, Energy, Power | 1970-2100 | 1970       | 2100     | Europe | 25km, Country, NUTS2 (MAR0 & MAR1 for offshore) | 3-hourly  | 10 RCMs, RCPS 4.5, 2.8.5, 2.6 (no all scenarios for all models) | ECMWF Copernicus License 1.0 | no     | https://doi.org/10.24381/cds.f6951a62                          |
| ECEM                                                                                                                          | CF, Energy, Power | 1979-2100 | 1979       | 2100     | Europe | Country and eh2050 clusters                     | daily     | 10 RCMs, 3 scenarios                                              | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/                     |
| Supplementary Data: 21st Century climate change impacts on key properties of a large-scale renewable-based electricity system | CF                | 1970-2100 | 1970       | 2100     | Europe | Country                                         | 3-hourly  | 5 GCMs, 3 RCP scenarios                                          | CC-BY-4.0                    | no      | https://data.mendeley.com/datasets/zs55rrrvzw/1 |
 
### Hydropower
| Name            | Unit              | Period    | Start year | End year | Domain | Spat. res. | Time res. | climate input(s)                                                 | data license                 | updates | URL                         |
| --------------- | ----------------- | --------- | ---------- | -------- | ------ | ---------- | --------- | ---------------------------------------------------------------- | ---------------------------- | ------- | --------------------------- |
| C3S Operational | CF, Energy, Power | 1970-2100 | 1970       | 2100     | Europe | Country    | 3-hourly  | 10 RCMs, RCPS 4.5, 2.8.5, 2.6 (no all scenarios for all models) | ECMWF Copernicus License 1.0                          | no     | https://doi.org/10.24381/cds.f6951a62      |
| ECEM            | CF, Energy, Power | 1979-2100 | 1979       | 2100     | Europe | Country    | daily     | 10 RCMs, 3 scenarios                                              | ECMWF Copernicus License 1.0 | no      | http://ecem.wemcouncil.org/ |
 
 
 

