# Linear-Quantum-Results
This repository contains the quantum implementations of the linear layers for the paper, **Quantum Implementation of Linear and Non-Linear Layers** by Anubhab Baksi, Sumanta Chakraborty, Anupam Chattopadhyay, Matthew Chun, SK Hafizul Islam, Kyungbae Jang, Hyunji Kim, Yujin Oh, Soham Roy, Hwajeong Seo, Siyi Wang; published in IEEE 37th International System-on-Chip Conference (SOCC), Dresden, Germany, 2024.

Conference URL: https://www.ieee-socc.org/ 

Publication URL: https://ieeexplore.ieee.org/abstract/document/10737862 

## Results
The following results are the currently best-known (those are being updated even after the camera-ready version of the paper is submitted):

* AES MixColumn: 97 × 16 (CNOT count × Quantum depth) ([file1](./AES/aes_mixcol-97xor-16qdepth-slp.txt))
* AES MixColumn: 95 × 31 (CNOT count × Quantum depth) ([file2](./AES/aes_mixcol-95xor-31qdepth-slp.txt))
* SHA-2:
    * Σ₀: 107 × 36 (CNOT count × Quantum depth) ([file3](./SHA-2/sha2_SIGMA_0-107xor-36qdepth.txt))
    * Σ₁: 115 × 29 (CNOT count × Quantum depth) ([file4](./SHA-2/sha2_SIGMA_1-115xor-29qdepth.txt))
    * σ₀: 109 × 32 (CNOT count × Quantum depth) ([file5](./SHA-2/sha2_SIGMA0-109xor-32qdepth.txt))
    * σ₁: 101 × 31 (CNOT count × Quantum depth) ([file6](./SHA-2/sha2_SIGMA1-101xor-31qdepth.txt))
* ASCON:
    * Σ₀: 317 × 96 (CNOT count × Quantum depth) ([file7](./ASCON/ascon_SIGMA_0-317xor-96qdepth.txt))
    * Σ₁: 343 × 100 (CNOT count × Quantum depth) ([file8](./ASCON/ascon_SIGMA_1-343xor-100qdepth.txt))
    * Σ₂: 325 × 93 (CNOT count × Quantum depth) ([file9](./ASCON/ascon_SIGMA_2-325xor-93qdepth.txt))
    * Σ₃: 300 × 79 (CNOT count × Quantum depth) ([file10](./ASCON/ascon_SIGMA_3-300xor-79qdepth.txt))
    * Σ₄: 346 × 106 (CNOT count × Quantum depth) ([file11](./ASCON/ascon_SIGMA_4-346xor-106qdepth.txt))
    
## Format
All the results are in-place SWAP and in-place XOR operations, except [file2](./AES/aes_mixcol-95xor-16qdepth-slp.txt) (here, the results are in-place assignments and in-place XOR operations).
