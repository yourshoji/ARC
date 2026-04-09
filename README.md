<p align="center">
  <img src="https://github.com/user-attachments/assets/026c837d-69ae-42e7-b393-e9d06e530972"  alt="Archery Analytics Preview" width="1100">
</p>

# Archery Performance Analytics (APA)
v1.0 | C-Based Terminal Analytics Tool

## 🎯 Overview
Archery Performance Analytics is a high-performance Command Line Interface (CLI) tool designed for professional archers and coaches. It automates the calculation of accuracy percentages and scoring metrics across various international target standards.

## 🛠 Technical Highlights
* **Dynamic Memory Management:** Utilizes `malloc` and `free` to allocate memory at runtime based on user-selected target configurations.
* **Fail-Safe Input Pipeline:** Implements robust data validation using `scanf` return-code analysis and buffer clearing (`getchar`) to prevent crashes from malformed data.
* **Modular Logic:** Decoupled scoring algorithms using pointer-based data manipulation (pass-by-reference).
* **Professional UX:** Leverages ANSI escape sequences for a themed, high-contrast tactical interface.

## 🏗 Build System
The project uses **CMake** to ensure cross-platform compatibility and automated build orchestration.

### Prerequisites
* C Compiler (GCC, Clang, or MSVC)
* CMake 3.10+

### Installation
```bash
# 1. Clone the repository
git clone https://github.com/yourshoji/APA.git archery-analytics
cd archery-analytics

# 2. Initialize the build environment
mkdir build && cd build

# 3. Configure and Compile
cmake ..
cmake --build .
```


<p align="center">
  <img src="https://github.com/user-attachments/assets/c4ea5326-0d62-4a1f-bc7a-863aa863dd53"  alt="Archery Analytics Preview" width="1100">
</p>
