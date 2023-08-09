<img align="center" height="200" src="/profile/peregrine_logo.png">

[![version](https://img.shields.io/badge/version-0.0.1-blue)](https://github.com/undark-lab/peregrine) 


# About: 
Welcome to PEREGRINE! A public, open-source pipeline designed for targeted inference of gravitational wave signals from multiple source types. 

## Access:
Currently, PEREGRINE has two public branches: 
- `cbc`: Inferring source parameters of standard LVKC CBC sources.
- `overlapping`: Inferring source parameters of overlapping or coincident gravitational wave detections in a 2G network.

## Papers using PEREGRINE:
- [![DOI](https://img.shields.io/badge/DOI-arXiv.2304.02035-brightgreen)](https://arxiv.org/abs/2304.02035) *Sequential simulation-based inference for gravitational wave signals (Bhardwaj, Alvey, Miller, Nissanke, Weniger)*
- [![DOI](https://img.shields.io/badge/DOI-arXiv.2304.02035-brightgreen)](https://arxiv.org/abs/2304.02035) *What to do when things get crowded? Scalable joint analysis of overlapping gravitational wave signals (Alvey, Bhardwaj, Nissanke, Weniger)*

## The algorithm: 
PEREGRINE leverages the power of (Truncated Marginal) Neural Ratio Estimation (TMNRE) via the open-source package [`swyft`](https://github.com/undark-lab/swyft).
- For details on (TM)NRE, [`swyft`](https://github.com/undark-lab/swyft) and more, please visit [The Undark Lab](https://github.com/undark-lab). 
- Documentation for [`swyft`](https://github.com/undark-lab/swyft) is available at: [swyft documentation](https://swyft.readthedocs.io/en/latest/).

## Contact:
For any queries related to PEREGINRE, please feel free to contact: 
- [Uddipta Bhardwaj](mailto:u.bhardwaj@uva.nl)
- [James Alvey](mailto:j.b.g.alvey@uva.nl)
- Alternatively, please feel free to open a github issue or pull request.

## Usage:
If you use PEREGRINE in your analysis, or find it useful, we would ask that you please use the following citation: 
```
@article{Bhardwaj:2023xph,
    author = "Bhardwaj, Uddipta and Alvey, James and Miller, Benjamin Kurt and Nissanke, Samaya and Weniger, Christoph",
    title = "{Peregrine: Sequential simulation-based inference for gravitational wave signals}",
    eprint = "2304.02035",
    archivePrefix = "arXiv",
    primaryClass = "gr-qc",
    month = "4",
    year = "2023"
}
```
