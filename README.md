# Ingest and Parse OOI Coastal Endurance Array data

- OOI "raw data" files
  - Description of the "raw data" files, organization:  http://oceanobservatories.org/data/raw-data/
  - CGSN-Parsers: https://github.com/ooi-integration/cgsn-parsers. Emilio's fork and changes to the CGSN-Parsers are [here, on the `mem_leak` branch](https://github.com/emiliom/cgsn-parsers/tree/mem_leak)
  - File headers (specially units) for `CE02SHSM` platform/site:  https://rawdata.oceanobservatories.org/files/CE02SHSM/R00001/cg_data/dcl11/datafmt.txt
  - Directory of `metbk` daily log (data) files for `CE07SHSM` platform/site, deployment 3 (`D00003`): https://rawdata.oceanobservatories.org/files/CE07SHSM/D00003/cg_data/dcl11/metbk/
- General OOI data information resources
  - Instruments page (metbk, etc): http://oceanobservatories.org/instruments/
- NANOOS
  - `CE07SHSM` platform/site asset on NVS: http://nvs.nanoos.org/Explorer?action=oiw:fixed_platform:OOI_CE07SHSM
