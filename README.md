# ⚡ Compilers and Runtimes for AI: From Prompts to Accelerators  
### EECS 598 · Fall 2025  
*Cutting Edge and Emerging Technologies from the Programming Interface down to Hardware Acceleration of AI*

---

## 📖 Course Summary

The science and art of creating **efficient AI systems** spans the entire computing stack—from high-level language abstractions down to specialized hardware accelerators. This course provides a comprehensive exploration of AI compiler and runtime techniques, covering everything from **language-level AI compiler systems** (DSPy, SGLang, MTP, Guidance, LMQL) to **hardware-level acceleration** (GPU kernels, TPU compilation, custom ASICs, and emerging AI chips).

Students will learn how modern AI compilers and runtime systems like **PyTorch, JAX, TVM, TensorRT, VLLM, and specialized LLM compilers** orchestrate the full pipeline from prompt engineering and program synthesis down to optimized execution on heterogeneous hardware. The course covers the complete spectrum: **prompt-level optimizations**, **graph-level transformations**, **kernel-level tuning**, **memory hierarchy optimization**, and **distributed system coordination**.

### What You’ll Do
- Design and implement **end-to-end optimized AI systems** spanning the full stack from language-level abstractions to hardware execution  
- Explore **language-level AI compiler techniques** (prompt optimization, program synthesis, declarative AI programming) and **traditional compiler optimizations** (graph-level transformations, kernel tuning, memory management, distributed training)  
- Work hands-on with **cutting-edge AI compiler ecosystems** (DSPy, SGLang, MTP, Guidance, LMQL, MLIR, TVM, PyTorch, CUDA) and **heterogeneous hardware platforms** (GPUs, TPUs, custom accelerators, emerging AI chips)  
- Present a **capstone project** demonstrating novel compiler/runtime optimizations for real-world AI workloads, with projects spanning the full spectrum from language-level innovations to hardware-level breakthroughs  

Projects are **team-based (3–5 students)** and include selecting a focus, designing the optimization approach, building compiler/runtime components, and benchmarking performance.  

### What You’ll Learn
- The **comprehensive landscape of AI systems**: from language-level AI compiler techniques (DSPy, SGLang, MTP) to hardware-level acceleration (GPU kernels, TPU compilation, custom ASICs)  
- **State-of-the-art techniques**: prompt-level optimization, program synthesis, graph-level transformation, auto-tuning, quantization, inference acceleration, and emerging AI chip architectures  
- **Critical research skills**: interpreting papers, evaluating cutting-edge systems, presenting technical ideas, and bridging the gap between high-level AI programming and low-level hardware optimization  

Grading is **project-heavy**. You’ll showcase your project’s evolution through presentations, paper reviews, and final demos.  

---

