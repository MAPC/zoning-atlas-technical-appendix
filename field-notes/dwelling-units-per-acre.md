---
description: Core Field
---

# Dwelling Units per Acre

### Dwelling Units per Acre \(`DUpAC`\) 

* Associated Fields: `DUpAC_SPEC`, `DUpAC_OVE`, `DUpAC_CALC1`, `DUpAC_CALC2`, 

  `DUpAC_CALC3`, `DUpAC_EFF`, `DUpAC_ESVAL` 

* Value Referenced In: N/A 

This field catalogs the maximum allowable dwelling unit density, in terms of dwelling units per acre. This allows a standardized comparison of density across zones where residential development is allowed by-right.

#### Estimation

`DUpAC` is populated for approximately 20% of the zones in the Zoning Atlas where residential development is allowed by-right. 

Where dwelling units per acre was not specified in the Bylaw or Ordinance, MAPC was able to approximate it for an additional 70% of zones using three different formula fields:

* `DUpAC_CALC1`: If both `MAXDU` and `MINLOTSIZE` are specified, dwelling units per acre are estimated by calculating the number of lots that could be constructed on an acre \(43,560SF/`MINLOTSIZE`\) and multiplying this number by the maximum dwelling units for each of those lots, `MAXDU`. This calculation yielded an estimate for approximately 40% of zones.
* `DUpAC_CALC2`: If `FAR` is specified, dwelling units per acre are estimated by calculating the maximum building square footage for a one-acre lot \(43,560SF \* `FAR`\) and dividing this figure by the estimated `SFpDU`, 1,000SF.  The calculation yielded an estimate for approximately 25% of zones.
* `DUpAC_CALC3`: If neither `MAXDU`, `MINLOTSIZE,` or `FAR` were specified, MAPC used the same estimation method as DUpAC\_CALC1, but replaced specified values with estimated values: \(43,560SF /`MNLS_EFF`\) \* `MXDU_EFF`. This calculated yielded an estimate for approximately 5% of zones.

The remaining 10% of the zones in the Zoning Atlas where residential development is allowed by-right have an estimate in the `DUpAC_OVE` field. In some instances, values are popualted because the three formula fields did not yield an estimate; in others, the formula fields yielded a result that was obviously inaccurate. One example of this is a zone with a specified `MINLOTSIZE` of 1, which had a DUpAC\_CALC1 value of over 80,000. This 

