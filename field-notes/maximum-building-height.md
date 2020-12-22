---
description: Core Field
---

# Maximum Building Height

### Maximum Building Height \(`MAXHEIGHT`\)  

* Associated Fields: `MXHT_SPEC`, `MXHT_CALC`, `MXHT_EFF`, `MXHT_ESVAL` 
* Value Referenced In: `MXFL_CALC` 

This field catalogs the maximum allowable building height, in feet. 

### Interpretation

As with other dimensional fields in the Zoning Atlas, in zones with multiple sets of dimensional regulations, the published value corresponds with the greatest density use allowed in the zone by-right.  Greatest density is determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, or by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development. 

### Estimation

`MAXHEIGHT` is populated for approximately 80% of the zones in the Zoning Atlas. 

Where a maximum building height was not specified in the Bylaw or Ordinance, MAPC provided an estimate in the Calculated Maximum Height \(`MXHT_CALC`\) field by multiplying the value in the Maximum Floors \(`MXFLRS`\) field by 10 feet and rounding down. 

### Support

`MAXHEIGHT` is used to estimate Maximum Building Floors.

