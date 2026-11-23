# ORAN-Bench-13K: An Open Source Benchmark for Assessing LLMs in Open Radio Access Networks

## Introduction

**ORAN-Bench-13K** is the first comprehensive benchmark designed to evaluate the performance of Large Language Models (LLMs) within the context of Open Radio Access Networks (O-RAN). This benchmark consists of over 13,000 meticulously curated multiple-choice questions generated from 116 O-RAN specification documents. It aims to assess LLMs' proficiency in understanding and generating human-like text specific to O-RAN tasks. We hope to build a community around this benchmark and welcome contributions from everyone working towards agentic O-RAN. The first version of the benchmark is available [here](https://github.com/prnshv/ORAN-Bench-13K/tree/d13ffc3).

The manuscript detailing ORAN-Bench-13K has been accepted at the IEEE Consumer Communications & Networking Conference (CCNC) 2025. The paper is available at the following link: [https://ieeexplore.ieee.org/abstract/document/10975994](https://ieeexplore.ieee.org/abstract/document/10975994). We have conducted comprehensive tests with multiple open-source and closed-source LLMs. Additionally, we propose a novel RAG-based pipeline named ORANSight. More information about these tests and ORANSight is available in our preprint

## Motivation

The rapid advancement of O-RAN technology necessitates the development of sophisticated and intelligent systems capable of managing complex tasks within these networks. Large Language Models have shown significant promise in various domains but have yet to be thoroughly evaluated within the specific context of O-RAN. ORAN-Bench-13K addresses this gap by providing a robust and comprehensive benchmark to evaluate LLMs' capabilities in this critical domain.

## Repository Structure

- **MCQA**: This folder contains three JSON files (Fin_E.json, Fin_M.json, Fin_D.json) corresponding to different difficulty levels of multiple-choice questions.

## Usage

To use the benchmark, you can load the JSON files in the `Benchmark` folder and integrate them into your LLM evaluation framework. Each file contains a list of questions, options, and the correct answer index.

## Citation

If you use ORAN-Bench-13K in your research, please cite our work as follows:

```bibtex
@INPROCEEDINGS{10975994,
  author={Gajjar, Pranshav and Shah, Vijay K.},
  booktitle={2025 IEEE 22nd Consumer Communications & Networking Conference (CCNC)}, 
  title={ORAN-Bench-13K: An Open Source Benchmark for Assessing LLMs in Open Radio Access Networks}, 
  year={2025},
  volume={},
  number={},
  pages={1-4},
  keywords={Accuracy;Codes;Large language models;Pipelines;Retrieval augmented generation;Open RAN;Benchmark testing;Chatbots;Reliability;Anomaly detection;O-RAN;LLMs;Benchmarks;LLM-Benchmark;Dataset;ChatGPT;Gemini;RAG},
  doi={10.1109/CCNC54725.2025.10975994}}
```

## Contribution

We welcome contributions to expand and improve the benchmark. If you have suggestions or want to add new questions, please reach out to us.

## ORANSight

We are currently working on a public deployment of the proposed ORANSight including associated codes, and a usable application will be shared soon.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
