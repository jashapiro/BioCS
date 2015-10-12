# Assignment Ideas

## Modeling Life:
* [Assignment 1](https://athena.brynmawr.edu/jupyter/hub/dblank/public//BioCS/notebooks/Lab01.ipynb): Move to find food 
  * picobot
  * rules to cover space
  * 
* [Assignment 2](https://athena.brynmawr.edu/jupyter/hub/dblank/public//BioCS/notebooks/Lab02.ipynb): Move randomly to find food. 
  * if() statements and loops
  * Optimal foraging theory: 
    * energy use
    * distributions of food

## DNA statistics:
* Assignment 3: GC counting
  * Count from a string
  * functions to count form a string (one argument, one output)
  * Break long sequence into windows
    * keep track of position and GC content
  * variables, math & plotting (basic graphics)
  * Biology questions
    * variation across a genome
    * coding vs. noncoding regions
    * Is GC appropriate for RNA


* Assignment 4: Translation and (identifying coding regions)
  * arrays, dictionaries, file access
  * File with one gene per fasta record 
    * Testing & debugging
  * DNA transcription and translation
  * Codon counting & position: integer division & modulus
  * Advanced: identify coding by presence of transcription start site

* Assignment 5: Mutations
  * Randomly mutate a DNA sequence (random numbers/pseudorandom)
  * Translate the new sequence
  * modulo arithmetic
  * What proportion of mutations change the protein sequence? Does this depend on the sequence?

* Assignment 6: Evolving agents
  * population of genotypes
  * calculate/simulate phenotype
  * ladybug that survives longest reproduces w/mutations
  * Repeat simulations & look at variation in winners
  * max fitness vs. sorted fitness


----------------------
Exam I
----------------------

## Population genetics
* Assignment 7: Random genetic drift
  * 2 allele model: fixation depends on starting frequency
  * selecting randomly from an array
  * infinite alleles model (or infinite sites)
  * sorting
    * recursion
    * divide and conquer
  * Biology questions:
    * population size variation
    * starting frequency variation
    * time to fixation
    * mutation-drift balance  

* Assignment 8: Natural selection / Individuals
  * Objects: Individuals with one or two DNA sequences
    * mating & reproduction
    * fitness function (additive vs dominance)
  * How does fixation speed/probability depend on selection & population size?
  * Selection with mutation : calculate fitness as a function of match to protein sequence

* Assignment 9: Learning / Plasticity
  * Neural network training

* Assignment 10:
  * Full Ladybug simulation
  * Evolution as an effective search 


# Project Ideas

* Dynamic models
  * simulating outbreaks (SIRS model)
  * expand population genetics/evolution model
  * Predator prey systems: Lotka-Volterra
  * Lac operon dynamics

* Spatial Models
  * spreading disease
  * dispersal models
  * evolution in space

* Bioinformatics topics
  * gene expression
  * genome variation (dinucleotides, trinucleotides)
  * big data analysis

* Agent-based robotics






## Other assignment ideas

## Sequence alignment
* Assignment: Calculate similarity score for an alignment
  * Affine vs fixed gap penalties
  * DNA vs protein

* Assignment: Global/or local alignment
  * Arrays & references

* Assignment: Local alignment

* Assignment XX Mutations and drift
  * Combine mutations in DNA sequence with drift
  * Calculate allele frequencies in the population
  * Infinite sites vs. finite sites.
  * Neutral Allele frequency spectrum

* Assignment X: Haploid & Diploid

  * fitness of diploids: additive vs dominant/recessive
  * modify previous code to simulate individuals, rather than alleles
  * Diploids need to mate to reproduce: pick two parents per next generation individual

* Assignment X: Recombination
  * Mating between diploid individuals
  * Recombination before mating
  * Effect of recombination on speed of adaptation/selection
