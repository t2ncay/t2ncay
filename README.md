# Tunjay Gafarli

**Compiler & GPU Engineer | Systems Architecture**
CENG Undergrad @ Türkiye-Azerbaijan University / METU.

I build low-level infrastructure that bridges high-level numerical math with bare-metal hardware. My focus is on deterministic execution, memory safety, and making ML frameworks run efficiently on resource-constrained devices.

### ⚙️ Current Focus: Vyne

I am the creator of **Vyne**, a systems programming language with region-based memory management and a multi-target compiler backend (x86, CUDA PTX, AVR, ESP32).

- **Deterministic GPU Training:** Wrote custom "gather" PTX kernels to bypass the `atomicAdd` race conditions that plague default PyTorch CUDA execution. Bit-exact reproducibility verified down to the CSV.
- **Memory Efficiency:** Reduced peak VRAM for ESPCN training from 11.2 MB to **0.65 MB** (94% reduction) using explicit `@device` region preallocation.
- **Bare-Metal Deployment:** Wrote a 42-line Vyne script to turn an ESP32 into a live Wi-Fi radar with a 3.5" SPI display, handling networking, UI, and memory all in one file.

### 🛠️ Tech Stack

| Layer         | Tools & Technologies                                        |
| :------------ | :---------------------------------------------------------- |
| **Languages** | C++, C, CUDA/PTX, Rust, Python, Vyne                        |
| **Compilers** | GCC, Clang, LLVM IR (learning), Vyne IR                     |
| **Hardware**  | ESP32, Arduino Uno R3, NVIDIA RTX 5060                      |
| **Systems**   | Explicit memory management, Arena allocators, Autodiff, DSP |

### 📂 Key Repositories

- **[vyne](https://github.com/t2ncay/vyne)** — The compiler, runtime, and ML ecosystem.
- _More hardware and embedded AI projects coming soon._

### 📫 Contact

If you are working on ML systems, compilers, or edge AI, I am always open to discussing architecture and research collaborations.

- **Personal Blog:** [https://t2ncay.github.io](https://t2ncay.github.io)
- **LinkedIn:** [linkedin.com/in/tuncay-gafarli-345916226](https://www.linkedin.com/in/tuncay-gafarli-345916226/)
- **Email:** [qtuncay70@gmail.com]
