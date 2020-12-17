---
description: Core Field
---

# Minimum Lot Size

### Minimum Lot Size \(`MINLOTSIZE`\) 

* Associated Fields: `MNLS_SPEC`, `MNLS_OVE`, `MNLS_CALC`, `MNLS_EFF`, `MNLS_ESVAL` 
* Value Referenced In: `DUpAC_CALC1` 

The `MINLOTSIZE` value published in the Zoning Atlas corresponds with the greatest density use allowed in the zone by-right, as determined by maximum dwelling units per acre \(`DUpAC`\), in the case of residential development, or by the floor-area ratio \(`FAR`\), in the case of mixed-use or non-residential development.  

We found several bylaws and ordinances with tiered minimum lot sizes. For example, a minimum lot size of 5,000SF for the first dwelling unit and then 2,500SF for each additional dwelling unit. In these instances, we would try to determine the applicable minimum lot size for the largest structure allowed by-right in that zone – in this example, the maximum number of dwelling units, 6 – and, if it was available, scale the recorded value of `MINLOTSIZE` to fit \(5,000SF + \(2,500SF \* \(6 - 1\) = 17,500SF\). When we could not determine the largest structure allowed by-right, and thus could not reasonably calculate this upper bound, we recorded the base value.  

> Example: A zone with a maximum of six dwelling units per lot, which specifies a minimum lot size of 5,000SF for the first dwelling unit and then 2,500SF for each additional dwelling unit would have a `MINLOTSIZE` of 17,000SF, equal to \(5,000SF + \(2,500SF \* \(6 - 1\).

When we could not determine the largest structure allowed by-right, and thus could not reasonably calculate this upper bound, we recorded the base value.  

{% hint style="info" %}
MINLOTSIZE is populated for approximately 80% of the zones in the Atlas. MAPC was able to estimate minimum lot size for an additional 2% of the zones in the Atlas by multiplying the specified values for Maximum Dwelling Units and Minimum Land Area per Dwelling Unit. These estimated values are in the `MNLS_EST` field.
{% endhint %}

  

