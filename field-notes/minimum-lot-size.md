---
description: Core Field
---

# Minimum Lot Size

### Minimum Lot Size \(`MINLOTSIZE`\) 

* Associated Fields: `MNLS_SPEC`, `MNLS_OVE`, `MNLS_CALC`, `MNLS_EFF`, `MNLS_ESVAL` 
* Value Referenced In: `DUpAC_CALC1` , `DUpAC_CALC3`

This field catalogs the size of the smallest developable lot within a zone, in square feet. 

### Interpretation

In zones with multiple sets of dimensional regulations, the `MINLOTSIZE` value published in the Zoning Atlas corresponds with the greatest density use allowed in the zone by-right, as determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, or by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development.  

In zones with tiered minimum lot sizes, the `MINLOTSIZE` value published in the Zoning Atlas corresponds with the minimum lot size for the largest structure allowed by-right in that zone.

> Example: A zone with a maximum of six dwelling units per lot, which specifies a minimum lot size of 5,000SF for the first dwelling unit and then 2,500SF for each additional dwelling unit would have a `MINLOTSIZE` of 17,000SF, equal to \(5,000SF + \(2,500SF \* \(5 additional dwelling units\).

When we could not determine the largest structure allowed by-right in a zone, and thus could not reasonably calculate the applicable minimum lot size, we recorded the base value for `MINLOTSIZE`.  

### Estimation

`MINLOTSIZE` is populated for approximately 80% of the zones in the Zoning Atlas. 

MAPC was able to estimate minimum lot size for an additional 2% of the zones by multiplying the specified values for Maximum Dwelling Units \(`MAXDU`\) and Minimum Land Area per Dwelling Unit \(`LApDU`\). These estimates are in the `MNLS_CALC` field.

### Support

`MINLOTSIZE` is used in one estimation of maximum dwelling units per acre, `DUpAC_CALC1`. `MNLS_EFF` is used is a second estimation of maximum dwelling units per acre, `DUpAC_CALC3`.

