<h1 align="center">Dharmesh Meena</h1>
<p align="center"><b>AI/ML engineer</b> &middot; LLM systems, retrieval, agents and evaluation</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dharmeshmeena/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-dharmeshmeena-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <img alt="Open to work" src="https://img.shields.io/badge/open%20to-AI%2FML%20roles-2ea44f?style=flat-square">
</p>

```console
dharmesh@ml:~$ whoami
Dharmesh Meena, AI/ML engineer

dharmesh@ml:~$ cat focus.txt
retrieval that is measured, not guessed
agents whose failures are tested code paths
evaluation numbers that come with confidence intervals

dharmesh@ml:~$ ls projects/
microllm/   rag-eval-lab/   agentkit/   evalkit/

dharmesh@ml:~$ _
```

## Flagship

**[microllm](https://github.com/dharmeshdev1/microllm)** is a from-scratch LLM stack: byte-level BPE tokenizer, a decoder-only transformer (RoPE, grouped-query attention, SwiGLU, KV cache), a resumable training loop, and speculative decoding that provably samples from the target distribution.

- Trained a 24.6M parameter model on TinyStories to 0.779 bits per byte on held-out stories, with a 2.5M draft model for speculative decoding (1.04x to 1.26x measured speedup).
- 139 tests, including attention checked against a naive reference, a chi-square test that speculative samples match the target distribution, and bit-exact checkpoint resume.
- The README reports its limitations and the results that did not flatter it.

## More projects

Each has no runtime dependencies, a test suite, lint and CI on Python 3.10 to 3.13, and a README that states its limitations.

| Project | What it is | Highlights |
| --- | --- | --- |
| [**rag-eval-lab**](https://github.com/dharmeshdev1/rag-eval-lab) | Retrieval library and evaluation harness | BM25, hashed n-gram vectors, reciprocal rank fusion, recall@k, MRR, nDCG |
| [**agentkit**](https://github.com/dharmeshdev1/agentkit) | Tool-using agent loop | Typed tool schemas, error recovery, repeat and step guards, JSONL traces, AST-based calculator |
| [**evalkit**](https://github.com/dharmeshdev1/evalkit) | Evaluation statistics toolkit | Unbiased pass@k, seeded bootstrap CIs, paired bootstrap, exact sign test, graders |

## How I work

- **Measure first.** A change is only an improvement if a metric moved, and the metric reports its uncertainty.
- **Make failure modes explicit.** Malformed tool calls, loops and missing data are handled paths with tests, not surprises.
- **Say what the numbers do not show.** Every README lists its limitations next to its results.

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)

Topics I work on: language model internals and inference, retrieval and ranking, LLM evaluation, tool use and agents, experiment statistics.

## Contact

Message me on [LinkedIn](https://www.linkedin.com/in/dharmeshmeena/).
