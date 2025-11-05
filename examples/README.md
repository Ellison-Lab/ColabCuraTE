#### This folder contains _ColabCuraTE_ examples showing the curation process for six different transposon families. The starting sequences for examples #1-5 were identified by _RepeatModeler2_, while the starting sequence for the sixth example was identified by _HiTE_.

1. [Curation of a _copia_ Long Terminal Repeat (LTR) retrotransposon from the fruit fly _Drosophila melanogaster_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/1_dMel_copia/ColabCuraTE_copia.ipynb)
2. [Curation of a _gypsy_ Long Terminal Repeat (LTR) retrotransposon from the snake _Bungarus multicinctus_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/2_bMul_gypsy/ColabCuraTE_gypsy.ipynb)
3. [Curation of a _SINE_ non-LTR retrotransposon from the snake _Bungarus multicinctus_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/3_bMul_SINE/ColabCuraTE_SINE.ipynb)
4. [Curation of a _LINE_ non-LTR retrotransposon from the snake _Bungarus multicinctus_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/4_bMul_LINE/ColabCuraTE_LINE.ipynb)
5. [Curation of a _hAT_ DNA transposon from the rice plant _Oryza sativa_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/5_oSat_hAT/ColabCuraTE_hAT.ipynb)
6. [Curation of the _297_ LTR retrotransposon from the fruit fly _Drosophila melanogaster_](https://colab.research.google.com/github/Ellison-Lab/ColabCuraTE/blob/main/examples/6_dMel_297/ColabCuraTE_297.ipynb)

#### Click the link above to open the corresponding notebook in Google Colab.

The above folders contain the files generated during the curation process. See below for the accession numbers of the genome assemblies used in each example.

>##### File descriptions
>- The initial, pre-curation, consensus sequence for each TE is in the file labeled `*_con.fa`. This file should be used as the starting point for the manual curation process.
>- The initial seed alignment is located in the file labeled `GENUS_SPECIES_TEID.stk`.
>- The trimmed multiple sequence alignment used to generate the final consensus sequence is located in the file `*_elements_aligned.fa`
>- The final seed alignment is located in the file labeled `TE-NUM_SPECIES.stk`.
>- The final curated consensus sequence is in the file labeled `TE-NUM_SPECIES.fasta`.
>- The completed notebook is also provided both as a python notebook file (`*.ipynb`) and as a PDF.

#### Genome assembly NCBI accession numbers
| Species|Accession|
| ------ | ------- |
| _Drosophila melanogaster_ | GCA_000001215.4 |
| _Bungarus multicinctus_ | GCA_023653725.1 |
| _Oryza sativa_ | GCF_034140825.1 |
