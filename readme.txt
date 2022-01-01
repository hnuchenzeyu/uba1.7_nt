####################################################
Univ-Bench Artificial Data Generator (UBA)
  Version 1.7
  Modify to generate N-Triple format file.
  The original site: http://swat.cse.lehigh.edu/projects/lubm/
####################################################

==================
USAGES
==================

command:
   edu.lehigh.swat.bench.uba.Generator
      	[-univ <univ_num>]
	[-index <starting_index>]
	[-seed <seed>]
	[-daml]

options:
   -univ number of universities to generate; 1 by default
   -index starting index of the universities; 0 by default
   -seed seed used for random data generation; 0 by default
   -daml generate DAML+OIL data; OWL data by default

output:
   Generate Lubm.nt

- The package's path should be on CLASSPATH.

For more information about the benchmark, visit its homepage http://www.lehigh.edu/~yug2/Research/SemanticWeb/LUBM/LUBM.htm.
