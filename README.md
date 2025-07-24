# <a href="https://github.com/xCollateral/VulkanMod"> <img src="./src/main/resources/assets/vulkanmod/Vlogo.png" width="30" height="30"/> </a> VulkanMod (DynamicFox Fork)

This is a fabric mod that introduces a brand new **Vulkan** based voxel rendering engine to **Minecraft Java** in order to both replace the default OpenGL renderer and bring performance improvements.

Also, it now adds a **DynamicFox**.  
Yes, really.  
Blame [TryDkg.wtf](https://trydkg.wtf) for the typo that started it all:  
> *"When dynamic fox setting in vulcan mod"*

## 🦊 What is DynamicFox?

A typo. A prophecy. A new entity.  
This fork does **not** add DynamicFog. It adds something far more powerful: the **DynamicFox**.  
It’s fast. It’s mysterious. It’s probably judging your render pipeline.

### Why?
- Highly experimental project that overhauls and modernizes the internal renderer for Minecraft. <br>
- Updates the renderer from OpenGL 3.2 to Vulkan 1.2.  <br>
- Provides a potential reference for a future-proof Vulkan codebase for Minecraft Java. <br>
- Utilizes the VulkanAPI to allow for capabilities not always possible with OpenGL. <br>
- Including reduced CPU Overhead and use of newer, modern hardware capabilities. <br>
- Also includes a **fox**. A dynamic one. 🦊

### Demonstration Video:

[![Demostration Video](http://img.youtube.com/vi/sbr7UxcAmOE/0.jpg)](https://youtu.be/sbr7UxcAmOE)

## FAQ
- Remember to check the [Wiki](https://github.com/xCollateral/VulkanMod/wiki) we wrote before asking for support!
- No, the fox is not in the wiki. It defies documentation.

## Installation

### Download Links:

- [![CurseForge](https://cf.way2muchnoise.eu/full_635429_downloads.svg?badge_style=flat)](https://www.curseforge.com/minecraft/mc-mods/vulkanmod)

- [![Modrinth Downloads](https://img.shields.io/modrinth/dt/JYQhtZtO?logo=modrinth&label=Modrinth%20Downloads)](https://modrinth.com/mod/vulkanmod/versions)

- [![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/xCollateral/VulkanMod/total?style=flat-square&logo=github&label=Github%20Downloads)](https://github.com/xCollateral/VulkanMod/releases)

### Install guide:
>1) Install the [fabric modloader](https://fabricmc.net).
>2) Download and put the `Vulkanmod.jar` file into `.minecraft/mods`
>3) Enjoy!
>4) Watch out for foxes.

## Useful links
<table>
    <tr>
      <th> Discord server</th>
      <th> Ko-Fi</th>
    </tr>
  <tr>
    <td style="text-align:center"> 
        <a href="https://discord.gg/FVXg7AYR2Q"> 
            <img alt="Discord" align="top" src="https://img.shields.io/discord/963180553547419670?style=flat-square&logo=discord&logoColor=%23FFFFFF&label=Vulkanmod%20official%20discord%20server&labelColor=%235865F2&color=%235865F2">
        </a>
     </td>
    <td>
        <a href="https://ko-fi.com/V7V7CHHJV">
            <img alt="Static Badge" align="top" src="https://img.shields.io/badge/KoFi-%23ff5e5b?logo=ko-fi&logoColor=%23FFFFFF&link=https%3A%2F%2Fko-fi.com%2FV7V7CHHJV">
        </a>
    </td>
  </tr>
</table>

## Features

### Optimizations:
>- [x] Multiple chunk culling algorithms
>- [x] Reduced CPU overhead
>- [x] Improved GPU performance
>- [x] Indirect Draw mode (reduces CPU overhead)
>- [x] Chunk rendering optimizations

### New changes:
>- [x] Native Wayland support
>- [x] GPU selector
>- [x] Windowed fullscreen mode
>- [x] Revamped graphic settings menu
>- [x] Resizable render frame queue
>- [ ] Shader support
>- [ ] Removed Herobrine
>- [x] **Added DynamicFox** (thanks TryDkg.wtf)

## Notes
- This mod is still in development, please report issues in the [issue tab](https://github.com/xCollateral/VulkanMod/issues) with logs attached!
- This mod isn't just "Minecraft on Vulkan" (e.g: [zink](https://docs.mesa3d.org/drivers/zink.html) ), it is a full rewrite of the Minecraft renderer.
- Also, there's a fox now. It’s dynamic. Don’t ask how. Just accept it.
- ⚠️ **If your issue involves the DynamicFox, do NOT bother xCollateral.**  
  That chaos was unleashed by **CodedByDuke**, not the original author.  
  All fox-related bugs, existential crises, and typo-induced anomalies should be directed to me.

---

> “You asked for fog. You got a fox. That’s on you.”
