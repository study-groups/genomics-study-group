# genomics-study-group


This is a self-study guide for learning [genomics](https://www.genome.gov/about-genomics/fact-sheets/A-Brief-Guide-to-Genomics). The fundamentals of bioinformatic data science are based on [information theory](https://bioinformaticshome.com/bioinformatics_tutorials/sequence_alignment/introduction_to_information_theory.html)  and [sequential sequence processing](./papers/2007-BootstrapParticleFilteringSPMagCandy.pdf).

The StatQuest video [A gentle introduction to RNA-seq](https://www.youtube.com/watch?v=tlf6wYJrwKY) by Josh Starmer is a good introduction to the field of applied bioinformatics, specifically indentifying and relating sequences of base pairs from [PCR](https://www.youtube.com/watch?v=7beN35g5xuM).

Gene folding is more complex, [Demis Hassabis of Deep Mind](https://lexfridman.com/demis-hassabis/) frames the next 50 years of work. For technical background, [Principles of protein folding--a perspective from simple exact models](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2143098) is a decent 
technincal starting place.


A practical nexus of gene sequencing and protien folding is the the [Blast site at Ncbi](https://blast.ncbi.nlm.nih.gov/Blast.cgi). This is a [good video](https://youtu.be/WRKQGwh_Mw0) that explains the Blast site.

The [Rosalind](http://rosalind.info/problems/tree-view/) project provides challenge problems as described by [Bioinformatics Algorithms](https://www.bioinformaticsalgorithms.org/) by Phillip Compeau and Pavel Pevzner.

Transformers are at the heart of everything. Here is DeepMind's [AlphaFold 2 Explained](https://www.youtube.com/watch?v=B9PL__gVxLI) by Y. Kikcher.

## 2023 Currently Reviewing:

- [Node embedding for Predictin Disease Genes](https://github.com/lucacareddu/Comparing-node-embedding-methods-and-classifiers-for-predicting-disease-genes):  Python code of the work done for the masters project "Learning from Networks". Uses Karate Klub for graph embeddings.

- [Brown, CS 181: Computational Molecular Biology](http://cs.brown.edu/courses/cs181/lectures.html): decent college level course on DNA sequencing.

## Subject definitions
- [DNA Sequencing](https://en.wikipedia.org/wiki/DNA_sequencing) is the process of determining the nucleic acid sequence – the order of nucleotides in DNA. It includes any method or technology that is used to determine the order of the four bases: adenine, guanine, cytosine, and thymine. The advent of rapid DNA sequencing methods has greatly accelerated biological and medical research and discovery.

- [Sanger Sequencing](https://en.wikipedia.org/wiki/Sanger_sequencing) is a method of DNA sequencing. Developed by Frederick Sanger and colleagues in 1977, it was the most widely used sequencing method for approximately 40 years.  More recently, higher volume Sanger sequencing has been replaced by ["Next-Gen" sequencing methods](https://www.illumina.com/content/dam/illumina-marketing/documents/products/illumina_sequencing_introduction.pdf).

- [Systems Biology](https://en.wikipedia.org/wiki/Systems_biology) is the computational and mathematical modeling of complex biological systems. It is a biology-based interdisciplinary field of study that focuses on complex interactions within biological systems, using a holistic approach (holism instead of the more traditional reductionism) to biological research.

- [Genomics](https://en.wikipedia.org/wiki/Genomics) is an interdisciplinary field of science focusing on the structure, function, evolution, mapping, and editing of genomes. A genome is an organism's complete set of DNA, including all of its genes. In contrast to genetics, which refers to the study of individual genes and their roles in inheritance, genomics aims at the collective characterization and quantification of genes, which direct the production of proteins with the assistance of enzymes and messenger molecules.

- [Genomic Signal Processing](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2766787/): defined by Edward Dougherty. Genomic Signal Processing (GSP) has been defined as the analysis, processing, and use of genomic signals for gaining biological knowledge and the translation of that knowledge into systems-based applications, where by genomic signals we mean the measurable events, principally the production of mRNA and protein carried out within the cell. Clever formalization by D. Anastassiou, [Genomic Signal Processing](https://github.com/study-groups/bioinformatics-study-group/tree/main/papers/2001-Genomic-Signal-Processing-Anastassiou.pdf)

## Videos

- [Careers in Bioinformatics and Precision Medicine - Career Development Week](https://youtu.be/UuSFWlohYEg): by Semyon Kruglyak. Precision medicine integrates molecular and clinical research with patient data and outcomes, aiming to place the patient at the center of all elements. In this emerging field, bioinformatics is a core technology. Learn how bioinformatics has evolved to deal with Next Gen Sequencing data and explore new career opportunities for biomedical and clinical researchers. Recorded on 03/25/2014.

- [From the Human Genome Project to Precision Medicine: A Journey to Advance Human Health](https://www.youtube.com/watch?v=M9OGNXwCq3c):by Eric D. Green, Director, National Human Genome Research Institute. Dr. Green is the founding director of the NIH Intramural Sequencing Center (1997-2009). Prior to that, he played an integral role in the Human Genome Project.


# Start here for serious study

- MIT Open Courseware's [Foundations of Computational And-Systems Biology, Spring 2014](https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/index.htm). 
This course is an introduction to computational biology emphasizing the fundamentals of nucleic acid and protein sequence and structural analysis; it also includes an introduction to the analysis of complex biological systems. Topics covered in the course include principles and methods used for sequence alignment, motif finding, structural modeling, structure prediction and network modeling, as well as currently emerging research areas. [Video Lectures from Spring 2014 at MIT](https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/video-lectures/).

## Coursera

Bioinformatics as taught by Pavel Pevzner and Phillip Compeau of California San Diego.

- [Bioinformatics I: Finding Hidden Messages in DNA](https://www.coursera.org/learn/dna-analysis): In the first half of the course, we investigate DNA replication, and ask the question, where in the genome does DNA replication begin?  We will see that we can answer this question for many bacteria using only some straightforward algorithms to look for hidden messages in the genome. In the second half of the course, we examine a different biological question, when we ask which DNA patterns play the role of molecular clocks.  The cells in your body manage to maintain a circadian rhythm, but how is this achieved on the level of DNA? 

- [Bioinformatics II: Genome Sequencing](https://www.coursera.org/learn/genome-sequencing): Biologists still cannot read the nucleotides of an entire genome as you would read a book from beginning to end. However, they can read short pieces of DNA. In this course, we will see how graph theory can be used to assemble genomes from these short pieces. We will further learn about brute force algorithms and apply them to sequencing mini-proteins called antibiotics. 

- [Bioinformatics III: Comparing Genes, Proteins, and Genomes](https://www.coursera.org/learn/comparing-genomes):Once we have sequenced genomes in the previous course, we would like to compare them to determine how species have evolved and what makes them different.

- [Bioinformatics IV:  Molecular Evolution](https://www.coursera.org/learn/molecular-evolution): One way we can use these methods is in order to construct a "Tree of Life" showing how a large collection of related organisms have evolved over time.

- [Bioinformatics V: Genomic Data Science and Clustering](https://www.coursera.org/learn/genomic-data): How do we infer which genes orchestrate various processes in the cell?  How did humans migrate out of Africa and spread around the world? In this class, we will see that these two seemingly different questions can be addressed using similar algorithmic and machine learning techniques arising from the general problem of dividing data points into distinct clusters.

- [Bioinformatics VI: Finding Mutations in DNA and Proteins](https://www.coursera.org/learn/dna-mutations): This course will cover advanced topics in finding mutations lurking within DNA and proteins. The approach we will use is based on a powerful machine learning tool called a hidden Markov model.

### Other online courses

- [DIY Transcriptomics](http://diytranscriptomics.com/): A virtual asynchronous course covering best practices for RNAseq data analysis, uses R/bioconductor environment.

- [RNA-Seq with Bioconductor in R](https://www.datacamp.com/courses/rna-seq-with-bioconductor-in-r): We will start the course with a brief overview of the RNA-Seq workflow with an emphasis on [differential expression (DE) analysis](https://bioconductor.org/packages/release/workflows/vignettes/rnaseqGene/inst/doc/rnaseqGene.html).  The DESeq2 R package will be used to model the count data using a negative binomial model and test for differentially expressed genes.

## Papers

- [Evaluating Protein Transfer Learning with TAPE](https://www.biorxiv.org/content/10.1101/676825v1): 
Protein modeling is an increasingly popular area of machine learning research. Semi-supervised learning has emerged as an important paradigm in protein modeling due to the high cost of acquiring supervised protein labels, but the current literature is fragmented when it comes to datasets and standardized evaluation techniques. To facilitate progress in this field, we introduce the Tasks Assessing Protein Embeddings (TAPE), a set of five biologically relevant semi-supervised learning tasks spread across different domains of protein biology. We curate tasks into specific training, validation, and test splits to ensure that each task tests biologically relevant generalization that transfers to real-life scenarios. Available at [tape repo](https://github.com/songlab-cal/tape).

- [2000-FrequencyDomainAnalysisOfBiomolecularSequencesAnastassiou](./papers/2000-FrequencyDomainAnalysisOfBiomolecularSequencesAnastassiou.pdf): by Dimitiris Anastassiou. Applies DFT to RNA to distinguish coding from non-conding regions in DNA sequences.

- [RNA sequencing data: hitchhiker's guide
to expression analysis](./papers/2018-RnaSequencingDataHitchhikersGuideLoveEtal.pdf) Gene expression is the fundamental level at which the result of various genetic and regulatory programs are observable. The measurement of transcriptome­wide gene expression has convincingly switched from microarrays to sequencing in a matter of years. RNA sequencing (RNA­seq) provides a quantitative and open system for profiling transcriptional outcomes on a large scale and therefore facilitates a large diversity of applications, including basic science studies, but also agricultural or clinical situations.

- [2001 A computational analysis of sequence features involved in recognition of short introns](https://www.pnas.org/content/98/20/11193) by Lim and Burge. "Splicing of short introns by the nuclear pre-mRNA splicing machinery is thought to proceed via an “intron definition” mechanism, in which the 5′ and 3′ splice sites (5′ss, 3′ss, respectively) are initially recognized and paired across the intron. Here, we describe a computational analysis of sequence features involved in recognition of short introns by using available transcript data from five eukaryotes with complete or nearly complete genomic sequences." Complete [PDF](https://www.pnas.org/content/pnas/98/20/11193.full.pdf)

- [Tree based machine learning framework for predicting ground state energies of molecules ](https://arxiv.org/abs/1609.07124) 
by Burak Himmetoglu.  We present an application of the boosted regression tree algorithm for predicting ground state energies of molecules made up of C, H, N, O, P, and S (CHNOPS). The PubChem chemical compound database has been incorporated to construct a dataset of 16,242 molecules, whose electronic ground state energies have been computed using density functional theory.


- [IEEE Spectrum article: Genomics Signal Processing](https://pdfs.semanticscholar.org/eb87/1f4b1840e9357a78df2a1809161dbbee4796.pdf): 
by Dimitris Anastassiou. Genomic information is digital in a very real sense; it is
represented in the form of sequences of which each element
can be one out of a finite number of entities. 

- [Deep Learning for Genomics: A Concise Overview](https://arxiv.org/pdf/1802.00810.pdf) Tianwei Yue tyue@andrew.cmu.edu
Haohan Wang haohanw@cs.cmu.edu
School of Computer Science
Carnegie Mellon. The paper explores how deep learning can address challenges in analyzing genomic data, which is becoming increasingly complex with advancements in high-throughput sequencing techniques. The authors discuss the need for task-specific knowledge to develop deep learning models for genomics and provide a review of deep learning applications in various aspects of genomic research. They also highlight current challenges and potential research directions for future genomics applications.


- [A primer on deep learning in genomics](./papers/2018-Zou-Primer.pdf)  by James Zou et. al. Deep learning methods are a class of machine learning techniques capable of identifying highly complex patterns in large data-
sets. Here, we provide a perspective and primer on deep learning applications for genome analysis. We discuss successful
applications in the fields of regulatory genomics, variant calling and pathogenicity scores. We include general guidance for how
to effectively use deep learning methods as well as a practical guide to tools and resources. This primer is accompanied by an interactive online tutorial.

  - Associated with colabratory notebook:[A Primer on Deep Learning in Genomics - Public.ipynb](https://colab.research.google.com/drive/17E4h5aAOioh5DiTo7MZg4hpL6Z_0FyWr#scrollTo=eiiwjw4yhX0P)

- [Genome Functional Annotation using Deep Convolutional
Neural Network](https://www.biorxiv.org/content/biorxiv/early/2018/05/25/330308.full.pdf) by 
Ghazaleh Khodabandelou
, Etienne Routhier and Julien Mozziconacci. In genomics, which deals with DNA sequences, the development of deep
neural networks is expected to revolutionize current practice, from fundamental issues
such as understanding the evolution of genomes to more specific applications such as
the development of personalized medicine. Several approaches have been developed
relying on convolution neural networks (CNN) to identify the functional role of
sequences such as promoters, enhancers or protein binding sites along genomes. These
approaches rely on the generation of sequences batches with known annotations for
learning purpose. While they show good performance to predict annotations from a test
subset of these batches, they usually work less well when applied genome-wide; i.e. for
whole genome annotation. In this paper, we address this issue and propose an optimal
strategy to train CNN for this specific application. We use as a case study gene
Transcription Start Sites (TSS) and show that a model trained on one organism (e.g.
human) can be used to predict TSS in a different specie (e.g. mouse)

## Resources
- [Glossary of Next Gen Sequencing](https://www.illumina.com/science/technology/next-generation-sequencing/beginners/glossary.html): terms used in in NGS defined by Illumina. Video overview: [NGS for beginners](https://www.illumina.com/science/technology/next-generation-sequencing/beginners.html).

- [Bioinformatics Algorithms](https://www.bioinformaticsalgorithms.org/): Book and methodology by Phillip Compeau and Pavel Pevzner. Great.

 - [DNA Analysis on Coursera by Pavel Pevzner and Phillip Compeau](https://www.coursera.org/learn/dna-analysis): 8 part course on DNA statistics.
  
- [Rosalind](http://rosalind.info/problems/locations): Rosalind is a platform for learning bioinformatics and programming through problem solving.

## Data Sets
- [Google genomics data sets](https://cloud.google.com/genomics/docs/public-datasets/) Cloud Genomics provides a variety of public datasets that you can access for free and integrate into your applications. Google hosts these datasets, providing public access to the data.

## Software
- [HCA](https://mloss.org/software/title/?page=11) Multi-core non-parametric and bursty topic models (HDP-LDA, DCMLDA, and other variants of LDA) implemented in C using efficient Gibbs sampling, with hyperparameter sampling and other flexible controls.

## Companies

- [Insitro](https://insitro.com/): biology at scale, started by Daphne Koller
who started Coursea and taught [Probabilistic Graphical Methods](https://www.coursera.org/instructor/koller).

- [Tempus](https://www.tempus.com/) is a technology company that has built the world’s largest library of clinical and molecular data and an operating system to make that data accessible and useful, starting with cancer. Our goal is for each patient to benefit from the treatment of others who came before.

- [Illumina](https://www.illumina.com/company/about-us/fact-sheet.html) is a leading developer, manufacturer, and marketer of life science tools and integrated systems for large-scale analysis of genetic variation and function. These systems are enabling studies that were not even imaginable just a few years ago, and moving us closer to the realization of personalized medicine. With rapid advances in technology taking place, it is mission-critical to offer solutions that are not only innovative, but flexible, and scalable, with industry-leading support and service.

- [Just Add Data](https://www.jadbio.com/): Machine Learning for Bioinformatics at a small start up in Greece. 
