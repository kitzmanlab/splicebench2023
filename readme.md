Download and unzip data from Zenodo [10.5281/zenodo.8351879
](https://zenodo.org/record/8351879)

Get and setup hg19 reference
```
wget https://hgdownload.cse.ucsc.edu/goldenpath/hg19/bigZips/hg19.fa.gz 
gunzip hg19.fa.gz 
bgzip hg19.fa
samtools faidx hg19.fa.gz
```

Install [splfxseq package](https://github.com/kitzmanlab/splfxseq)
