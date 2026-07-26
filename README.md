# riscv-edge-ai-accelerator



The proposed system architecture integrates a RISC-V based processing unit with a tightly coupled AI accelerator implemented on FPGA. The processor manages system control, instruction execution, and data movement between memory and the accelerator.The AI accelerator, based on a systolic array architecture, is designed to efficiently perform matrix multiplication and convolution operations commonly used in AI inference workloads. Input data and weights are stored in on-chip memory (BRAM) and supplied to the accelerator for parallel computation.
The tightly coupled integration between the processor and accelerator enables low-latency data exchange and improved computational efficiency. This architecture supports scalable, real-time edge AI processing while maintaining low power consumption and high performance on adaptive FPGA platforms.
