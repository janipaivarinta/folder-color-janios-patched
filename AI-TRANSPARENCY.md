# AI Transparency Statement

## Project Information

**Project:** Folder Color – JaniOS Patched Edition  
**Repository:** https://github.com/janipaivarinta/folder-color-janios-patched  
**Original project:** https://github.com/costales/folder-color  
**Original author:** Marcos Alvarez Costales  
**Fork maintainer:** Jani Päivärinta  
**License:** GPL-3.0-or-later

## 1. Purpose

This document provides transparency regarding the use of artificial intelligence (AI) in the development and maintenance of Folder Color – JaniOS Patched Edition.

The project is a modified fork of Folder Color 0.4.2, intended to improve compatibility, error handling, and stability when running with GNOME Files (Nautilus), GTK4, and Debian 13 (trixie).

## 2. AI Tools Used

The following AI tool was used during development:

- **Provider:** OpenAI
- **Tool:** ChatGPT
- **Model:** GPT-6
- **Purpose:** Source code analysis, debugging assistance, patch generation, and technical documentation.

AI was used as a development assistance tool, not as an autonomous software maintainer.

## 3. AI-Assisted Development

ChatGPT assisted with the following activities:

### Source Code Analysis

- Reviewing the original Folder Color 0.4.2 Python source code.
- Identifying potential compatibility and stability problems involving GTK4, GObject, and Nautilus.
- Examining potential causes of Nautilus freezing.
- Suggesting improvements to exception handling and metadata operations.

### Code Modifications

AI assistance was used to generate modifications involving:

- Safer GTK4 icon-theme lookups.
- Handling missing or unavailable icon resources.
- Fallback handling for unsupported Nautilus zoom levels.
- Improved exception handling and diagnostic logging.
- More targeted GIO metadata queries.
- Removal of unnecessary folder modification-time updates.
- Deferred icon-theme initialization.
- Improvements to folder color and emblem handling.

These modifications are intended to improve software reliability while preserving the original functionality.

### Documentation

AI assistance was also used to prepare technical explanations, installation guidance, and this transparency statement.

## 4. Human Involvement and Testing

The development process involved human-directed investigation and testing.

The maintainer:

- Identified and reproduced Nautilus freezing on Debian 13.
- Investigated the problem using Linux diagnostic tools and GDB backtraces.
- Tested alternative GTK4 rendering configurations, including Cairo.
- Isolated the original Folder Color extension as a trigger for the freezing.
- Requested and evaluated AI-assisted source code modifications.
- Installed the patched extension and initiated stability testing.
- Maintains responsibility for reviewing, accepting, and publishing changes.

The AI system did not independently access or operate the maintainer's computer.

## 5. Verification and Limitations

AI-generated code and explanations may contain errors, incomplete assumptions, or compatibility problems.

The initial patch was generated without reproducing the original failure in an equivalent GNOME runtime environment.

At the time of the initial patch development:

- Python syntax validation was reported.
- Runtime stability testing was ongoing.
- The precise underlying cause of the Nautilus freezing had not been conclusively established.
- The patch had not undergone comprehensive automated regression or compatibility testing.

Successful operation in one environment does not guarantee compatibility with every Debian, GNOME, or Nautilus release.

Future releases should document additional testing and any confirmed fixes.

## 6. Authorship and Attribution

Folder Color was originally developed by Marcos Alvarez Costales and contributors.

The original project's copyright notices, licensing terms, and attribution remain applicable.

Jani Päivärinta maintains the JaniOS fork and coordinates its modifications, testing, documentation, and distribution.

Portions of the modified source code and documentation were generated with AI assistance. Such contributions are disclosed here rather than represented as exclusively human-written.

The use of AI does not alter the licensing obligations associated with the original software.

## 7. Responsibility and Maintenance

The project maintainer is responsible for:

- Reviewing and accepting proposed modifications.
- Testing software behavior and compatibility.
- Addressing reported defects.
- Maintaining license compliance and appropriate attribution.
- Deciding whether changes are suitable for release.

AI-generated suggestions are not treated as independently verified technical conclusions.

## 8. Transparency Commitment

This project aims to maintain a transparent record of AI involvement in software development.

Significant future AI-assisted modifications should be documented through Git commits, release notes, or updates to this statement where appropriate.

The goal is to distinguish original upstream contributions, human-directed maintenance, and AI-assisted development clearly.

---

**Maintainer:** Jani Päivärinta  
**Project:** Folder Color – JaniOS Patched Edition  
**Year:** 2026  
**License:** GPL-3.0-or-later
