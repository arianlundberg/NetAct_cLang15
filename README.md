
# Issues with the original version written by Lu lab, addressed in this repo 
Incompatibility with C++ version 15 arises because the random_shuffle function has been deprecated in C++ versions 13 and above.

### Installation:
```
library(devtools)
install_github("arianlundberg/NetAct_cLang15", dependencies=T)
```

## NetAct 
NetAct a computational platform for constructing core transcription-factor regulatory networks using both transcriptomics data and literature-based transcription factor-target databases. NetAct robustly infers the activities of regulators using target expression, constructs networks based on transcriptional activity, and integrates mathematical modeling for validation. 
NetAct is licensed under the MIT License <https://github.com/lusystemsbio/NetAct/blob/master/LICENSE> 




### Authors:
Kenong Su <Kenong.Su@Pennmedicine.upenn.edu>,
Vivek Kohar <vivek.kohar@gmail.com>, 
Danya Gordin <Danya.Gordin@gmail.com> (Main maintainer),
Mingyang Lu <mingyang.lu@northeastern.edu>
from the Lu lab @ Northeastern University <https://lusystemsbio.northeastern.edu/>.

### Tutorial:
https://htmlpreview.github.io/?https://github.com/lusystemsbio/NetAct/blob/master/vignettes/Tutorial.html
### Manual:
https://github.com/lusystemsbio/NetAct/blob/master/vignettes/NetAct_1.0.6.pdf

### Reference:

Kenong Su, Ataur Katebi, Vivek Kohar, Benjamin Clauss, Danya Gordin, Zhaohui S. Qin, R. Krishna M. Karuturi, Sheng Li, Mingyang Lu. (2022) NetAct: a computational platform to construct core transcription factor regulatory networks using gene activity, Genome Biology, 23:270. https://doi.org/10.1186/s13059-022-02835-3
