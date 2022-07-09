<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">MangoDeath Launcher</h1>

<em><h5 align="center">(Formalmente Helios Launcher)</h5></em>

[<p align="center"><img src="https://img.shields.io/github/workflow/status/dscalzi/HeliosLauncher/Build.svg?style=for-the-badge" alt="gh actions">](https://github.com/dscalzi/HeliosLauncher/actions) [<img src="https://img.shields.io/github/downloads/dscalzi/HeliosLauncher/total.svg?style=for-the-badge" alt="downloads">](https://github.com/dscalzi/HeliosLauncher/releases) <img src="https://forthebadge.com/images/badges/winter-is-coming.svg"  height="28px" alt="winter-is-coming"></p>

<p align="center">Launcher para ingresar a MangoDeath2 con Mods.</p>

![Screenshot 1](https://i.imgur.com/6o7SmH6.png)
![Screenshot 2](https://i.imgur.com/x3B34n1.png)

## Características

* 🔒 Gestión completa de la cuenta.
  * Añadir varias cuentas y cambiar fácilmente entre ellas.
  * Autenticación de Microsoft (OAuth 2.0) + Mojang (Yggdrasil) totalmente compatible.
  * Las credenciales nunca se almacenan ni se transmiten directamente a Mojang.
* 📂 Efficient asset management.
  * Receive client updates as soon as we release them.
  * Files are validated before launch. Corrupt or incorrect files will be redownloaded.
* ☕ **Automatic Java validation.**
  * If you have an incompatible version of Java installed, we'll install the right one *for you*.
  * You do not need to have Java installed to run the launcher.
* 📰 News feed natively built into the launcher.
* ⚙️ Intuitive settings management, including a Java control panel.
* Supports all of our servers.
  * Switch between server configurations with ease.
  * View the player count of the selected server.
* Automatic updates. That's right, the launcher updates itself.
*  View the status of Mojang's services.

This is not an exhaustive list. Download and install the launcher to gauge all it can do!

## Downloads

You can download from [GitHub Releases](https://github.com/dscalzi/HeliosLauncher/releases)



**Supported Platforms**

If you download from the [Releases](https://github.com/dscalzi/HeliosLauncher/releases) tab, select the installer for your system.

| Platform | File |
| -------- | ---- |
| Windows x64 | `Helios-Launcher-setup-VERSION.exe` |
| macOS x64 | `Helios-Launcher-setup-VERSION-x64.dmg` |
| macOS arm64 | `Helios-Launcher-setup-VERSION-arm64.dmg` |
| Linux x64 | `Helios-Launcher-setup-VERSION.AppImage` |


## Resources

* [Wiki][wiki]
* [Nebula (Create Distribution.json)][nebula]
* [v2 Rewrite Branch (Inactive)][v2branch]

The best way to contact the developers is on Discord.

[![discord](https://discordapp.com/api/guilds/211524927831015424/embed.png?style=banner3)][discord]

---

### See you ingame.


[nodejs]: https://nodejs.org/en/ 'Node.js'
[vscode]: https://code.visualstudio.com/ 'Visual Studio Code'
[mainprocess]: https://electronjs.org/docs/tutorial/application-architecture#main-and-renderer-processes 'Main Process'
[rendererprocess]: https://electronjs.org/docs/tutorial/application-architecture#main-and-renderer-processes 'Renderer Process'
[chromedebugger]: https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome 'Debugger for Chrome'
[discord]: https://discord.gg/zNWUXdt 'Discord'
[wiki]: https://github.com/dscalzi/HeliosLauncher/wiki 'wiki'
[nebula]: https://github.com/dscalzi/Nebula 'dscalzi/Nebula'
[v2branch]: https://github.com/dscalzi/HeliosLauncher/tree/ts-refactor 'v2 branch'
