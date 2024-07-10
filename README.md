# ORAN-Bench-13K: An Open Source Benchmark for Assessing LLMs in Open Radio Access Networks

## Introduction

**ORAN-Bench-13K** is the first comprehensive benchmark designed to evaluate the performance of Large Language Models (LLMs) within the context of Open Radio Access Networks (O-RAN). This benchmark consists of 13,952 meticulously curated multiple-choice questions generated from 116 O-RAN specification documents. It aims to assess LLMs' proficiency in understanding and generating human-like text specific to O-RAN tasks.

The manuscript detailing ORAN-Bench-13K has been submitted to the IEEE Consumer Communications & Networking Conference (CCNC) 2025. The preprint is available on arXiv at the following link: [https://arxiv.org/abs/2407.06245](https://arxiv.org/abs/2407.06245). We have conducted comprehensive tests with multiple open-source and closed-source LLMs. Additionally, we propose a novel RAG-based pipeline named ORANSight. More information about these tests and ORANSight is available in our preprint

## Motivation

The rapid advancement of O-RAN technology necessitates the development of sophisticated and intelligent systems capable of managing complex tasks within these networks. Large Language Models have shown significant promise in various domains but have yet to be thoroughly evaluated within the specific context of O-RAN. ORAN-Bench-13K addresses this gap by providing a robust and comprehensive benchmark to evaluate LLMs' capabilities in this critical domain.

## Repository Structure

- **MCQA**: This folder contains three JSON files (Fin_E.json, Fin_M.json, Fin_D.json) corresponding to different difficulty levels of multiple-choice questions.

## Usage

To use the benchmark, you can load the JSON files in the `Benchmark` folder and integrate them into your LLM evaluation framework. Each file contains a list of questions, options, and the correct answer index.

## Citation

If you use ORAN-Bench-13K in your research, please cite our work as follows:

```bibtex
@misc{gajjar2024oranbench13kopensourcebenchmark,
      title={ORAN-Bench-13K: An Open Source Benchmark for Assessing LLMs in Open Radio Access Networks}, 
      author={Pranshav Gajjar and Vijay K. Shah},
      year={2024},
      eprint={2407.06245},
      archivePrefix={arXiv},
      primaryClass={cs.NI},
      url={https://arxiv.org/abs/2407.06245}, 
}
```

## Contribution

We welcome contributions to expand and improve the benchmark. If you have suggestions or want to add new questions, please reach out to us.

## ORANSight

We are currently working on a public deployment of the proposed ORANSight including associated codes, and a usable application will be shared soon.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
