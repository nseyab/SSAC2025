## MIT Sloan Sports Analytics Conference 2025 Research Repository

This repository is provided alongside the paper: "Tackling Action Sparsity with Probability Vectors". It contains all relevant data.

## Abstract

The purpose of this research is to addresses one of the primary challenges in analyzing player behavior through spatial data, inherent sparsity of actions during a match. We do this by proposing a new Probability Vectors of Zonal Actions (PVZA) technique, which models player behavior using a multinomial distribution across spatial zones on the pitch. 

## Data

StatsBomb Open Data [^1] for the Women's Super League 2020/2021 season was accessed and processed to Atomic Soccer Player Action Description Language [^2][^3]. The processed data is stored in Apache Arrow format.  

[^1]: “Statsbomb Open Data.” https://github.com/statsbomb/open-data, n.d. Accessed August 21, 2024.
[^2]: Decroos, Tom, Lotte Bransen, Jan Van Haaren, and Jesse Davis. “Actions Speak Louder than Goals: Valuing Player Actions in Soccer.” In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, 1851–61. KDD ’19. New York, NY, USA: Association for Computing Machinery, 2019. https://doi.org/10.1145/3292500.3330758.
[^3]: Van Roy, Maaike, Robberechts, Pieter, Decroos, Tom, and Davis, Jesse. “Valuing On-the-Ball Actions in Soccer: A Critical Comparison of xT and VAEP.” In Proceedings of the {AAAI}-20 Workshop on Artifical Intelligence in Team Sports. AITS. AI in Team Sports Organising Committee, 2020.
