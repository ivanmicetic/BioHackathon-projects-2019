# Monday 2019-11-18

* discusses BridgeDb<>identifiers.org with Nick, including use of MIRIAM and enhancement of compact identifiers
* Egon, Petros: discussed an attack plan to get the BridgeDb IMS Docker working again
   * worked on updating MySQL, but this requires completion of the `@Tag("mysql")` (the tests time out, a bug)
* Denise: worked on SPARQL to [count how many genes from a list occur in one or more pathways](https://www.wikipathways.org/index.php/Help:WikiPathways_Sparql_queries#Count_how_many_genes_from_a_list_occur_in_one_or_more_pathways)
* Emma: worked on PubChemLite evaluation, benchmarking subsets of [PubChem](https://pubchem.ncbi.nlm.nih.gov/) against [MassBank-data](https://github.com/MassBank/MassBank-data/) (starting with [CASMI2016](http://casmi-contest.org/2016/solutions-cat2+3.shtml))

# Tuesday 2019-11-19

* Travis now runs the tests for BridgeDb git master (but not webservices, mysql)
