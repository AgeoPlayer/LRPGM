<div align="center">

<a href="https://lrpgm.netlify.app/">
  <img src="https://lrpgm.netlify.app/img/icon.png" width="116" alt="LRPGM logo">
</a>

# LRPGM

### Translate RPG Maker games without installing Ruby, changing the original files, or breaking the game.

LRPGM understands the project structure, protects sensitive commands, and applies translations through a reversible workflow—so you can focus on the text instead of rebuilding a broken game.

[![Download LRPGM](https://img.shields.io/badge/Download_LRPGM-087FF5?style=for-the-badge&logo=windows11&logoColor=white)](https://lrpgm.netlify.app/download)
[![Official website](https://img.shields.io/badge/Official_website-172033?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lrpgm.netlify.app/)
[![Discord](https://img.shields.io/badge/Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FFz58GqCBM)

[English](README.md) · [Português](README.pt-BR.md)

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows11&logoColor=white)
![RPG Maker](https://img.shields.io/badge/RPG%20Maker-XP%20%7C%20VX%20%7C%20VX%20Ace%20%7C%20MV%20%7C%20MZ-087FF5)
![Development](https://img.shields.io/badge/Development-active-22C55E)

**Over 250 subscribers · over 500 community members · over 3,000 downloads**

</div>

---

<div align="center">
  <img src="https://lrpgm.netlify.app/img/evolution/image_v4.png" alt="LRPGM interface" width="100%">
</div>

## More than a translator

Translating an RPG Maker game is not as simple as replacing words. A modified command, an ignored line break, an incompatible font, or an incorrect image name can prevent the game from starting or break events during gameplay.

LRPGM was built to handle the complete workflow. It identifies the engine and project structure, extracts useful text, preserves sensitive elements, lets you review the result, and applies the translation while keeping the project playable.

> **The goal is not only to translate. It is to translate safely.**

## Why use LRPGM?

| Easy to start | Smart during translation | Safe when applying |
| --- | --- | --- |
| Does not require Ruby | Detects control codes and sensitive structures | Preserves the original game files |
| Automatically identifies the RPG Maker version | Recognizes custom line breaks and patterns | Uses a separate plugin and translation file |
| Organizes projects in a single library | Avoids translating elements that must remain unchanged | Lets you disable the translation and restore the original state |
| Lets you pause, continue, and review your work | Adjusts fonts and references that could break the game | Validates content before applying changes |

## Legacy and modern RPG Maker support

LRPGM provides its own reading and writing support for formats used by **RPG Maker XP, VX, and VX Ace**, without requiring an external Ruby installation. For **MV and MZ**, it understands the modern project structure, files, plugins, and control patterns.

Supported engines:

- RPG Maker XP
- RPG Maker VX
- RPG Maker VX Ace
- RPG Maker MV
- RPG Maker MZ

> Modified games, third-party plugins, and custom project structures may require specific compatibility adjustments. The integrated reporting system helps turn real compatibility cases into reusable improvements.

## A complete translation workflow

### 1. Add the game

Select the project folder. LRPGM identifies the engine, file structure, active plugins, and the most suitable workflow.

### 2. Extract only what matters

Choose dialogue, events, databases, plugins, scripts, and other detected resources. Filters reduce noise and protect commands that must not be handled as ordinary text.

### 3. Translate with context

LRPGM identifies the languages found in the project and lets you choose the target language and the translation provider that best suits your needs.

### 4. Review before applying

Correct names, recurring terms, and sentences directly in the review workflow. You remain in control before any change is applied to the game.

### 5. Apply reversibly

In the main workflow, LRPGM adds a lightweight plugin and a separate translation file. Original files remain preserved, and disabling the plugin can return the game to its previous state.

## Protection against broken games

- Preserves commands, variables, scripts, and plugin patterns.
- Detects RPG Maker control codes used in messages.
- Recognizes standard and custom line breaks.
- Replaces incompatible fonts when necessary.
- Protects technical values that should not be translated.
- Corrects image and file references when translated names could cause errors.
- Reuses compatibility profiles and learned corrections.
- Sends technical reports from the application with the context needed for investigation.

## Download and installation

LRPGM is available for **Windows 10 and Windows 11**.

### [Download the latest version from the official website](https://lrpgm.netlify.app/download)

The download page offers two official installers:

- **Full Installer:** includes the required .NET runtime and is recommended for most users.
- **Compact Installer:** smaller download that requires the .NET 9 Desktop Runtime x64 to be installed.

The installer verifies file integrity before making changes to the computer. Download LRPGM only from the official website or the files published in this repository's **Releases** section.

## See LRPGM in action

- [Discover the LRPGM workflow](https://www.youtube.com/watch?v=OuEVYdBpO40)
- [Watch a practical demonstration](https://www.youtube.com/watch?v=4CCLuPYL7bE)
- [Explore more LRPGM features](https://www.youtube.com/watch?v=An9FgHVAh_I)

## Plans and access

You can download LRPGM for free and try its main workflow. **Basic** and **Plus** plans provide additional features, expanded limits, more translation providers, and options for advanced workflows.

[Compare LRPGM plans](https://lrpgm.netlify.app/adquirir)

## Help, community, and reports

- [Help center](https://lrpgm.netlify.app/help)
- [Official Discord server](https://discord.gg/FFz58GqCBM)
- [Update history](https://lrpgm.netlify.app/updates)
- [Contact](https://lrpgm.netlify.app/contact)

Game-specific problems should be reported through the LRPGM application. This allows the report to include the engine, application version, and technical context required for investigation. For account, access, and general questions, use the official Discord server.

## About this repository

This is LRPGM's public presentation and official distribution repository. It contains project information, release notes, and published installers.

The LRPGM source code and internal infrastructure are not distributed in this repository.

## Frequently asked questions

<details>
<summary><strong>Do I need to install Ruby?</strong></summary>

No. LRPGM has its own technology for working with supported legacy formats and does not depend on an external Ruby installation.

</details>

<details>
<summary><strong>Does the translation replace the original game files?</strong></summary>

Not in the main workflow. The translation is applied through a plugin and a separate file, preserving the original game data and allowing a reversible application.

</details>

<details>
<summary><strong>Can I review the translation before applying it?</strong></summary>

Yes. LRPGM includes a review workflow for correcting names, sentences, and recurring terms before applying the translation.

</details>

<details>
<summary><strong>Are all games automatically compatible?</strong></summary>

LRPGM supports XP, VX, VX Ace, MV, and MZ. However, heavily modified games or projects with custom plugins may require compatibility adjustments. These cases can be reported directly through the application.

</details>

<details>
<summary><strong>Is LRPGM free?</strong></summary>

There is a free way to get started. Basic and Plus plans unlock additional features, providers, limits, and advanced options.

</details>

---

<div align="center">

**LRPGM — simple on the outside, intelligent within, and safe where it matters.**

RPG Maker is a trademark of its respective owners. LRPGM is an independent tool and is not officially affiliated with the creators of RPG Maker.

</div>
