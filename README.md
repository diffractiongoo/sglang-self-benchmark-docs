# SGLang self-benchmark documents

Design notes and a worked walkthrough for SGLang self-benchmarking in AISim.

| Document | Description |
| --- | --- |
| [SGLang self-benchmark design](sglang-self-benchmark-design.pdf) | An AISim integration proposal that preserves the vLLM self-benchmark workflow and profile contract through an AISim controller and a narrow SGLang execution adapter. |
| [SGLang self-benchmark journey](sglang-self-benchmark-journey.pdf) | A worked walkthrough of one campaign cell with prefill and decode points, comparing the standalone design with a proposed controller inside the SGLang scheduler. |

Start with the design document, then read the journey for a concrete example. The journey's scheduler integration is a proposal that has not been prototyped or run on a GPU.

Open either PDF to read it in GitHub's viewer, or use the download button to save a copy. This repository contains the two PDF documents; it does not contain the SGLang source code or benchmark artifacts.
