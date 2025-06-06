# Employee Intranet Installer

This repository serves as the update and distribution hub for the Employee Intranet application.

## Overview

This repo contains:

- A `version.txt` file used by the application to check for updates.
- The latest `.exe` installer available on the [Releases](https://github.com/hjliss0628/employee-intranet/releases) page.

The main application checks this repository during startup to verify if a newer version is available.

If Windows Defender prompts you while installing the application, click More Info and Run anyway.

## Usage

After opening the program, you will be prompted with multiple button choices. I recommend running through the configuration options before running the automation.

### Run Automation

Begins the automatic state and firm calendar search. It will prompt you to sign into Clio and you can sign-in, or alternatively close the window.
When the automation is finished running, it will prompt you to save an excel file containing the raw results, matches, and flags.

### Edit Run Link

Edits the configuration for the spreadsheet with all current cases. It will default to the correct link.

### Set Max Instances

Edits the configuration for the maximum number of searches to be performed at once; 5-10 will be the fastest, but if you are having issues try a lower number (must be 1 or higher).

### Select Browser

Edits the configuration to specify a different browser other than your default system browser.

### Enter Debugging

Resets your configuration to default; opens a console and displays what is happening in the program.

### Define Ignore List

Edits the configuration to add lists of counties to ignore in the District and County courts. By default, the counties not included on the Multi Court Calendar are added to the District ignore list, but more counties can be added to either list.
