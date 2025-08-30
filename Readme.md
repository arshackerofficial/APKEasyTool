# APK Easy Tool

A Windows-based tool for **decompiling, recompiling, signing, and managing APK files**.  
This repository contains a Visual Studio solution for continued development of APK Easy Tool, originally created by **Evildog1**.

---

## ⚠️ Credits
This project is based on the work of **[Evildog1](https://forum.xda-developers.com/t/tool-windows-apk-easy-tool-v1-60-2020-02-09.3333960/)**.  
If you continue to develop APK Easy Tool under this name, please **give credit to the original author**.

---

## Features
- Decompile & recompile APKs  
- Sign APKs with your own keys  
- Zipalign APKs for optimization  
- Extract resources  
- GUI interface for easier use compared to CLI tools  
- Integration with `apktool`, `jarsigner`, and related Android utilities  

---

## Requirements
- **Windows 7 or later**  
- **Visual Studio 2019** (or newer) with C# workload installed  
- Java JDK 8+  
- [Apktool](https://ibotpeaches.github.io/Apktool/) (bundled or provided separately)  

---

## Build Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/arshackerofficial/APKEasyTool.git
   cd APKEasyTool
2. Open `APKEasyTool.sln` in **Visual Studio 2019+**.
3. Restore NuGet packages if prompted.
4. Build the solution (`Ctrl+Shift+B`).
5. Run the compiled application from `bin/Debug` or `bin/Release`.

---

## Usage

1. Launch APK Easy Tool.
2. Select an APK file.
3. Choose an action (Decompile, Recompile, Sign, Zipalign, Extract, etc.).
4. Check logs in the console area for progress and error details.

---

## Folder Structure

```
AETShellExt/        # Windows shell extension integration
APKEasyTool/        # Main C# project
Assets/             # Embedded resources
IconRes/            # Application icons
Resources/          # Supporting files
packages/           # NuGet dependencies
APKEasyTool.sln     # Visual Studio solution
Changelog.txt       # Project changelog
Readme.txt          # Legacy readme (replaced by README.md)
```

---

## Development Notes

* Project is written in **C# (WinForms)**.
* Ensure Java paths are correctly set in environment variables (`JAVA_HOME`).
* Apktool must be accessible by the app (bundled JAR or manually added).

---

## License

This repository does not define a custom license. Treat it as a **continuation project**:

* You may build upon it.
* Always credit the original author **Evildog1**.
* Respect Android app licensing when working with APKs.

---

## Acknowledgements

* Original author: **Evildog1**
* Apktool by **iBotPeaches**
* Java SDK/Jarsigner
* Community contributors

```
