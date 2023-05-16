April 2023 
 - initialise ADMS vocabulary 2.0
 - ISSUE > adms:sample had as range adms:Asset, while in DCAT(-AP) it has range dcat:Distribution. This is incompatible.
   Resolved by changing the range to rdfs:Resource. 
 - ISSUE > fix typo original RDF representation:
	schemeAgency must be schemaAgency ( the character e must be a).
 - use vCard:Kind instead of vCard:vCard to be in line with DCAT(-AP). Both classes are equivalent according to vCard vocabulary and can thus be used interchanged.
 - add section on motivation (based on the original)
 - add section DCAT profiling as example 
     In this section the original usage of ADMS is included.
     The terms from the original ADMS not belonging to the adms are moved to this section.
