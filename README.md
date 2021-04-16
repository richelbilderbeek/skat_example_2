# skat_example_2

Branch   |[![GitHub Actions logo](GitHubActions.png)](https://github.com/richelbilderbeek/skat_example_2/actions)
---------|-------------------------------------------------------------------------------------------------------------------
`master` |![R-CMD-check](https://github.com/richelbilderbeek/skat_example_2/workflows/R-CMD-check/badge.svg?branch=master) 
`develop`|![R-CMD-check](https://github.com/richelbilderbeek/skat_example_2/workflows/R-CMD-check/badge.svg?branch=develop)

SKAT example 2.

This example is a mix of simulation and imputation.
The assumptions, however, I think are invalid:
the phenotype is simulated to depend on the number of the minor SNPs 
within a genotype.
This is not how GWAS imputation works: instead there
should be one SNP that does correlate to a phenotype,
where the others are just noise.

