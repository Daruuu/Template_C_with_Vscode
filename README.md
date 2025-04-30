# Template_C_with_Vscode
This is a clean template for C projects using CMake and Visual Studio Code.
Sure! Here's the **English version** of your `README.md` for a C/CMake project template in VSCode — ideal for future projects:

---

```markdown
# 🛠️ C Project Template with CMake + VSCode

This is a clean template for C projects using **CMake** and **Visual Studio Code**. It includes basic configuration to build, run, and debug your program directly inside VSCode.

---

## 📁 Recommended Structure

```
cub3d/
├── CMakeLists.txt
├── src/
│   ├── main.c
│   └── ...
├── include/
│   ├── cub3d.h
│   └── ...
├── .vscode/
│   ├── launch.json
│   ├── settings.json
│   └── tasks.json
```

---

## ⚙️ VSCode Configuration Files

### `.vscode/launch.json`
Defines how to **run and debug** the program in VSCode.

- Launches the `cub3d` executable
- Opens an external console
- Uses `gdb` for debugging
- Runs the `"build cub3d"` task before launching

### `.vscode/tasks.json`
Defines custom tasks such as building the project.

- Uses `cmake --build build`
- Can be run via `Ctrl + Shift + B` or from the bottom bar

### `.vscode/settings.json`
Sets up your VSCode environment.

- Specifies project folder with `CMakeLists.txt`
- Configures compiler (e.g., `/usr/bin/gcc`)
- Adds include paths for IntelliSense/autocompletion

---

## ✅ Requirements

- GCC: `sudo apt install build-essential`
- CMake: `sudo apt install cmake`
- VSCode Extensions:
  - C/C++
  - CMake Tools

---

## 🚀 Getting Started

1. Clone the project:
   ```bash
   git clone https://github.com/yourusername/c-project-template.git
   cd c-project-template
   ```

2. Create the `build/` directory:
   ```bash
   mkdir build && cd build
   cmake ..
   ```

3. Open in VSCode:
   ```bash
   code .
   ```

4. From the bottom status bar:
   - Select a compiler kit (e.g., GCC)
   - Choose `[Debug]` build mode
   - Click "Build" or press `F5` to run

---

## 🧪 Modular Layout

- **src/** → `.c` source files
- **include/** → project headers
- **CMakeLists.txt** → build configuration
- **.vscode/** → editor and build settings

---

## 🧰 Tips

- Add more tasks (like `clean`, `run`, etc.) to `tasks.json`
- Rename the final binary from `cub3d` to whatever fits your project

---

## 🔒 License

This project is licensed under the MIT License. Use it freely in your own C projects.

```

---
