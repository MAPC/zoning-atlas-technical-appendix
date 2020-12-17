---
description: Support Field
---

# Maximum Building Floors

### Maximum Building Floors \(`MAXFLRS`\) 

* Associated Fields: `MXFL_SPEC`, `MXFL_CALC`, `MXFL_EFF`, `MXFL_ESVAL` 
* Value Referenced In: `MXHT_CALC`, `MXDU_CALC3`, `FAR_CALC` 

This field catalogues the maximum allowable building floors, or stories. As with other dimensional regulations in the Zoning Atlas, the published value corresponds with the dimensional regulations of the greatest density use. 

`MAXFLRS` is populated for approximately 50% of the zones in the Atlas. Where `MAXFLRS` was not specified in the Bylaw or Ordinance, MAPC provided an estimate in the Calculated Maximum Floors  \(`MXFL_CALC`\) field by dividing `MAXHEIGHT` by 10 feet and rounding down. `MAXFLRS` is used to estimate `MAXHEIGHT`. The value in the Effective Maximum Floors \(`MXFL_EFF`\) field is used in one estimation of Maximum Dwelling Units and in the estimation for FAR. 

