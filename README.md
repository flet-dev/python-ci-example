[![Build status](https://ci.appveyor.com/api/projects/status/lkhmhb99rssv2mud/branch/main?svg=true)](https://ci.appveyor.com/project/flet-dev/python-ci-example/branch/main)

# AppVeyor CI pipeline to build Flet app desktop package

This repository contains a sample "Counter" Python app using Flet framework and CI configuration to package Flet app into standalone desktop bundle with PyInstaller for Windows, macOS and Linux.

Main features:

* Build packages for Windows, macOS and Ubuntu on every commit and upload them into build "Artifacts".
* Uses Python 3.10 on all thress platforms.
* Uploads packages to GitHub repository [releases](https://github.com/flet-dev/python-ci-example/releases) when a new tag is pushed.

To get started with AppVeyor you can just fork this repository and replace `main.py`, `requirements.txt` and `icon.png` with your own.
