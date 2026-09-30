<p align="left">
  <img src="./assets/Fabian-Galvez-README.svg" alt="Hi, I'm Fabian" />
</p>

<br>

> I build tools that help improve workflows,
> and I keep the computers, networks and servers those tools run on working.

<br>

---

<br>

## DensePack

DensePack turns text into images that cost about 50% fewer input tokens than the text.

The plugin saves on whole Claude Code sessions, not only on input tokens. In Anthropic's `claude plugin eval` on Opus 5.5, it cut the price of three coding tasks by 31.8% to 38.3% on average.

| Repository                                                                                                       | Run                                                                                                                                                                                 | Description                                                                                                                                                                                                              | Source                                                                                     |
| ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| [DensePack plugin](https://github.com/Fabian-Galvez/DensePack)                                                   | Run these two commands in Claude Code.<br><br>`/plugin marketplace add Fabian-Galvez/DensePack`<br><br>`/plugin install densepack@densepack-marketplace`                       | Packs the files your agent reads, long command output, the briefs it sends and the reports subagents send back into DensePack images. Fable, Opus and Sonnet agents read them at about half the tokens of the text.                                   | [hooks.json](https://github.com/Fabian-Galvez/DensePack/blob/main/plugin/hooks/hooks.json) |
| [DensePack right-click tool](https://github.com/Fabian-Galvez/DensePack/tree/main/tools)<br><br>Windows, Linux and macOS<br> | Needs an install                                                                                                                                                                    | Packs selected files into DensePack images from the right-click menu. On Windows, it also packs selected text with keyboard shortcuts.                                                                                  | [densepack.py](https://github.com/Fabian-Galvez/DensePack/blob/main/tools/densepack.py)    |
| [DensePack HTML app](https://github.com/Fabian-Galvez/DensePack)<br>                                             | [Try it](https://fabian-galvez.github.io/DensePack/)<br>                                                                                                                            | Turns pasted text into the smallest image an AI model can still read. <br><br>Sending a condensed image of text instead of the raw text uses about 50% fewer input tokens. | [index.html](https://github.com/Fabian-Galvez/DensePack/blob/main/index.html)              |

<br>

---

<br>

## Xanini

Xanini makes custom .svg banners, icons and animations that are yours to keep. You upload them to your own repository, and they keep rendering because they do not depend on an outside server.

| Repository                                        | Run                                                   | Description                                                                                                                                            | Source                                                                     |
| ------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| [Xanini](https://github.com/Fabian-Galvez/Xanini) | [Try it](https://fabian-galvez.github.io/Xanini/)<br> | SVG studio that makes .svg icons, banners and animations that render on GitHub, all from your browser. <br><br>The files you create are yours to keep. | [index.html](https://github.com/Fabian-Galvez/Xanini/blob/main/index.html) |

> [!NOTE]
> <strong>This is a personal project. It is still in development and far from perfect or finished.</strong> <br>
>
> That being said, <strong>it works</strong>, and it made every .svg file and animation in these repositories, including the banner at the top of this README.

<sub>Download the index.html to run locally and offline.</sub>

<br>

---

<br>

## DataPeel

| Repository                                            | Description                                                                                                                                        | No install               | Source                                                                                       |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | -------------------------------------------------------------------------------------------- |
| [DataPeel](https://github.com/Fabian-Galvez/DataPeel) | Shows the hidden data in every picture in its folder, marks in red the parts that can identify you, and wipes all of it in one click. | Windows EXE file<br>Linux and macOS run from source | [metadata_wipe.py](https://github.com/Fabian-Galvez/DataPeel/blob/main/src/metadata_wipe.py) |

<br>

---

<br>

## VtG

| Repository                                  | Description                                                                                                                                                                                 | No install                   | Source                                                                            |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | --------------------------------------------------------------------------------- |
| [VtG](https://github.com/Fabian-Galvez/VtG) | Turns every screen recording in its folder into a gif. Each video gets its own tab with sliders for frames, quality and width, and a live estimate of the file size.<br>VtG made the demo gifs in these repos. | Windows EXE file<br>Linux and macOS run from source | [vid_to_gif.py](https://github.com/Fabian-Galvez/VtG/blob/main/src/vid_to_gif.py) |

<br>

---

<br>

## xGator

xGator is the first Python app I built to fix a real workflow problem. An aerospace parts manufacturer's QA team uses it to combine CNC part measurements from many Excel workbooks into one. A task that took the team hours now takes 5 minutes.

It has run daily in production since September 2025 with zero support tickets.

| Repository                                          | Description                                                                                            | Source                                                                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| [xGator](https://github.com/Fabian-Galvez/xGator) | Pulls the columns you choose out of Excel workbooks (.xlsx) and gathers them into one master workbook. | [aggregator.py](https://github.com/Fabian-Galvez/xGator/blob/main/aggregator.py) |

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

<br>

<sub>[LinkedIn](https://www.linkedin.com/in/fabian-gz/)</sub>
