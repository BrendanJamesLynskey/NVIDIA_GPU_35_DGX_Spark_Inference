# LLM Inference on DGX Spark — Practical Numbers and Patterns

Realistic tok/s on every model size from 1 B to 671 B, framework selection (Ollama, vLLM, NIM, TRT-LLM), quantisation choice (BF16 / FP8 / MX-FP4 / AWQ-INT4), KV cache placement on unified memory, batching strategy on a bandwidth-bound box, long context with FP8 KV, multimodal stacks (vision / ASR / TTS), and two-Spark pipeline parallel. Includes an interactive inference estimator that turns model + precision + batch + pairing into expected tok/s.

**Live site:** https://brendanjameslynskey.github.io/NVIDIA_GPU_35_DGX_Spark_Inference/

Part of the [NVIDIA GPU Architectures series](https://github.com/BrendanJamesLynskey/LLMs#nvidia-gpu-architectures).
