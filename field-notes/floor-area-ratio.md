---
description: Core Field
---

# Floor-area Ratio

### Floor-area Ratio \(`FAR`\) 

* Associated Fields: `FAR_SPEC`, `FAR_OVE`, `FAR_CALC`, `FAR_EFF` 
* Value Referenced In: `MXDU_CALC2`, `DUpAC_CALC2` 

This field catalogs the maximum FAR allowed in a zone by-right. This allows a standardized comparison of density across zones that allow non-residential uses.  

#### Estimation

Approximately 60% of the zones in the Atlas where non-residential uses are allowed by-right have a FAR sourced from a Bylaw or Ordinance; the same is true for approximately 35% of the zones where only residential uses are allowed by-right.

MAPC estimated FAR for zones where non-residential uses are allowed by-right by multiplying maximum percent lot coverage by maximum floors. We were able to estimate FAR for about 50% of these zones using values specified in the Bylaw or Ordinance, `PCTLOTCOV` and `MXFLRS,` but did use estimated reference values, `PLC_EFF` and `MXFL_EFF`, for about 40%. 

The remaining 10% of zones in the Zoning Atlas where non-residential uses are allowed by-right have an estimate in the `FAR_OVE` field.      

