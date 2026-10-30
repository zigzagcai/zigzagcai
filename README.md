## Hi there 👋

I am Zheng Cai, nickname zigzagcai, an AI Infra engineer, working on (M)LLM pre/post-train and Automatic kernel/framework optimization.

I love the general idea of open-source, learn from the open-source community and try my best to contribute back.

Selected code/knowledge I have ever shared:
1. Developed sequence parallelism for DSA(DeepSeek Sparse Attention)-like models in vLLM, which delivered 25.42% TTFT redution and 32.59% throughput improvement for GLM-5.3-Flash under 1M long context length. https://github.com/vllm-project/vllm/pull/54951
2. Developed CUDA kernel for variable length Mamba training and delivered 2~4x end-to-end training speedup. https://github.com/state-spaces/mamba/pull/244
3. Figure out and fix deadlock for Colossal.AI training framework under very large scale (>2k gpus) training scenarios. https://github.com/hpcaitech/ColossalAI/pull/5625
4. Implement FSDP+EP+Ulysses_SP for 671B full-size DeepSeek V3 model. https://github.com/zigzagcai/DeepSeekV3
5. Figure out and fix accuracy issue with NCCL all-reduce under real world LLM training. https://zhuanlan.zhihu.com/p/701623664
6. My best practice on how to deal with PyTorch dataloder memory leakage caused by Python copy-on-write mechanism. https://github.com/pytorch/pytorch/issues/13246#issuecomment-2264647131
7. Support NoGIL experimental feature for NumPy-1.18.5. https://github.com/colesbury/numpy/commit/0d6ef2770268711ee6417792ba0da35fcb264bf5
