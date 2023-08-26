# VanBitCrackenS1-Distributed-Puzzle-66-Address-Scanner
Welcome to VanBitCrackenS1, a distributed puzzle 66 address scanner designed to explore a vast range of possibilities and uncover hidden addresses. This repository offers an innovative solution for the cryptographic challenge presented by puzzle 66 addresses, utilizing a distributed approach to efficiently scan through 588 ranges, each scanning 48 bits in length.

## How to Get Started

1. **Clone the Repository**: Begin by cloning this repository to your local machine using the following command or download the zip file:

   ```sh
   git clone https://github.com/your-username/VanBitCrackenS1-Distributed-Puzzle-66-Address-Scanner

2. **Download the Executable Files**: Inside the cloned repository, you'll find two executable files, `588_ranges.exe` and `VanBitCrackenS1.exe`. Both these files must be placed in the same directory.

3. **Initiating the Scanner**: Run the `588_ranges.exe` executable. This will prompt you to enter a range for scanning. To start, we provide you with the initial range: `(2900a000000000000:2900affffffffffff)`.

4. **Validating the Range**: The script will verify the provided range's correctness. If valid, you'll move to the next step.

5. **Optional: GPU Details**: If you have multiple GPUs, you can enter GPU IDs using the `-gpuId` flag (e.g., `-gpuId 0,1,2`). Otherwise, simply press Enter to proceed.

6. **Running the Scanner**: The script will initiate `VanBitCrackenS1.exe` to scan through the addresses listed in `addresses.txt` within the specified range, including the puzzle 66 address. If any addresses are found, they will be saved in the `found.txt` file in the same directory.

7. **Proof of Work**: The other three addresses are used as proof of work, so be sure to keep the `found.txt` file safe until the scanning process is completed.

8. **Addresses and Private Keys**: If puzzle 66 addresses are discovered, they will be saved in a `found.txt` file, along with their associated private keys.

## Resuming the Scanning Process

If you need to pause and resume your scanning process:

1. **Recording Progress**: After completing a certain number of ranges, your progress will be recorded in the `range.txt` file in the same directory.

2. **Resuming the Scan**: When resuming, input the last completed range as shown in the `range.txt` file when prompted by `588_ranges.exe`.

3. **Continuing from Last Point**: This will allow you to continue your scanning process from where you left off, ensuring no repetition and optimizing your effort.

## Acknowledgments
A big thank you to [WanderingPhilosopher] and their [VanBitCrackenS1] for contributing of this project. Your dedication to open source software is truly inspiring.

[(https://github.com/WanderingPhilosopher/VanBitCrakcenS).]
## Contributing and Feedback

We encourage you to contribute to this project by exploring ways to enhance scanning efficiency, improving UI/UX, and optimizing the scanning algorithms. Feel free to open issues, provide feedback, and collaborate with the community to make this tool even more powerful.

Good luck and happy hunting!

---
Disclaimer: This software is intended for educational and research purposes only. Please ensure you have appropriate permissions to scan addresses.
```
