<p align="center">
  <a href="https://smx.icegame.ro">
    <img src="https://smx.icegame.ro/images/logo-2.png" alt="SourceMod Online Compiler">
  </a>
</p>

[![Website](https://img.shields.io/badge/Website-smx.icegame.ro-blue)](https://smx.icegame.ro)
[![SourceMod](https://img.shields.io/badge/SourceMod-1.7.3%20to%201.12.0-orange)](https://smx.icegame.ro)
[![Languages](https://img.shields.io/badge/Interface-16%20languages-green)](https://smx.icegame.ro)

#### 👉 **[smx.icegame.ro](https://smx.icegame.ro)** **is a free online compiler for [SourceMod](https://www.sourcemod.net/) plugins (CS:S, CS:GO, TF2, L4D, L4D2, DoD and other Source mods).**
#### **Upload your `.sp` file or paste the source code, pick the SourceMod version, and download the compiled `.smx` plugin. No local SourcePawn compiler required.**

## Why this exists

Compiling a SourceMod plugin normally means downloading the right SourceMod package, matching the compiler (`spcomp`) to your server version, and collecting every include file by hand. This compiler does it all in the browser: you pick the version, send the source, and get the `.smx` back.

## Features

**Simple workflow**
- Upload a `.sp` file or paste the source code directly into the page
- Compiled `.smx` plugin is available to download as soon as the build succeeds
- Compiler output can be shown on every compilation, so you can see warnings and errors line by line
- Option to automatically import the source code, so you can keep working on it

**SourceMod versions**
- Build against **1.7.3, 1.8.0, 1.9.0, 1.10.0, 1.11.0 or 1.12.0**
- Pick the version that matches your server, so the plugin is compiled with the same includes you run in production

**Custom includes**
- If your plugin depends on an external `.inc` file that the compiler does not provide, you can upload your own include files

**Sandboxed compilation**
- Compilation runs in a sandbox, separated from the website
- Live status indicators for the database, server load and build sandbox directly in the header

**Interface**
- 16 languages: English, Romanian, Italian, Hungarian, Serbian, Bulgarian, German, French, Russian, Turkish, Portuguese, Hindi, Spanish, Arabic, Japanese, Chinese
- Compilation statistics by SourceMod version (successful and failed builds)
- Navbar button to switch between the SourceMod, CounterStrikeSharp and AMX Mod X compilers

## How to use it

1. Go to **[smx.icegame.ro](https://smx.icegame.ro)** and pick your interface language.
2. Select the **SourceMod version**. Not sure which one? Type `sm version` in the server console to check what your server runs.
3. Select your **`.sp`** file, or paste the source code into the box.
4. If the plugin needs extra includes, press **Upload .inc** and add them first.
5. Press **Compile Now**.
6. If the build succeeds, download the compiled **`.smx`** and upload it to `addons/sourcemod/plugins/` on your server.

## Screenshots

<details>
<summary>📸 Main page (click to expand)</summary>

<br>

[![Main page](https://github.com/barlap/sourcemod-web-compiler/blob/main/smx_main_page.PNG?raw=true)](https://github.com/barlap/sourcemod-web-compiler/blob/main/smx_main_page.PNG)

</details>

<details>
<summary>📸 Compilation result (click to expand)</summary>

<br>

[![Compilation result](https://github.com/barlap/sourcemod-web-compiler/blob/main/smx_compiler_result.PNG?raw=true)](https://github.com/barlap/sourcemod-web-compiler/blob/main/smx_compiler_result.PNG)

</details>

## Good to know

- The compiler takes a single `.sp` file. If your plugin includes custom `.inc` files, upload them with the **Upload .inc** button before compiling.
- Always compile with the SourceMod version that matches your server, to avoid errors caused by missing or different natives and methodmaps.

## Links

- Compiler: https://smx.icegame.ro
- IceGame Romania: https://icegame.ro

## Feedback

Found a bug or have a suggestion? Open an [issue](https://github.com/barlap/sourcemod-web-compiler/issues). Feedback is welcome.
