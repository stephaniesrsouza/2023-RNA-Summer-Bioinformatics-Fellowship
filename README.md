# 2023 RNA Institute Summer Bioinformatics Fellowship
![image](https://github.com/stephaniesrsouza/2023-RNA-Summer-Bioinformatics-Fellowship/assets/134233137/2f0bd983-5aef-4e76-b1c2-efb036b32a35)


This repository contains information and coding exercises for the Andam Lab group for the 2023 summer bioinformatics workshop.


conda install -c conda-forge -c bioconda -c defaults abricate
abricate --db card --quiet *.fa > abricate_amr_results.tab
abricate --summary abricate_amr_results.tab > abricate_amr_summary.tab

abricate --db vfdb --quiet *.fa > abricate_vfdb_results.tab
abricate --summary abricate_vfdb_results.tab > abricate_vfdb_summary.tab
