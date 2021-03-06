# Linux-SDM-Downloader 1.3.0
Downloader SDM files via SDX file (DreamSpark) on Linux (primary)

## What is it?
Linux-SDM-Downloader is Python script for download SDM files and joining to one file. For downloading these files is needed SDX file. SDM file is possible unpacking via [xSDM](https://github.com/v3l0c1r4pt0r/xSDM).

## Prerequisites
- Lxml

### Installing dependencies on Linux (debian):
```
# aptitude install python-lxml
```
or
```
# apt-get install python-lxml
```

## How to use
Download actual source code (unpacking) and run:
```
git clone https://github.com/RadekSimkanic/Linux-SDM-Downloader.git
cd Linux-SDM-Downloader
python main.py <SDX file>
```

Next step after successful process for unpacking SDM package is unpacking via [xSDM](https://github.com/v3l0c1r4pt0r/xSDM).

## News
2016-11-19
- Version 1.3.0
- Added pretty exit error in case of the file is not found.
- Added function to create and/or enter dedicated download directory in the same directory as the source .sdx file.
- Added support for Windows.
- Added support Python 3.

2016-07-28:
- Version 1.2.0
- Added functionality that checks for free space on disk.
- Fix bug - selecting file in groups.

2016-06-22:
- Version 1.1.0
- Eliminating the use of beautifulsoup. Prerequisities only Lxml.
- New error information about expiry to download file.

2015-10-28:
- Version 1.0.0
- Enable downloading also ISO files (and maybe others files) via .SDX.
- List of tested OS and status whether works ok or not.

2015-01-29:
- Created first beta version.

## Tested

Version 1.3.0:
- **Windows 10 x64** | Python 3.5.2: **OK** (Niklas Rosenstein)

Version 1.\*.\*:
- **Linux Ubuntu 15.10 wily** | Python 2.7.10: **OK** (Bent Haase)
- **Linux Mint 17.1 Rebecca** | Python 2.7.6: **OK** (Radek Simkanič)
- **Linux Debian Wheezy** | Python 2.7.3: **OK** (Dominik Chrastecký)
- **Windows 10** | cygwin | Python 2.7.8: **OK** (Dominik Chrastecký)
- **Linux Debian 8 Jessie (32 bit)** | Python 2.7.9: **OK** (Zbyněk Fišer - Nialaren)
- **OS X 10.11.1 (15B42)** | Python 2.7.10: **OK** (Michal Jamroz)
- **Arch (4.2.5-1)** | Python 2.7.10: **OK**
- **Linux Fedora 24** | Python 2.7.11: **OK** (Michael Chavrimootoo)

Please tell me whether you work Linux-SDM-Downloader on your distribution.
