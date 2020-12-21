---
description: Support Field
---

# Minimum Land Area per Dwelling Unit

### Minimum Land Area per Dwelling Unit \(`LApDU`\) 

* Associated Fields: `LApDU_SPEC` 
* Value Referenced In: `MNLS_CALC`, `MXDU_CALC1` 

This field catalogs the minimum amount of lot area required for each dwelling unit on a lot within a zone, in square feet. 

#### Interpretation

As with other dimensional regulations in the Zoning Atlas, in zones with multiple sets of dimensional regulations, the published value corresponds with the greatest density use allowed in the zone by-right.  Greatest density is determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, and by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development.  

As with [Minimum Lot Size](minimum-lot-size.md), in zones with tiered minimum land area per dwelling unit, the  `LApDU` value published in the Zoning Atlas corresponds with the requirement applicable to the greatest number of dwelling units.

> Example: A zone with an minimum land area per dwelling unit of 6,000SF plus 1,250SF for each dwelling unit more than 1 would have an `LApDU` of 1,250SF.

#### Scope

LApDU is populated for approximately 40% of the zones in the Atlas where residential development is allowed by-right. There is not currently a field where unspecified values are estimated.

