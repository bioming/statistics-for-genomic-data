# statistics-for-genomic-data
notes for statistics in analyzing genomic data
## choose a suitable statistics for your genomic analysis

### Fst: a measure of population differentiation due to genetic structure (originated from popoolation and wikipedia)
By default Fst is calculated from the allele-frequencies (not from the allele-counts) using the standard equation as shown in "Hartl and Clark (2007): Principles of Population Genetics"
 
 Fst = (Pi_total - Pi_within) / Pi_total
 Pi_within = (Pi_population1 + Pi_population2)/ 2
 Pi: 1 - fA ^ 2 - fT ^ 2 -fC ^ 2 - fG ^ 2
 fN:  frequency of nucleotide N
 Pi_total: for the total Pi the allele frequencies of the two
     populations are averaged and Pi is calculated as shown above

if the alternative method C<--karlsson-fst> is used, Fst is calculated  from the allele-counts according to:
Karlsson et al. (2007): Efficient mapping of mendelian traits in dogs through genome-wide association, Nature genetics

### Fisher's Test: 
