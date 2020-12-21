---
description: Core Field
---

# Multifamily Housing

### Multifamily \(`MULFAM2`, `MULFAM3_4`, `MULFAM5_19`, `MULFAM20_`\) 

The four multifamily fields describe whether multifamily housing is allowed on a lot within a given zone, and if so, whether this housing is allowed by \(1\) Special Permit or \(2\) By-right. A value of \(0\) means multifamily housing is never permitted.

The four multifamily fields use this structure for different housing unit thresholds: 

* `MULFAM2`: 2 or more units by Special Permit or By-right
* `MULFAM3_4`: 3 to 4 units by Special Permit or By-right
* `MULFAM5_19`: 5 to 19 units by Special Permit or By-right
* `MULFAM20_`: 20 or more units by Special Permit or By-right

The multifamily fields are the only fields in the database that capture special permit information. 

In populating the multifamily fields, we found several zones where multifamily housing was allowed by-right, but only in unique instances, such as in a conversion of an existing single-family home to a two-family home or when the occupants of the building were elderly and low-income. MAPC generally did not classify these zones as by-right multifamily zones because multifamily housing was not universally permitted.   

{% hint style="info" %}
Multifamily is populated for all zones in the Atlas. 
{% endhint %}



