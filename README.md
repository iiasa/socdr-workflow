# State of CDR - Data Portal Definitions

Copyright 2024 IIASA and SOCDR contributors

This work is licensed under <a href="http://creativecommons.org/licenses/by/4.0/" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0</a>
<a href="http://creativecommons.org/licenses/by/4.0/" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">
<img style="height:15px!important;margin-left:3px;vertical-align:text-bottom;" src=".static/cc.svg"><img style="height:15px!important;margin-left:3px;vertical-align:text-bottom;" src=".static/by.svg"></a>

[![License: CC-BY 4.0](https://img.shields.io/github/license/iiasa/ecemf-workflow)](https://github.com/iiasa/ecemf-workflow/blob/main/LICENSE)
[![Code style: ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

## Overview

This repository holds codelists (i.e., definitions) for variables and regions
used for the data portal of the "State of CDR" project (release 2024).

Visit https://portal.stateofcdr.org for more information.

> [!TIP]
> For *users not comfortable working with GitHub repositories and yaml files*,
> the definitions for this project are available for download as an xlsx spreadsheet
> at https://files.ece.iiasa.ac.at/socdr/project-template.xlsx.

## Codelists and definitions

The folder `definitions` contains the "codelists", i.e., list of allowed variables and
regions, for use in the validation workflow. In the IAMC community, the word
"variable template" is also used to refer to the codelists for variables.

## Dependencies

The project uses the Python package [nomenclature-iamc](https://nomenclature-iamc.readthedocs.io)
for management of codelists and validation of scenario data.
Read more about the [IAMC data format](https://docs.ece.iiasa.ac.at/iamc.html).