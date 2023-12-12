
# Documentation of shared data

## Usage

This file contains the summary information of the data that has been shared in the framework of the CLINT project.
It can be updated/commited manually or using the `clintshare` tool (recommended):

```bash
module load clint share
clintshare <path-of-data>
```

- Each section corresponds to a type of data and can be identified with its title and its unique ID `dataid`.
- Each section should corresponds to data with unique product, institute, model, experiment and variable fields.

Indexing to [Freva evaluation system](https://www.xces.dkrz.de) is indicated in `Indexed`.


## Daily global minimum temperature from 20cr-v3

- Dataid: k204239.13122023.130101
- Modified date: 12/12/2023 13:01:58
- Userid: k204239
- Username: Etienne Plésiat
- Data path: /home/k/k204239/works/tmp/20crv3/outputs/*/TMIN*.nc
- Number of added files: 15840
- Total size (in MB): 
- Task: 5.2
- Source: https://portal.nersc.gov/archive/home/projects/incite11/www/20C_Reanalysis_version_3/everymember_anal_netcdf/subdaily/TMIN2m
- Processes: Daily minimum of the original 3-hourly data using CDO, zip compression using CDO
- Product: k204239-20cr-v3
- Institute: noaa-cires
- Model: gfs
- Experiment: 20cr-v3
- Variable: tasmin
- Comments: 
- Indexed: 15840 files - 12/12/2023 14:10:38

## ERA5 global hourly 2m temperature

- Dataid: b382634.12122023.153639
- Modified date: 12/12/2023 15:36:39
- Userid: b382634
- Username: Ronan McAdam
- Data path: /work/bk1318/b382634/ERA5/hourly/t2m//**
- Number of added files: 581
- Total size (in MB): 725837
- Variable: t2m
- Task: 3.2
- Source: https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=overview
- Processes: None
- Product: b382634-reanalysis
- Institute: ecmwf
- Model: ifs
- Experiment: era5
- Comments: March data contains 31st day only
- Indexed: No
