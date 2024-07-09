# OVERVIEW

- Project name: Intellectual Disability Whole Exome Sequencing
- Project location: The Montreal Neurological Institute and Hospital, Montreal, Quebec
- Last updated: November 2022
- Contact email address: neurobioinfo@mcgill.ca, https://neurobioinfo.github.io/

The Montreal Neurological Institute and Hospital (The Neuro) Bioinformatics Core is responsible for processing, consolidating, and storing the genomics data generated for the range of studies being performed by the institute’s researchers and clinicians. As such, the data are sorted into sets based on the sequencing methodology used and the phenotype of study. The Neuro's commitment to open science practices have resulted in all of the data being made publicly available through the C-BIG initiative, following appropriate ethical approvals and the principal investigator(s) consent.

Largely, these genomics datasets were generated for the purposes of novel gene-disease relationship discovery, although other analyses may have also been performed. We recommend contacting the recruiting principal investigator(s), outlined below, for full details regarding the previous use of these datasets.

### Dataset contents
- 2827.0045 GB
- FASTQ files, BAM alignments, and gVCF/VCF files
- 262 Subjects

## METHODS

### -- Recruitment --
Patients diagnosed with Intellectual Disability were recruited at The Montreal Neurological Institute and Hospital (The Neuro) in the clinic of Dr. Guy Rouleau. All indivduals provided informed consent.

### -- Data Acquisition --
Whole blood was obtained from all individuals and DNA was isolated. Whole exome sequencing was performed using either the Illumina NovaSeq 6000 or the Illumina HiSeq. Sequencing reads were processed using a Burrows-Wheeler Aligner (BWA) alignment, Genome Analysis Toolkit (GATK)/Picard post-alignment, and GATK HaplotypeCaller calling pipeline.

Sequencing details: 
 
                        Machine-pairing Sequencing_center   Capture_type_kit       Date
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_10_25
                  Illumina_HiSeq_Paired                IC        Exome_SS_V4 2017_10_17
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_12_10
                  Illumina_GAIIx_Paired               UBC     Exome_SS_38Mbp 2017_10_06
                  Illumina_HiSeq_Paired                IC     Exome_SS_50Mbp 2012_01_09
                  Illumina_HiSeq_Paired                IC              50Mbp      merge
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_12_14
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_12_30
                  Illumina_HiSeq_Paired                IC        Exome_SS_V4 2012_12_03
                      ABI_SOLID4_Paired              SteJ     Exome_SS_50Mbp 2011_06_22
                  Illumina_HiSeq_Paired                IC        Exome_SS_V4 2013_01_30
                  Illumina_HiSeq_Paired                IC     Exome_SS_50Mbp 2011_03_22
                  Illumina_GAIIx_Paired                IC     Exome_SS_38Mbp 2017_10_06
                  Illumina_GAIIx_Paired                HK     Exome_SS_38Mbp 2017_10_06
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_12_20
                      ABI_SOLID4_Single              SteJ     Exome_SS_50Mbp 2010_12_02
                      ABI_SOLID4_Paired              SteJ     Exome_SS_50Mbp 2011_05_12
                  Illumina_HiSeq_Paired                IC     Exome_SS_50Mbp 2011_03_23
                  Illumina_HiSeq_Paired                IC                 V4      merge
                  Illumina_HiSeq_Paired                IC     Exome_SS_50Mbp 2011_04_16
                  Illumina_HiSeq_Paired                IC     Exome_SS_50Mbp 2012_04_03
                  Illumina_HiSeq_Paired                IC                 V4 2014_05_05
                  Illumina_HiSeq_Paired                IC        Exome_SS_V4 2014_01_10
                  Illumina_HiSeq_Paired                IC        Exome_SS_V4 2014_01_13
                  Illumina_HiSeq_Paired                IC           Exome_V5 2014_05_28
                  Illumina_HiSeq_Paired                IC           Exome_V5 2014_11_05
                  Illumina_HiSeq_Paired                IC           Exome_V5      merge
                  Illumina_HiSeq_Paired               HSJ           Exome_V5 2014_12_08
                  Illumina_HiSeq_paired               HSJ Exome_SS_V5_Clinic       2015
                  Illumina_HiSeq_paired               HSJ        Exome_SS_V5       2016
