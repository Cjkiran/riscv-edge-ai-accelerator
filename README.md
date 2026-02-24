# riscv-edge-ai-accelerator

<img width="1839" height="794" alt="image" src="https://github.com/user-attachments/assets/e93d2128-df22-4d03-a4ef-5716a74fe76c" />

The proposed system architecture integrates a RISC-V based processing unit with a tightly coupled AI accelerator implemented on FPGA. The processor manages system control, instruction execution, and data movement between memory and the accelerator.The AI accelerator, based on a systolic array architecture, is designed to efficiently perform matrix multiplication and convolution operations commonly used in AI inference workloads. Input data and weights are stored in on-chip memory (BRAM) and supplied to the accelerator for parallel computation.
The tightly coupled integration between the processor and accelerator enables low-latency data exchange and improved computational efficiency. This architecture supports scalable, real-time edge AI processing while maintaining low power consumption and high performance on adaptive FPGA platforms.
