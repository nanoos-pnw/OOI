### OOI Listings

- Research Arrays: http://oceanobservatories.org/research-arrays/
- Sites: http://oceanobservatories.org/site-list/
- Instruments: http://oceanobservatories.org/instruments/
- Data Products: http://oceanobservatories.org/data-products/data-products-complete-list/

### Table of parameters mapping for OA assets

| id  | platform_code | parameters                                                       |
|:--- |:------------- |:---------------------------------------------------------------- |
| 560 | CE09OSSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; **CO2_sw(7m)** |
| 561 | GA01SUMO      | temperature; salinity; CO2_air; CO2_sw(7m); **pH**               |
| 562 | GP03FLMA      | **temperature; salinity; pH**                                    |
| 563 | CE02SHSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*                 |
| 564 | CE01ISSM      | temperature; salinity; pH; CO2_sw(7m)                            |
| 565 | CE04OSSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*                 |
| 566 | GI01SUMO      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; CO2_sw(7m)     |
| 567 | CE06ISSM      | temperature; salinity; pH; CO2_sw(7m)                            |
| 568 | CP01CNSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; CO2_sw(7m)     |
| 569 | CP03ISSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; CO2_sw(7m)     |
| 570 | CP04OSSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; CO2_sw(7m)     |
| 571 | CE07SHSM      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*                 |
| 572 | GS01SUMO      | temperature; salinity; pH; CO2_air; *CO2_sw(1m)*; CO2_sw(7m)     |

Notes:
- *parameter* = This parameter is part of `pCO2a` instrument which measures both CO2 in air and water.
- **parameter** = This parameter data are recovered from instrument, and are not in situ live stream.

### OOI Resource Links

- https://marine.rutgers.edu/cool/ooi/uframe-status/viz/json/uframe-instruments-all.json
- https://ooinet.oceanobservatories.org/api/asset_deployment
- https://ooinet.oceanobservatories.org/api/uframe/stream
- https://github.com/adampotocki/ref_des
- http://uframe-test.ooi.rutgers.edu:12576/sensor/inv/
- https://github.com/ooi-integration/asset-management
- https://github.com/kerfoot/ooinet-product-browser/tree/master/www/json/observatoryDataProducts
- https://github.com/asascience-open/ooi-ui-services
- https://ooinet.oceanobservatories.org/api/asset_deployment?min=True
- https://github.com/asascience-open/ooi-ui-services/blob/master/db/ooiui_schema_data.sql
- https://github.com/asascience-open
- https://marine.rutgers.edu/cool/ooi/uframe-status/
- http://ooiufs01.ooi.rutgers.edu:12576/sensor/inv/
- https://github.com/ooi-data-review/uframe-api
- https://marine.rutgers.edu/cool/ooi/uframe-status/json/status.json
- https://ooinet.oceanobservatories.org/api/array

### Raw Data Archive

Link to the structure of the Raw Data Archive can be found in this [tree.html](https://rawdata.oceanobservatories.org/files/.tree.html)

**Note: It appears that this html is not updated for each deployment.**

### OOI Data Vocabulary Table

| Vocab                 | Definition |
|:--------------------- |:----------- |
| BEP 	                | Benthic Experiment Package, a cabled seafloor platform containing a Low-Power Junction Box and multiple instruments inside a trawl-resistant frame |
| Cabled                | Any node or instrument attached to the electro-optical cable on the west coast |
| CPM 	                | Platform Controller (engineering data only) |
| D0000\*               | Deployment folder, aka telemetered data (sent to shore while platform is deployed) |
| DCL 	                | Data Concentrator Logger, the controller computer that concentrates the data from multiple instruments on uncabled moorings, packages the data, and telemeters to shore |
| DVL 	                | Glider ADCP, Teledyne RDI 600 kHz Explorer DVL |
| LJ0\*\*               | Low-Power Junction Box, a smaller cabled node that powers seafloor instruments, occasionally located inside a seafloor platform |
| LV0\*\*               | Low-Voltage Node, connected to the Primary Node |
| MFN 	                | A seafloor instrument frame at the base of coastal moorings, containing the anchor and acoustic release package, battery packs, and multiple instruments |
| MJ0\*\*               | Medium-Power Junction Box, a cabled node that powers seafloor instruments |
| PN0\*\*               | Primary Node, connected directly to the electro-optical cable, usually not instrumented |
| Profiler              | A mooring installation with an instrumented platform that moves up and down vertically in the water column. One type of profiler on the OOI is a wire-following modified McLane profiler (WFP) that crawls along an inductive cable using a traction motor. These are indicated by reference designator platform codes ending in “PM” for “Profiler Mooring”. The other type of profiler is a coastal surface piercing profiler (CSPP) that uses a winch to spool out line from a buoyant instrument platform, raising and lowering it in the water. This type of profiler has a platform code that ends in “SP” for “Surface Piercing”. |
| R0000\*               | Recovery folder, aka recovered data (downloaded after platform is recovered) |
| Recovered             | Data offloaded directly from an instrument or data logger; usually by connecting the instrument to a computer after the instrument has been recovered and writing to files, often onboard the recovery vessel. |
| Reference Designators | The machine-readable codes used to refer to arrays, sites, platforms, and instruments on the OOI. See reference sheet for site codes and the 5-letter instrument codes. |
| Streamed 	            | Data received via transmission over electro-optical cable. Streaming data are provided at full temporal resolution and near-real time. |
| Telemetered           | Data received through a transmission media over distance. Examples are: surface buoy to satellite, glider to satellite, acoustic modem. Data received through satellite relay or other mechanisms results in “batch” receipt and may be decimated in time. These data have greater latencies than the streaming data. |
| Uncabled 	            | Any platform (mooring, glider, or profiler) not attached to the electro-optical cable on the west coast |
| X0000\* 	            | Test data, collected on deck or during integration and burn-in testing. Use at your own risk. |
