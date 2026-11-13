# Communicate using Markdown

## Overview 
In this project you learn about markdown files and how to use them.

## Features

* Contains checks to make sure you are doing it correct

* Has detailed instructions

* Has links

## Contents

* [Overview](#overview)

* [Features](#features)

* [Prerequisites](#prerequisites)

* [Installation](#installation)

* [Usage](#usage)

* [Expected output](#expected-output)

* [Project files](#project-files)

* [Contributing](#contributing)

* [Support](#support)

* [License](#license)

* [Troubleshooting](#troubleshooting)

* [Review checklist](#review-checklist)

## Prerequisites

Use a web browser to read the project on GitHub. To work on a local copy, install Git and a text editor such as VS Code. A GitHub account with access to the repository is required to contribute.

## Installation

This project is a Markdown document, so there is no package to install or server to start. Run these commands in a terminal to download the repository and enter its folder:

```bash
git clone https://github.com/Ojas-Khobragade/Markdown-Activity.git
cd Markdown-Activity
```

To verify setup, open `day-1.md` in your editor. If the file is present, setup worked. No build or dependency installation is required.

## Usage

From the `Markdown-Activity` repository folder, display the journal in a terminal with this command. On Windows PowerShell, use `Get-Content day-1.md` instead.

```bash
cat day-1.md
```

For formatted reading, open [the journal](../day-1.md) on GitHub. To edit it, select the pencil icon, change the text, and use the Preview tab to check the result. Check or uncheck tasks by editing their Markdown and committing your changes.

## Expected output

The terminal displays the source Markdown, which is the raw text with symbols like `#` and `- [ ]` still visible. Your title may differ from this shortened example:

```text
# Daily Learning

## Morning Planning
```

On GitHub, the same file is rendered Markdown: headings appear at different sizes and task markers become checkboxes.

## Project files

| File | Purpose |
| --- | --- |
| [Journal](../day-1.md) | Daily plans, code samples, and learning metrics |
| [Project README](README.md) | Setup and usage instructions |

## Contributing

To suggest a change, fork the repository or create a new branch from the default branch. Keep each change focused on one improvement, such as fixing a typo or clarifying one section. Preview your Markdown on GitHub and click every link to confirm it works. Then open a pull request with a short title and a description of what you changed and why.

This project has no application test suite to run for the journal. Instead, the course's GitHub Actions checks evaluate submissions automatically, so check the pull request's Checks tab after you open it.

## Support

If you are stuck or find a mistake, ask for help by opening an issue on the [Markdown-Activity Issues tab](https://github.com/Ojas-Khobragade/Markdown-Activity/issues). Include the lesson number, what you tried, and the exact error message or a description of what you expected to happen. Do not post passwords, tokens, or other private information.

## License

This project is distributed under the [MIT License](../LICENSE). Read the license for its permissions and conditions.

## Troubleshooting

**Problem:** Running `cat day-1.md` prints `cat: day-1.md: No such file or directory`.

**Solution:** You are probably not in the repository's root folder. Run `cd Markdown-Activity` to enter the cloned folder, then run `ls` (or `dir` on Windows) to confirm `day-1.md` is listed. If it is still missing, check that you are on the branch that contains the journal, since a file that exists on `start-blog` may not exist on another branch until it is merged.

---

## Review checklist

- [x] Confirmed the purpose, audience, and feature descriptions are accurate.
- [x] Followed setup and usage instructions and compared the result.
- [x] Tested Contents and file links and checked image alternative text.
- [x] Verified contribution, support, and license information.

---

<img src="https://octodex.github.com/images/Professortocat_v2.png" alt="Mona, the GitHub Octocat mascot dressed as a professor" align="right" height="200px" />

Hey Ojas-Khobragade!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![Go to Exercise](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/Ojas-Khobragade/Markdown-Activity/issues/1)

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
