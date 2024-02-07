# Homepage

[![Button](https://raw.githubusercontent.com/OZI-Project/.github/main/github-metrics-ozi-project.svg)](https://github.com/OZI-Project)

## OZI &mdash; Python Project Packaging for Meson

A set of free (and open source) tools to make Python package publishing easier. This project is under active development but *unstable*. OZI is expected to be in Alpha release status by <s>January 2024</s> Q1 2024.

![Button](https://img.shields.io/pypi/status/ozi?style=for-the-badge&logo=pypi) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/OZI?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-Apache--2.0_with_LLVM_exceptions-282661?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMTIyLjg4IDEwMi43MiIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMTIyLjg4IDEwMi43MiIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI%2BPHN0eWxlIHR5cGU9InRleHQvY3NzIj4uc3Qwe2ZpbGwtcnVsZTpldmVub2RkO2NsaXAtcnVsZTpldmVub2RkO308L3N0eWxlPjxnPjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik02NS42MSwyMC45MXY3Mi43NGgzNS42M2MwLjM4LDAsMC42OCwwLjMxLDAuNjgsMC42OXY3LjdjMCwwLjM4LTAuMzEsMC42OS0wLjY4LDAuNjlIMjIuODQgYy0wLjM4LDAtMC42OS0wLjMxLTAuNjktMC42OXYtNy43YzAtMC4zOCwwLjMxLTAuNjksMC42OS0wLjY5aDM1LjYzbDAtNzIuNzFjLTMuMS0xLjA4LTUuNTYtMy41My02LjY0LTYuNjNIMjkuM3YzLjQzIGMwLDAuMzgtMC4zMSwwLjY4LTAuNjgsMC42OGgtNS43OGMtMC4zOCwwLTAuNjktMC4zMS0wLjY5LTAuNjh2LTMuNDNoLTUuNzNjLTAuNDQsMC0wLjgtMC4zMS0wLjgtMC42OFY3Ljg0IGMwLTAuMzgsMC4zNi0wLjY5LDAuOC0wLjY5aDM1LjQzQzUzLjMzLDIuOTksNTcuMzEsMCw2MS45OSwwYzQuNjgsMCw4LjY2LDIuOTksMTAuMTQsNy4xNmgzNS41M2MwLjQ0LDAsMC44LDAuMzEsMC44LDAuNjl2NS43OCBjMCwwLjM4LTAuMzYsMC42OC0wLjgsMC42OGgtNi40NnYzLjQzYzAsMC4zOC0wLjMxLDAuNjgtMC42OCwwLjY4aC01Ljc4Yy0wLjM4LDAtMC42OS0wLjMxLTAuNjktMC42OHYtMy40M0g3Mi4xNiBDNzEuMDksMTcuMzgsNjguNjcsMTkuODEsNjUuNjEsMjAuOTFMNjUuNjEsMjAuOTF6IE05OS42NiwyMi4zbDIyLjkxLDQwLjQ4YzAuMiwwLjM1LDAuMjksMC43MywwLjI4LDEuMWgwLjAyYzAsMC4wNSwwLDAuMSwwLDAuMTUgYzAsOS42NC0xMS4zNSwxNy40Ni0yNS4zNSwxNy40NmMtMTMuODUsMC0yNS4xLTcuNjUtMjUuMzQtMTcuMTVjLTAuMDQtMC4xNi0wLjA2LTAuMzQtMC4wNi0wLjUxYzAtMC40NCwwLjE0LTAuODYsMC4zNy0xLjIgbDIzLjQzLTQwLjQzYzAuNTktMS4wMiwxLjg5LTEuMzcsMi45MS0wLjc4Qzk5LjIsMjEuNjUsOTkuNDgsMjEuOTUsOTkuNjYsMjIuM0w5OS42NiwyMi4zeiBNOTkuNzUsMzEuMTF2MzAuNmgxNy4zMkw5OS43NSwzMS4xMSBMOTkuNzUsMzEuMTF6IE05NS42Nyw2MS43VjMxLjE2TDc3Ljk2LDYxLjdIOTUuNjdMOTUuNjcsNjEuN3ogTTI3LjU0LDIyLjNsMjIuOTEsNDAuNDhjMC4yLDAuMzUsMC4yOSwwLjczLDAuMjgsMS4xaDAuMDIgYzAsMC4wNSwwLDAuMSwwLDAuMTVjMCw5LjY0LTExLjM1LDE3LjQ2LTI1LjM1LDE3LjQ2Yy0xMy44NSwwLTI1LjEtNy42NS0yNS4zNC0xNy4xNUMwLjAyLDY0LjE5LDAsNjQuMDIsMCw2My44NCBjMC0wLjQ0LDAuMTQtMC44NiwwLjM3LTEuMkwyMy44LDIyLjIxYzAuNTktMS4wMiwxLjg5LTEuMzcsMi45MS0wLjc4QzI3LjA4LDIxLjY1LDI3LjM2LDIxLjk1LDI3LjU0LDIyLjNMMjcuNTQsMjIuM3ogTTI3LjYzLDMxLjExdjMwLjZoMTcuMzJMMjcuNjMsMzEuMTFMMjcuNjMsMzEuMTF6IE0yMy41NCw2MS43VjMxLjE2TDUuODQsNjEuN0gyMy41NEwyMy41NCw2MS43eiBNNjEuOTksNi4wNyBjMi41OSwwLDQuNjksMi4xLDQuNjksNC42OWMwLDIuNTktMi4xLDQuNjktNC42OSw0LjY5Yy0yLjU5LDAtNC42OS0yLjEtNC42OS00LjY5QzU3LjMsOC4xNyw1OS40LDYuMDcsNjEuOTksNi4wN0w2MS45OSw2LjA3eiIvPjwvZz48L3N2Zz4%3D)


<small>
  &dagger; <a href="https://mesonbuild.com/">Meson</a> is a registered trademark of 
  Jussi Pakkanen. The OZI project is not affiliated with or endorsed by the Meson 
  development team or Jussi Pakkanen.
</small>

<small>
  Read the Docs logos and other trademarks are used under the terms of the <a href="https://creativecommons.org/licenses/by/4.0/">CC-BY 4.0</a>
  license. The GitHub&#174; Octocat&#174; logo and other trademarks are used under the terms of a <a href="https://github.com/logos">license</a>.
  The OZI Project is not affiliated with or endorsed by GitHub, Inc. The Python logo, Python Package Index logo, and other trademarks are used under the terms of a <a href="https://www.python.org/psf/trademarks/">license</a>, the OZI Project is not affiliated with or endorsed by the Python Software Foundation.
</small>
