MultiGPS
===========

MultiGPS is a framework for analyzing collections of multi-condition ChIP-seq datasets and characterizing differential binding events between conditions. In analyzing multiple-condition ChIP-seq datasets, MultiGPS encourages consistency in the reported binding event locations across conditions and provides accurate estimation of ChIP enrichment levels at each event.


Executables:
--------------
The following webpage maintains executable JAR files for major versions: 
http://mahonylab.org/software/multigps


Dependencies:
--------------
MultiGPS requires Java 8+. To build MultiGPS, you will also need to download and build the seqcode-core library (https://github.com/seqcode/seqcode-core), and place the build and lib directories on your paths. 


Citation:
--------------
An integrated model of multiple-condition ChIP-seq data reveals predeterminants of Cdx2 binding
S Mahony, MD Edwards, EO Mazzoni, RI Sherwood, A Kakumanu, CA Morrison, H Wichterle, DK Gifford
PLoS Computational Biology (2014) 10(3):e1003501


Major History:
--------------

Version 0.75 (2020-07-09): Fixing mishandling of multimapped reads in BWA output BAM files. Option --nonunique now works as expected. 

Version 0.74 (2017-04-01): MultiGPS now produces BED files by default (change inherited from update to seqcode-core). 

Version 0.73 (2017-02-17): Minor update that includes support for full-genome FASTA files in --seq option and other updates to support Galalxy integration.

Version 0.72 (2016-11-23): First release in this repo. Fixed several bugs for stability.  

Version 0.5 (2014-03-01): Initial release with publication. This version predates the current repo, but code is archived here: http://mahonylab.org/software/multigps
