---
description: The section of the technical documentation pertains to base zoning districts.
---

# Field Structure

The lack of specified data for many of the core fields, and the corresponding addition of standardized estimation methods, led to the following six-part structure for each one of the core fields and many of the support fields: 

### 1. Zone Value

This field is populated when a dimensional regulation is specified in the bylaw or ordinance, otherwise, it is left blank. 

### 2. Calculated Value\(s\)

For each core field and many support fields, there are one to three associated fields with estimates of that value. These estimates are calculated using set formulas that reference dimensional regulations that are specified in the bylaw or ordinance; there are multiple Calculated Value\(s\) when it was not possible to estimate all unspecified Zone Values with a single method because the referenced regulations were not uniformly available. Calculated Value fields are populated even if a Zone Value is specified, provided the referenced regulations are in place. Fields in this category end “\_CALC.” 

### 3. Override Value

This field is populated when the Calculated Value field\(s\) do not yield an estimate for the dimensional regulation because the required referenced regulations are incomplete. There are a few instances in the database where an Override Value is provided because the calculated value seemed to be inaccurate.  Fields in this category end “\_OVE.” 

### 4. Effective Value

This field compresses the preceding fields \(Zone Value, Calculated Value\(s\), and Override Value\) into a single number that can be used for an approximate comparison. If an Override Value is specified, the Effective Value will be this number; otherwise, it will be the Zone Value, then the Calculated Value1, then 2, then 3. Fields in this category end “\_EFF.” 

### 5. Specification Description

This single select field captures if and how a dimensional regulation is included in the bylaw or ordinance: a dimensional regulation referenced in the zoning code but where the maximum \(or minimum\) value is specified with a formula, a dimensional regulation referenced in the zoning code but where a value is not defined for that district, and a dimensional regulation that is not referenced in the zoning code. Null values reflect instances where a Specification Description is not yet populated. Fields in this category end “\_SPEC.”  

### 6. Estimation Indicator

This formula field identifies whether the Effective Value is equal to the Zone Value. Fields in this category end “\_ESVAL.” 

