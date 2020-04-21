## Deployment, transect and section files
- Master "transect" (hydrographic line) JSON file: [NHD.json](https://github.com/nanoos-pnw/OOI/blob/master/gliders/NHD.json)
- Deployment files: [ce_319_00008_sections.json](https://github.com/nanoos-pnw/OOI/blob/master/gliders/ce_319_00008_sections.json), [ce_382_00005_sections.json](https://github.com/nanoos-pnw/OOI/blob/master/gliders/ce_382_00005_sections.json)
- NVS-style section file for NHD: [NHD_ce_319_00008_NVSsectionfile.txt](https://github.com/nanoos-pnw/OOI/blob/master/gliders/NHD_ce_319_00008_NVSsectionfile.txt). This file will be generated automatically by NANOOS from the transect and deployment JSON files
- Deployment file conventions
  1. There is only 1 dictionary key per hydro line in the `sections` dictionary in a deployment section JSON file
  2. Each line's list has section dictionary entries in chronological order
  3. The overall order going across multiple line elements is not necessarily in chronological order
  4. A consequence of 1, 2, and 3 is that there may be a time gap within a hydrographic line's list.
- Master "transect" (hydrographic line) JSON file conventions
  1. `deployments` list is in ascending chronological order.
- For active deployments, `datetime_end` and `recovery_date` are represented by `null`

## Glider DAC ERDDAP
- https://gliders.ioos.us/erddap/ (also https://data.ioos.us/gliders/erddap/)
- Data access page for ERDDAP dataset `ce_319-20190125T2248-delayed`: https://gliders.ioos.us/erddap/tabledap/ce_319-20190125T2248-delayed.html. This corresponds to OOI glider deployment file `ce_319_00008_sections.json`
