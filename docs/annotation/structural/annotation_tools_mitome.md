List of mitome annotation tools
===========================

| year	| Tool name | Publication | Type | Method | Organism | Comments | Output Format |
| --- | --- | --- | --- | --- | --- | --- | --- |
2004 | DOGMA | Wyman SK, Jansen RK and Boore JL (2004) Automatic annotation of organellar genomes with DOGMA. Bioinformatics 20: 3252-3255 | | | animal mitochondrial and plant chloroplast | |
2007 | RNAweasel | Lang B.F., M-J. Laforest, and G. Burger (2007) Mitochondrial introns: a critical view. Trends Genet 23:119-25. | abinitio | based on RNA secondary structure profiles | | mitochondrial RNAs only |
2007 | [MFannot](https://github.com/BFL-lab/Mfannot) | Lang B.F., M-J. Laforest, and G. Burger (2007) Mitochondrial introns: a critical view. Trends Genet 23:119-25. | pipeline | abinitio + similarity | annotation of mitochondrial and plastid genomes | helpful with organelle genomes that contain lots of introns. Output not easy to deal with. AGAT can be used to convert the output in gff. | 
2010 | MITOFY | Alverson AJ, Wei X, Rice DW, Stern DB, Barry K and Palmer JD (2010) Insights into the evolution of mitochondrial genome size from complete sequences of Citrullus lanatus and Cucurbita pepo (Cucurbitaceae). Molecular Biology and Evolution 27: 1436-1448 | | | Plant mitochondrial | |
2010 | MOSAS | Sheffield NC, Hiatt KD, Valentine MC, Song H and Whiting MF (2010) Mitochondrial genomics in Orthoptera using MOSAS. Mitochondrial DNA 21: 87-104 | | | insect mitochondrial genome | |
2011 | MAKER2 | Holt, C. & Yandell, M. MAKER2: an annotation pipeline and genome-database management tool for second-generation genome projects. BMC Bioinformatics 12, 491 (2011). | pipeline | | Eukaryote, Prokaryote but alignment approach can be used for other type | It uses proteins, transcripts ... Abinitio: Augustus, Fgnesh,Genemark,snap. Need to modify the code to accept specific codon table for mitochondria. Not the best choice but provide nice protein alignments useful for manual curation |	|
2013 | MitoAnnotator | Iwasaki W, Fukunaga T, Isagozawa R, Yamada K, Maeda, Y, Satoh TP, Sado T, Mabuchi K, Takeshima H, Miya M and Nishida M (2013) MitoFish and MitoAnnotator: a mitochondrial genome database of fish with an accurate and automatic annotation pipeline. Molecular Biology and Evolution 30: 2531-2540 | Ab initio (sensors + Neural network) | | Fish | MitoFish is a comprehensive and standardized fish mitochondrial genome database used by MitoAnnotator |
2013 | MITOS | Bernt M, Donath A, Jühling F, Externbrink F, Florentz C, Fritzsch G, Pütz J, Middendorf M and Stadler PF (2013) MITOS: improved de novo metazoan mitochondrial genome annotation. Molecular Phylogenetics and Evolution 69: 313-319 | | | metazoan mitochondrial genome | |
2014 | Prokka | Seemann T., Prokka: rapid prokaryotic genome annotation. Bioinformatics 2014 Jul 15;30(14):2068-9. PMID:24642063 | pipeline | Ab initio + evidence-based for functional annotation | prokaryote | https://github.com/tseemann/prokka Do structural and functional annotation. No intron allowed! | .gff, .gbk, .fna, .faa, .ffn, .sqn, .fsa, .tbl, .err, .log, .txt, .tsv
| 2017 | Geseq | Tillich M, Lehwark P, Pellizzer T, Ulbricht-Jones ES, Fischer A, Bock R and Greiner S (2017) GeSeq – versatile and accurate annotation of organelle genomes. Nucleic Acids Research 45: W6-W11 | | | mitochondria and chloroplast | web based tool |
2018 | AGORA | Jung J, Kim JI, Jeong Y-S and Yi, G (2018) AGORA: organellar genome annotation from the amino acid and nucleotide references. Bioinformatics 34: 2661-2663 | | | organelle genome annotation ( mitochondrion and plastid genomes of eukaryotes ) | web application | |
2019 | MitoZ | Yang C, Meng G, Liu S and Li Y (2019). MitoZ: a toolkit for animal mitochondrial genome assembly, annotation and visualization. Nucleic Acids Research, gkz173 | | | | |
| year	| Tool name | Publication | Type	| Method | Organism | Comments | Output Format |


Interesting resource:  
https://chlorobox.mpimp-golm.mpg.de/Alternative-Tools.html
