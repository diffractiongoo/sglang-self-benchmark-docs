# SGLang self-benchmark documents

Design notes and a worked walkthrough for SGLang self-benchmarking in AISim.

| Document | Description |
| --- | --- |
| [SGLang self-benchmark design](sglang-self-benchmark-design.pdf) | An AISim integration proposal that preserves the vLLM self-benchmark workflow and profile contract through an AISim controller and a narrow SGLang execution adapter. |
| [SGLang self-benchmark journey](sglang-self-benchmark-journey.pdf) | A worked walkthrough of one campaign cell with prefill and decode points, comparing the standalone design with a second design: a driver in the Dynamo worker and a recorder inside the SGLang scheduler. Final version, 13 November 2026. It also compares how exposed each design is to SGLang version changes, lists the gaps the second design closes, records a decision for each item that was still open, and ends with six acceptance checks. |

Start with the design document, then read the journey for a concrete example. The journey's second design was read from source at SGLang v0.5.22 and v0.5.23. It has not been prototyped or run on a GPU, so the six acceptance checks are still to do.

Open either PDF to read it in GitHub's viewer, or use the download button to save a copy. This repository contains the two PDF documents; it does not contain the SGLang source code or benchmark artifacts.
