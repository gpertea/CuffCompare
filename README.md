## CuffCompare
* compare and evaluate the accuracy of RNA-Seq transcript assemblers (Cufflinks, Stringtie). 
* collapse (merge) duplicate transcripts from multiple GTF/GFF3 files
* classify transcripts from one or multiple GTF/GFF3 files as they relate to reference transcripts provided in a
annotation file (also in GTF/GFF3 format)

This program is also distributed as part of the Cufflinks suite (see manual: http://cole-trapnell-lab.github.io/cufflinks/cuffcompare/). However building Cufflinks from source may be more complicated than using this source package, which only depends on my other code repository [GCLib](../../../gclib).
In order to build CuffCompare from this source package the following steps can be taken:
```
  cd /some/build/dir
  git clone https://github.com/gpertea/gclib
  git clone https://github.com/gpertea/cuffcompare
  cd cuffcompare
  make
```
This should build the **cuffcompare** binary in the current directory.

