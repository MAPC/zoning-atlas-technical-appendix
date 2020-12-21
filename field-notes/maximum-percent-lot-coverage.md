---
description: Support Field
---

# Maximum Percent Lot Coverage

### Maximum Percent Lot Coverage \(`PCTLOTCOV`\) 

* Associated Fields: `PLC_SPEC`, `PLC_OVE`, `PLC_CALC`, `PLC_EFF`, `PLC_ESVAL` 
* Value Referenced In: `FAR_CALC` 

This field catalogs the maximum amount of the lot that can be covered by structures, as a percentage of the lot. 

#### Interpretation

As with other dimensional regulations in the Zoning Atlas, in zones with multiple sets of dimensional regulations, the published value corresponds with the greatest density use allowed in the zone by-right.  Greatest density is determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, and by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development.  

#### Scope

`PCTLOTCOV` is populated for approximately 60% of the zones in the Atlas. For the 40% of zones without a specified maximum percent lot coverage, MAPC estimated this value as 100%. These estimated values are calculated in the `PLC_CALC` field.

There are 20 instances where this estimate is superseded by an override value in the `PLC_OVE` field that draws on minimum setbacks.



