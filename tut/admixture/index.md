# Structure Plots

## Data input format

Genesis requires two input files and an optional third file:
- An admixture file which contains on each line the estimated ancestral proportions of
each individual. Typically, this would be produced by a program like Admixture (e.g,
and admixture Q file), or CLUMPP, the output formats of which Genesis supports
natively. For example, an Admixture Q file for K=4, contains four columns. Provided
the input is a legal format, Genesis will automatically work out what input file it is,
and what the K value is. Instructions on using the structure2CLUMPP script which
can be used for Structure input files is described later.

- A plink-style fam file. The first two columns must uniquely identify the individuals
(the first column is usually the family identifier, the second the individual identifier).
See the plink manual for further description. The j-th line of this fam file describes the
j-th individual in the admixture file. This all that Genesis requires, although fam files
typically have other columns as well.

- Optionally, a phenotype file: again, the first two columns indentify the individual, and
subsequent columns label the individuals (e.g., case/control, male/female, population
group, language, etc). The individual identifiers should be the same as in the fam file:
each individual in the fam file should also be in the phentoype file, but there is no
problem in having individuals in the phenotype file who are not in the fam file. The
order of entries in the phenotype file need not be the same as in the fam file. You could
use the same file as the fam and the phenotype file.

## Inputting Data