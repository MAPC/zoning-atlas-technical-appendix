---
description: Support Field
---

# Maximum Building Floors

### Maximum Building Floors \(`MAXFLRS`\) 

* Associated Fields: `MXFL_SPEC`, `MXFL_CALC`, `MXFL_EFF`, `MXFL_ESVAL` 
* Value Referenced In: `MXHT_CALC`, `MXDU_CALC3`, `FAR_CALC` 

This field catalogs the maximum allowable building floors, or stories. 

#### Interpretation

As with other dimensional regulations in the Zoning Atlas, in zones with multiple sets of dimensional regulations, the published value corresponds with the greatest density use allowed in the zone by-right.  Greatest density is determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, and by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development.  

#### Scope

`MAXFLRS` is populated for approximately 50% of the zones in the Atlas. Where `MAXFLRS` was not specified in the Bylaw or Ordinance, MAPC provided an estimate in the Calculated Maximum Floors  \(`MXFL_CALC`\) field by dividing `MAXHEIGHT` by 10 feet and rounding down. `MAXFLRS` is used to estimate `MAXHEIGHT`. The value in the Effective Maximum Floors \(`MXFL_EFF`\) field is used in one estimation of Maximum Dwelling Units and in the estimation for FAR. 

`MAXFLRS` is used to estimate `MAXHEIGHT.` The value in the Effective Maximum Floors \(`MXFL_EFF`\) field is used in one estimation of Maximum Dwelling Units and in the estimation for FAR.

