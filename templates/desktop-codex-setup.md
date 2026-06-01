# Desktop Codex Setup Checklist

Use this checklist when setting up a new Windows computer for Pablo's research workflow.

## Install Apps

1. Install Codex from the official OpenAI/Codex source.
2. Install Git for Windows from https://git-scm.com/install/windows.
3. Install GitHub Desktop.
4. Install Dropbox and sign into Pablo's account.

## Configure Git For Windows

- Initial branch: override to `main`.
- PATH: Git from the command line and also from 3rd-party software.
- SSH: bundled OpenSSH.
- HTTPS: native Windows Secure Channel.
- Line endings: checkout Windows-style, commit Unix-style.
- Terminal: MinTTY.
- Pull behavior: fast-forward or merge.
- Credentials: Git Credential Manager.
- File system caching: enabled.
- Symbolic links: disabled unless needed.

## Clone The Suite

In GitHub Desktop, clone:

`https://github.com/pablobrugarolas/pbrugaro_research_suite`

Recommended local path:

`C:\Users\<desktop-user>\Dropbox\Codex\pbrugaro_research_suite`

GitHub is the source of truth. Dropbox is a backup and sync layer.

## Install Global Codex Instructions

Copy:

`templates\global-codex-AGENTS.md`

to:

`C:\Users\<desktop-user>\.codex\AGENTS.md`

## Install Suite Skills And Agents

Copy the suite skills from:

`C:\Users\<desktop-user>\Dropbox\Codex\pbrugaro_research_suite\.codex\skills`

to:

`C:\Users\<desktop-user>\.codex\skills`

Copy the suite agents from:

`C:\Users\<desktop-user>\Dropbox\Codex\pbrugaro_research_suite\.codex\agents`

to:

`C:\Users\<desktop-user>\.codex\agents`

Restart Codex after copying these folders.

## Verify

- `git --version` works in PowerShell.
- GitHub Desktop shows the suite repo on `main`.
- Codex shows Git review controls inside the suite repo.
- `C:\Users\<desktop-user>\.codex\AGENTS.md` contains Pablo's global principles.
- `C:\Users\<desktop-user>\.codex\skills\pbrugaro_research_suite\SKILL.md` exists.
- A fresh Codex session can see the suite skills.
