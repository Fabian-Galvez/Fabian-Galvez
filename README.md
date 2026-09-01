<p align="left">
  <img src="./assets/Fabian-Galvez-README.svg" alt="Hi, I'm Fabian" />
</p>

<br>

> I build tools that help improve workflows,
> and I keep the computers, networks and servers those tools run on working.

<br>



<br>

## Live tools


Single-file apps that run in the browser as GitHub Pages. No install and no login required.

<sub>Download the index.html to run locally and offline.</sub>

| Repository                                                                                                         | Demo                                                 | Description                                                                                                                                                                                                              | Source                                                                    |
| ------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| [DensePack](https://github.com/Fabian-Galvez/DensePack)<br><br>(Also a right-click tool and a plugin for Claude below) | [Try it](https://fabian-galvez.github.io/DensePack/)<br> | Turns pasted text into the smallest image an AI model can still read. <br><br>Sending a condensed image of text instead of the raw text saves 56 to 77 percent of a long agent report, measured across 261 real reports. | [index.html](https://github.com/Fabian-Galvez/DensePack/blob/main/index.html) |
| [Xanini](https://github.com/Fabian-Galvez/Xanini)                                                                      | [Try it](https://fabian-galvez.github.io/Xanini/)<br>    | SVG studio that makes .svg icons, banners and animations that render on GitHub, all from your browser. <br><br>The files you create are yours to keep.                                                                   | [index.html](https://github.com/Fabian-Galvez/Xanini/blob/main/index.html)    |

<br>

---

<br>

## Desktop workflow tools

On Windows download the exe and double click to run, on Linux and macOS, run from the source. No login required. No install required unless stated otherwise.

In depth information and instructions are available in each tool's README.

| Repository                                                                                                   | Demo                                                                                                                                                                            | Description                                                                                                                                                                                                 | Source                                                                                   |
| ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| [DensePack plugin](https://github.com/Fabian-Galvez/DensePack)                                                   | Plugin for Claude Code<br><br><br>Run:<br>```<br>/plugin marketplace add Fabian-Galvez/DensePack```<br> <br> Then:<br>```<br>/plugin install densepack@densepack-marketplace<br>``` | Plugin for Fable 5 and Opus 5 that automatically packs the briefs sent out and the reports subagents send back as DensePack images.<br><br>The lead agent reads the same amount of text at half the tokens. | [hooks.json](https://github.com/Fabian-Galvez/DensePack/blob/main/plugin/hooks/hooks.json)   |
| [DensePack right-click tool](https://github.com/Fabian-Galvez/DensePack/tree/main/tools)<br><br>Windows only<br> | Install required                                                                                                                                                                | Packs any text file, or whatever you have selected, into a DensePack image via the right-click context menu and keyboard shortcuts.                                                                         | [densepack.py](https://github.com/Fabian-Galvez/DensePack/blob/main/tools/densepack.py)      |
| [xGator](https://github.com/Fabian-Galvez/xGator)                                                                | Download single EXE file<br>                                                                                                                                                    | Pulls the columns you choose out of Excel workbooks (.xlsx) and aggregates them into one master workbook.                                                                                                   | [aggregator.py](https://github.com/Fabian-Galvez/xGator/blob/main/aggregator.py)             |
| [DataPeel](https://github.com/Fabian-Galvez/DataPeel)                                                            | Download single EXE file                                                                                                                                                        | Wipes the metadata of every image in its folder with one click, and shows the data that can identify you in each image, before and after the wipe.                                                          | [metadata_wipe.py](https://github.com/Fabian-Galvez/DataPeel/blob/main/src/metadata_wipe.py) |
| [VtG](https://github.com/Fabian-Galvez/VtG)                                                                      | Download single EXE file<br>                                                                                                                                                    | Turns every screen recording in its folder into a gif. One tab per video, sliders for frames, quality and width, a live size estimate.<br>(The demo gifs in these repos were made with VtG)                 | [vid_to_gif.py](https://github.com/Fabian-Galvez/VtG/blob/main/src/vid_to_gif.py)            |

<br>

---

<br>

### Live guides and references

Walkthroughs, references and lab notes I documented while working presented as single-file apps that run in the browser as GitHub Pages. No install and no login required.

<sub>Download the index.html to run locally and offline.</sub>

| Repository                                                                            | Demo                                                                  | Description                                                                                                                                                               | Source                                                                                     |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [AZ-104 Reference](https://github.com/Fabian-Galvez/az104-reference)                      | [Try it](https://fabian-galvez.github.io/az104-reference/)<br>            | An interactive app that holds all 38 Azure services covered in the AZ-104 exam, including the commands administrators use.<br><br>Add, edit and search notes in the page. | [index.html](https://github.com/Fabian-Galvez/az104-reference/blob/main/index.html)            |
| [Old PC to Hypervisor](https://github.com/Fabian-Galvez/old-pc-to-hypervisor)             | [Try it](https://fabian-galvez.github.io/old-pc-to-hypervisor/)<br>       | A 7 step interactive walkthrough for installing a hypervisor on BIOS-only and on UEFI hardware.                                                                           | [index.html](https://github.com/Fabian-Galvez/old-pc-to-hypervisor/blob/main/index.html)       |
| [Build Your Own Walkthrough](https://github.com/Fabian-Galvez/build-your-own-walkthrough) | [Try it](https://fabian-galvez.github.io/build-your-own-walkthrough/)<br> | An 11 step interactive walkthrough that teaches how to build an interactive walkthrough app for your own project.                                                         | [index.html](https://github.com/Fabian-Galvez/build-your-own-walkthrough/blob/main/index.html) |


<br>

---

<br>

## [Home lab](https://github.com/Fabian-Galvez/homelab-docs)

The current lab, built, broken, fixed, and documented. 


| Documentation                                                                                                        | Description                                                                                                                                                              |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Active Directory lab](https://github.com/Fabian-Galvez/homelab-docs/blob/main/docs/active-directory-lab.md)             | Domain controller, <br>DNS, DHCP scope, OUs and groups, <br>bulk user creation with PowerShell, <br>home folders, roaming profiles, <br>domain-joined client.            |
| [Remote access and security](https://github.com/Fabian-Galvez/homelab-docs/blob/main/docs/remote-access-and-security.md) | Tailscale/WireGuard for remote access without opening inbound ports. RustDesk, Pi-hole DNS filtering, router hardening, guest network isolation, SSH key authentication. |
| [Hypervisor host](https://github.com/Fabian-Galvez/homelab-docs/blob/main/docs/hypervisor-host.md)                       | Bare-metal hypervisor on a BIOS-only 2011 desktop. Storage layout, containers against VMs, node upgrades.                                                                |
| [Media server](https://github.com/Fabian-Galvez/homelab-docs/blob/main/docs/media-server.md)                             | Jellyfin in a Debian LXC with a bind-mounted 1 TB drive, shared to Windows over Samba.                                                                                   |
| [Troubleshooting](https://github.com/Fabian-Galvez/homelab-docs/blob/main/docs/troubleshooting.md)                       | Hardware and software issues I ran into and resolved using the CompTIA A+ six-step troubleshooting method.                                                               |

<br>

---

<br>

## In production

Python application with a tkinter GUI, built to improve a QA team's workflow for consolidating CNC machined part measurements from specific columns in the workbooks they received.



| App repo                                     | Description                                                                                            | Runs on               | Source                                                                      |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------ | --------------------- | --------------------------------------------------------------------------- |
| [xGator](https://github.com/Fabian-Galvez/xGator) | Pulls the columns you choose out of Excel workbooks (.xlsx) and gathers them into one master workbook. | Windows, Linux, macOS | [aggregator.py](https://github.com/Fabian-Galvez/xGator/blob/main/aggregator.py) |

| Tickets                                                               | Workflow                                              |
| --------------------------------------------------------------------- | ----------------------------------------------------- |
| Runs daily in production with zero support tickets raised against it. | Work that took the QA team hours now takes 5 minutes. |

<br>

<sub>The version in this repo is much more versatile and works on any column.</sub>

<br>

---

<br>

## Certifications

| Credential                                 | Issuer              |
| ------------------------------------------ | ------------------- |
| CompTIA A+                                 | CompTIA             |
| Google IT Support Professional Certificate | Google, on Coursera |

<br>

---

<sub>[LinkedIn](https://www.linkedin.com/in/fabian-gz/)</sub>
