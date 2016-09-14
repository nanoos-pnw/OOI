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
