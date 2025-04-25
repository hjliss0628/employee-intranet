# Employee Intranet Installer

This repository serves as the update and distribution hub for the **Employee Intranet** application.

## Overview

This repo contains:

- A `version.txt` file used by the application to check for updates.
- The latest `.exe` installer available on the [Releases](https://github.com/hjliss0628/employee-intranet/releases) page.

The main application checks this repository during startup to verify if a newer version is available.

If Windows Defender prompts you while installing the application, click More Info and Run anyway.

## Usage

After opening the program, you will be prompted with multiple button choices.

### Run Automation

Begins the automatic state and firm calendar search. It will prompt you to sign into Clio and you can sign-in or close the window.

### Edit Run Link

Edits the configuration for the spreadsheet with all current cases.

### Set Max Instances

Edits the configuration for the maximum number of searches to be performed at once; 5-10 is optimal.

### Select Browser

Edits the configuration to specify a different browser other than your default system browser.

### Define Ignore List

Edits the configuration to add lists of counties to ignore in the District and County courts. By default, the counties not included on the Multi Court Calendar are added to the District ignore list, but more counties can be added to either list.
