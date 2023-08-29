# MSD
The data and code of ACL 2023 Findings paper "I run as fast as a rabbit, can you? A Multilingual Simile Dialogue Dataset"

https://arxiv.org/abs/2306.05672

The simile in a dialogue scene is very different from the traditional simile in a sentence or a triplet. This paper studies the complex simile phenomena in dialogue and proposes simile dialogue data with both English and Chinese examples. The statistics are as below.

|Category                       |   Ch   |    En   |
|:------------:|:------------:|:------------:|
|Simile                         |  5,515 |  3,576  |
|Literal                        |  5,904 |  4,570  |
|Tenor in context               |  32.8% |  48.9%  |
|Tenor in response              |  67.2% |  51.1%  |
|Vehicle before Tenor           |  5.7%  |  0.9%   |
|Tenor before Vehicle           |  94.3% |  99.1%  |
|Ave. context words in simile   |  20.76 |  22.22  |
|Ave. response words in simile  |  18.86 |  17.83  |

The MSD-v1.0.zip contains five folders corresponding to the five tasks we defined and the data we used in the paper.

1 - Simile Recognition

2 - Simile Interpretation

3 - Simile Generation

4 - Simile Response Retrieval

5 - Simile Response Generation(Completion)

If you use the MSD data for research, please cite our paper "I run as fast as a rabbit, can you? A Multilingual Simile Dialogue Dataset"

@article{DBLP:journals/corr/abs-2306-05672,

  author       = {Longxuan Ma and
                  Weinan Zhang and
                  Shuhan Zhou and
                  Churui Sun and
                  Changxin Ke and
                  Ting Liu},
                  
  title        = {I run as fast as a rabbit, can you? {A} Multilingual Simile Dialogue Dataset},
                  
  journal      = {CoRR},
  
  volume       = {abs/2306.05672},
  
  year         = {2023},
  
  url          = {https://doi.org/10.48550/arXiv.2306.05672},
  
  doi          = {10.48550/arXiv.2306.05672},
  
  eprinttype    = {arXiv},
  
  eprint       = {2306.05672},
  
  timestamp    = {Wed, 14 Jun 2023 13:17:00 +0200},
  
  biburl       = {https://dblp.org/rec/journals/corr/abs-2306-05672.bib},
  
  bibsource    = {dblp computer science bibliography, https://dblp.org}
  
}
