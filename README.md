# RTT NR Reference Data
This repository contains the reference data used by the Realtime Trains platform for Network Rail.

This data is periodically updated on the RTT website.

## Licence
This is licenced under a Creative Commons CC-BY licence. 

## File Information

| Filename      | Usage |
| ------------- | ----- |
| activities.csv | Decodes CIF activity codes to content (used internally only) |
| activities_public_detailed.csv | Decodes CIF activity codes to content - used on detailed mode train pages |
| activities_public_simple.csv | Decodes CIF activity codes to content - used on simple mode train pages |
| areas.csv     | Used on our status page to show the availability of TD data for each area (20 character limit) |
| attribution.csv | The delay code translations used on the RTT website, with long names used on train pages and short names being used on location pages |
| categories.csv | Used to translate status and category codes into names |
| operators.csv | Used to decode TOC codes to operator names. Long names are used in most locations, short names are used where we are also using another data item (such as a fleet name.) |
| vehicle_branding.csv | Used to map TOC-class combinations to branding names |
| vehicle_mapping.csv | Used to map vehicle TOPS numbers to their actual running names (used for heritage vehicles) |