## 👨‍🏫 Instruction Team
- **Instructor**: [Jason Mars](http://www.jasonmars.org) (📧 profmars@umich.edu)  
- **GSI**: *TBD*  

---

## 🗓 Logistics
- **Lecture**: TBD  
- **Credits**: 4  
- **Office Hours**: On Demand  
- **GSI Office Hours**: TBA  
- **Course Discussion**: Piazza (TBD)  
- **Canvas**: TBD  
- **Recorded Lectures**: Available on Canvas  

---

## 📂 Tentative List of Papers

| Technology Category | Paper Title | Year | Link |
|:------------------|:-------------|:----:|:-----|
| **LMQL** | **Prompting Is Programming: A Query Language for Large Language Models** | 2022 | [Paper](https://arxiv.org/abs/2212.06094) |
| **DSPy** | **DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines** | 2023 | [Paper](https://arxiv.org/pdf/2310.03714) |
| **DSPy** | **Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs** | 2024 | [Paper](https://arxiv.org/abs/2406.11695) |
| **DSPy** | **GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning** | 2025 | [Paper](https://arxiv.org/abs/2507.19457) |
| **SGLang** | **SGLang: Efficient Execution of Structured Language Model Programs** | 2023 | [Paper](https://arxiv.org/abs/2312.07104) |
| **MTP** | **Meaning-Typed Programming: Language Abstraction and Runtime for Model-Integrated Applications** | 2025 | [Paper](https://arxiv.org/abs/2405.08965) |
| **vLLM** | **Efficient Memory Management for Large Language Model Serving with PagedAttention** | 2023 | [Paper](https://arxiv.org/abs/2309.06180) |
| **vLLM** | **Effective Memory Management for Serving LLM with Heterogeneity** | 2025 | [Paper](https://arxiv.org/abs/2503.18292) |
| **TensorRT-LLM** | **GPU-Accelerated AI Inference Whitepaper** | 2023 | [Whitepaper](https://www.nvidia.com/en-us/lp/ai/inference-whitepaper/) |
| **Apache TVM** | **TVM: An Automated End-to-End Optimizing Compiler for Deep Learning** | 2018 | [Paper](https://arxiv.org/abs/1802.04799) |
| **Apache TVM** | **Ansor: Generating High-Performance Tensor Programs for Deep Learning** | 2020 | [Paper](https://arxiv.org/abs/2006.06762) |
| **Apache TVM** | **Relay: A High-Level Compiler for Deep Learning** | 2019 | [Paper](https://arxiv.org/abs/1904.08368) |
| **PyTorch 2** | **PyTorch 2: Faster Machine Learning Through Dynamic Python Bytecode and Graph Compilation for DNNs** | 2024 | [Paper](https://dl.acm.org/doi/10.1145/3620665.3640366) |
| **PyTorch ROCm** | **TorchBench: Benchmarking PyTorch with High API Surface Coverage** | 2023 | [Paper](https://arxiv.org/abs/2304.14226) |
| **PyTorch 2** | **TorchTitan: One-stop PyTorch native solution for production ready LLM pretraining** | 2024 | [Paper](https://arxiv.org/abs/2410.06511) |
| **PyTorch ROCm** | **ECLIP: Energy-efficient and Practical Co-Location of ML Inference Pipelines on GPUs** | 2025 | [Paper](https://arxiv.org/abs/2506.12598) |
| **PyTorch nvFuser** | **PyTorch 2: Faster Machine Learning Through Dynamic Python Bytecode and Graph Compilation for DNNs** | 2024 | [Paper](https://dl.acm.org/doi/10.1145/3620665.3640366) |
| **OpenXLA** | **Operator Fusion in XLA: Analysis and Evaluation** | 2023 | [Paper](https://arxiv.org/abs/2301.13062) |
| **OpenXLA** | **Memory Safe Computations with XLA Compiler** | 2022 | [Paper](https://arxiv.org/abs/2208.06413) |
| **OpenVINO** | **OpenVINO Deep Learning Workbench: Comprehensive Analysis and Tuning of Neural Networks Inference** | 2019 | [Paper](https://openaccess.thecvf.com/content_ICCVW_2019/papers/SDL-CV/Gorbachev_OpenVINO_Deep_Learning_Workbench_Comprehensive_Analysis_and_Tuning_of_Neural_ICCVW_2019_paper.pdf) |
| **OpenVINO** | **Leveraging Speculative Sampling and KV-Cache Optimizations Together for Generative AI using OpenVINO** | 2023 | [Paper](https://arxiv.org/abs/2311.04951) |
| **LLVM** | **LLVM: A Compilation Framework for Lifelong Program Analysis & Transformation** | 2004 | [Paper](https://dl.acm.org/doi/10.5555/977395.977673) |
| **Google MLIR** | **MLIR: A Compiler Infrastructure for the End of Moore's Law** | 2020 | [Paper](https://arxiv.org/abs/2002.11054) |
| **Meta Glow** | **Glow: Graph Lowering Compiler Techniques for Neural Networks** | 2018 | [Paper](https://arxiv.org/abs/1805.00907) |
| **Intel PlaidML** | **Stripe: Tensor Compilation via the Nested Polyhedral Model** | 2019 | [Paper](https://arxiv.org/abs/1903.06498) |
| **Triton** | **Triton: An Intermediate Language and Compiler for Tiled Neural Network Computations** | 2019 | [Paper](https://dl.acm.org/doi/10.1145/3315508.3329973) |
| **Triton** | **Geak: Introducing Triton Kernel AI Agent & Evaluation Benchmarks** | 2025 | [Paper](https://arxiv.org/abs/2507.23194) |
| **CUDA/ROCm** | **GPGPU Computing** | 2014 | [Paper](https://arxiv.org/abs/1408.6923) |
| **CUDA/ROCm** | **GPU Programming Model vs. Vendor Compatibility Overview** | 2023 | [Paper](https://arxiv.org/abs/2309.05445) |
| **CUDA/ROCm** | **Optimizing sDTW for AMD GPUs** | 2024 | [Paper](https://arxiv.org/abs/2403.06931) |
| **GPU ISA & Architecture** | **Demystifying the Nvidia Ampere Architecture through Microbenchmarking and Instruction-level Analysis** | 2023 | [Paper](https://arxiv.org/abs/2208.11174) |
| **GPU ISA & Architecture** | **Cambricon: An Instruction Set Architecture for Neural Networks** | 2016 | [Paper](https://dl.acm.org/doi/10.1145/3331469) |

*Need to add some compound AI papers, Graphine, and a few others*

---

## 📅 Schedule

| Week | Topics | Description | Notes/Links |
|------|--------|-------------|-------------|
| **Aug 25-27** | Course Introduction & Overview<br>Introduction to Compilers for AI | Lecture<br>Lecture |  |
| **Sep 1-3** | Labor Day (Holiday)<br>Language-Level AI Compiler Systems I | <br> |  |
| **Sep 8-10** | Language-Level AI Compiler Systems II<br>Prompt Engineering and Program Synthesis | <br> |  |
| **Sep 15-17** | Deep Learning Computational Graphs<br>Compiler Fundamentals for ML | <br> |  |
| **Sep 22-24** | The PyTorch Ecosystem<br>JAX and Functional Programming for ML | <br> |  |
| **Sep 29 - Oct 1** | TVM: Tensor Virtual Machine<br>Quantization Techniques | <br> |  |
| **Oct 6-8** | Memory Optimization<br>GPU Programming for AI | <br> |  |
| **Oct 13-15** | Fall Study Break (Holiday)<br>TensorRT and Inference Optimization | <br> |  |
| **Oct 20-22** | Large Language Model Optimization<br>Distributed Training Systems | <br> |  |
| **Oct 27-29** | Heterogeneous Computing<br>Hardware-Software Co-design | <br> |  |
| **Nov 3-5** | Emerging AI Chip Architectures<br>Emerging Techniques in AI Compilation | <br> |  |
| **Nov 10-12** | Datacenter-scale AI Infrastructure<br>Project Presentations I | <br> |  |
| **Nov 17-19** | Advanced Optimization Techniques<br>Guest Lectures | <br> |  |
| **Nov 24-26** | Project Work Session<br>Thanksgiving Recess (Holiday) | <br> |  |
| **Dec 1-3** | Final Project Presentations<br>Course Wrap-up & Future Directions | <br> |

---

## 📊 Grading

This is a very 'do based' course, we'll be learning, creating, innovating and sharing. A significant portion of the grade is allocated to the research project. Most (if not all) does very well in this class as long as you stay engaged on the journey. Lets create some amazing stuff! 😊

**Research Project: 50%**
- Project Pitch: 5%
- Project Update: 5%
- Video Lightning Talk: 10%
- Final Presentation: 15%
- Paper Write-Up: 15%

**Impact and Engagement: 50%**
TBD

---

## 🛠 Additional Details
- https://medium.com/geekculture/ai-compilers-ae28afbc4907
- https://developer.nvidia.com/blog/understanding-ptx-the-assembly-language-of-cuda-gpu-computing/?utm_source=chatgpt.com
- https://rocm.blogs.amd.com/software-tools-optimization/amdgcn-isa/README.html?utm_source=chatgpt.com

---

⭐ *Prepare to build the next generation of compilers and runtimes for AI.*  
