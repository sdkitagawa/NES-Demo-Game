# NES Demo Game

Information
---------
  - [What is this repository?](#what-is-this-repository)
  - [How to use this](#how-to-use-this)

## What is this repository?

A Demo project about how to make games for NES, just a bit of fun for someone who was bored.

Built using:

- `Assembly`
- [cc65 Assembler](https://cc65.github.io/)
- [Arm Assembly for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=dan-c-underwood.arm) 
- [ca65 Macro Assembler Language Support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=tlgkccampbell.code-ca65)

## How to use this?

It's pretty simple, all you need is `Visual Studio Code` or any other framework for code editing of your preference.

1a - Download the [cc65 Assembler](https://cc65.github.io/).

1b - This step is optional, if you are using `VSCode` as your default code editor, you can open the `NESDemo.code-workspace` file.

2 - Open the `cl65config.json` using the code editor of your preference.

3 - Change the `executable` path to the path where you downloaded and extracted [cc65 Assembler](https://cc65.github.io/).

4 - Press `CTRL` + `P` (on Windows) or `CTRL` + `SHIFT` + `P` (on macOS) and type `Tasks: Configure Default Build Task` and press `ENTER`.

5 - Last but not least, press `CTRL` + `P` (on Windows) or `CTRL` + `SHIFT` + `P` (on macOS) and type `Tasks: Run Build Task` and press `ENTER`.

6 - Wait until the Assembling process is done and if you did everything correctly, there should now be a file called `NES-Game-demo.nes` inside the workspace.
