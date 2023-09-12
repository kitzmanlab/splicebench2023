Download and unzip data from Zenodo
```
#TODO link here
#FOR now, 
rsync -avu -e ssh son:/nfs/turbo/umms-kitzmanj/oldvol2/jacob/proj/splicebench/for_zenodo/ ../data/ 
```

Get and setup hg19 reference
```
wget https://hgdownload.cse.ucsc.edu/goldenpath/hg19/bigZips/hg19.fa.gz 
gunzip hg19.fa.gz 
bgzip hg19.fa
samtools faidx hg19.fa.gz
```

Install [splfxseq package](https://github.com/kitzmanlab/splfxseq)# splicebench2023
