# Minimum Lot Size

### Minimum Lot Size \(`MINLOTSIZE`\) 

* Associated Fields: MNLS\_SPEC, MNLS\_OVE, MNLS\_CALC, MNLS\_EFF, MNLS\_ESVAL 
* Value Referenced In: DUpAC\_CALC1 

As noted above, the MINLOTSIZE value published in the Atlas corresponds with the greatest density use allowed in the zone by-right, as determined by Maximum Dwelling Units per Acre, in the case of residential development, or by FAR, in the case of mixed use or non-residential development.  

In populating the MINLOTSIZE field, we found several zones with tiered minimum lot sizes. For example, a minimum lot size of 5,000SF for the first dwelling unit and then 2,500SF for each additional dwelling unit. In these instances, we would try to determine the applicable MINLOTSIZE for the largest structure allowed by-right in that zone – in this example, the maximum number of dwelling units, 6 – and, if it was available, scale the recorded value of MINLOTSIZE to fit \(5,000SF + \(2,500SF \* \(6 - 1\) = 17,500SF\). When we could not determine the largest structure allowed by-right, and thus could not reasonably calculate this upper bound, we recorded the base value.  

MINLOTSIZE is populated for approximately 80% of the zones in the Atlas. MAPC was able to estimate minimum lot size for an additional 2% of the zones in the Atlas by multiplying the specified values for Maximum Dwelling Units and Minimum Land Area per Dwelling Unit. These estimated values are in the MNLS\_EST field.  

