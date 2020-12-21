---
description: Core Field
---

# Dwelling Units per Acre

### Dwelling Units per Acre \(`DUpAC`\) 

* Associated Fields: `DUpAC_SPEC`, `DUpAC_OVE`, `DUpAC_CALC1`, `DUpAC_CALC2`, `DUpAC_EFF`, `DUpAC_ESVAL` 
* Value Referenced In: N/A 

This field catalogs the maximum allowable dwelling unit density in terms of dwelling units per acre. This allows a standardized comparison of density across zones that allow residential uses. 

#### Estimation

`DUpAC` is populated for approximately 20% of the zones in the Atlas where residential development is allowed by-right. 

`DUpAC`can also be expressed in terms of `MAXDU` and `MINLOTSIZE`, so we were able to calculate `DUpAC` for an additional 35% of zones by calculating the number of lots that could be constructed on an acre \(43,560SF /`MINLOTSIZE`\) and multiplying by `MAXDU`. These `DUpAC` estimates are in `DUpAC_CALC1`. 

For the 45% zones in the Atlas where residential development is allowed by-right, but where `DUpAC`, `MINLOTSIZE`, and `MAXDU` were not specified, MAPC was able to estimate `DUpAC` using two different methods:  

* `DUpAC_CALC2`: If `FAR` is greater than 0, dwelling units per acre are estimated by calculating the maximum building square footage for a one-acre lot \(43,560SF \* `FAR`\) and dividing this figure by the estimated `SFpDU`.  
* `DUpAC_CALC3`: If estimated maximum dwelling units and estimated minimum lot size are both greater than 0, dwelling units per acre by calculating the number of lots that count be constructed on an acre \(43,560SF /`MNLS_EFF`\) and multiplying by `MXDU_EFF`. \(This calculation method is the same as the `DUpAC_CALC1`, but relies on estimated reference values. 

