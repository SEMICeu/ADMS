April 2023 
 - initialise ADMS vocabulary 2.0
 - identify issue #3: adms:sample had as range adms:Asset, while in DCAT(-AP) it has range dcat:Distribution. This is incompatible.
   Resolved by changing the range to rdfs:Resource. 
 - identify issue #4: typo original RDF representation: schemeAgency must be schemaAgency ( the character e must be a).
 - use vCard:Kind instead of vCard:vCard to be in line with DCAT(-AP). Both classes are equivalent according to vCard vocabulary and can thus be used interchanged.
 - add section on motivation (based on the original)
 - add section DCAT profiling as example 
     In this section the original usage of ADMS is included.
     The terms from the original ADMS not belonging to the adms are moved to this section.
 - publish draft release for review

May 2023
 - address editorial remarks (sentences, typos, British spellcheck, prefixes, ...)
 - apply the solutions for issue #3 and issue #4.
 - change the class and property tabular specification so that the rows only appear when there is a value in the specification.
 - add new logo for SEMIC


