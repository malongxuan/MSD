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

@inproceedings{DBLP:conf/acl/MaZZSK023,
  author       = {Longxuan Ma and
                  Weinan Zhang and
                  Shuhan Zhou and
                  Churui Sun and
                  Changxin Ke and
                  Ting Liu},
  editor       = {Anna Rogers and
                  Jordan L. Boyd{-}Graber and
                  Naoaki Okazaki},
  title        = {I run as fast as a rabbit, can you? {A} Multilingual Simile Dialogues
                  Datasets},
  booktitle    = {Findings of the Association for Computational Linguistics: {ACL} 2023,
                  Toronto, Canada, July 9-14, 2023},
  pages        = {7223--7237},
  publisher    = {Association for Computational Linguistics},
  year         = {2023},
  url          = {https://doi.org/10.18653/v1/2023.findings-acl.453},
  doi          = {10.18653/v1/2023.findings-acl.453},
  timestamp    = {Wed, 23 Aug 2023 14:28:15 +0200},
  biburl       = {https://dblp.org/rec/conf/acl/MaZZSK023.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
