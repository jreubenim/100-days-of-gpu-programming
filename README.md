# 🧠 100 Days of GPU Programming

Inspired by the 100-Day GPU Programming challenge by Hkproj on X , this repository tracks daily progress as I explore CUDA, AI kernels, distributed training, and deployment.

## 📅 Progress Tracker

| Day | Topic | Mini-Project / Task | Status | Notes |
|-----|-------|----------------------|--------|-------|
| 1 | GPU vs CPU architecture | Diagram SMs, cores, memory hierarchy | ❌ |  |
| 2 | Install CUDA toolkit, NVCC flags | "Hello GPU" kernel | ❌ |  |
| 3 | Host vs Device code (`__global__`, etc.) | Vector addition (single block) | ❌ |  |
| 4 | Thread hierarchy: grids, blocks, warps | Vector addition (multi-block) | ❌ |  |
| 5 | Memory types: global/shared/registers | Vector copy with shared memory | ❌ |  |
| 6 | Synchronization (`__syncthreads()`) | Tiled matrix multiply | ❌ |  |
| 7 | Host–device transfers (`cudaMemcpy`) | Benchmark copy bandwidth | ❌ |  |
| 8 | Profiling intro: `nvprof` / Nsight Compute | Profile Day 6 kernel | ❌ |  |
| 9 | Warp divergence | Branchy kernel | ❌ |  |
| 10 | Occupancy & launch config | Tune kernel | ❌ |  |

...

| 100 | Final Capstone | Train → Quantize → Serve multimodal API | ❌ |  |

---

## 📚 Resources

- [CS149 Lectures](https://gfxcourses.stanford.edu/cs149/fall23)
- [NVIDIA CUDA Docs](https://docs.nvidia.com/cuda/)
- [GPU Mode Lectures](https://github.com/gpu-mode/lectures/tree/main/)
- [Christian Mills CUDA Notes](https://christianjmills.com/series/notes/cuda-mode-notes.html)
- [LeetGPU](https://leetgpu.com/) – GPU coding practice
