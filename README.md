# Inscript

An ultra-fast, lightweight Notepad alternative built for Windows. Combining the speed of raw C++ with advanced version control and workspace management, Inscript gives you a powerful text editing experience without the bloat.

---

## Key Features

* **Blazing Fast Performance:** Built entirely with C++ and native Windows utilities. No heavy web frameworks, no lag—just pure speed.
* **Version History:** Never lose your progress. Inscript tracks your file's history over a visual timeline. 
* **Branching:** See a point in time you want to explore? Branch your file at any historical timeline marker to spawn a brand new file instantly.
* **Vertical Tabs:** Maximize your screen real estate. Efficiently switch between multiple open files and active documents using a sleek vertical tab layout.
* **Bilingual Text Editing:** Fully optimized for seamless, high-performance text editing in both **Sinhala** and **English**.
* **Zero-Friction Auto-Save:** Inscript automatically saves your newly created and edited files directly to your default or custom-chosen directory. Drop the `Ctrl + S` anxiety.
* **Recent Files Hub:** A welcome dashboard inspired by MS Word that lets you quickly jump back into your past documents right where you left off.

---

## Tech Stack

Inscript is built from the ground up to be close to the metal on Windows systems:

* **Language:** C++
* **Build System:** CMake
* **OS APIs:** Native Windows Utilities / Win32 API

---

## Getting Started

### Prerequisites

To build Inscript from source, ensure you have the following installed on your Windows machine:
* [CMake](https://cmake.org/download/) (Version 3.15 or higher)
* A C++ compiler supporting C++17 or higher (e.g., MSVC via Visual Studio)

### Building from Source

1. **Clone the repository:**
   ```
   git clone [https://github.com/your-username/Inscript.git](https://github.com/your-username/Inscript.git)
   cd Inscript
   ```

2. **Generate the build files using CMake:**
    ```
    mkdir build
    cd build
    cmake ..
    ```

3. **Build the project:**
    ```
    cmake --build . --config Release
    ```

4. Run the executable located in the build/Release folder!

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](/LICENSE) file for details.