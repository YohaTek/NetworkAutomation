# Network Automation

A small, work-in-progress collection of Python examples for automating
network device configuration. The goal is to show how repeatable scripts can
replace manual CLI work for a company network, improving efficiency and
reducing human error.

## Status

This repository is a starting point: it currently contains only this README.
Example scripts, device inventories and setup notes will be added as the
project develops.

## Layout

```
.
└── README.md   # this file
```

## Prerequisites

- Python 3.8 or newer
- Network devices (physical or virtual) reachable over SSH, with credentials
  for a lab or test environment
- Third-party libraries will be listed here, and in a `requirements.txt`, as
  the scripts that need them are added

## Running the examples

There are no runnable scripts yet. When they are added, this section will
document setup (for example creating a virtual environment and installing
dependencies) and the command to run each example.

> Run these scripts only against lab or test devices. Never store credentials
> in the repository: use environment variables or a local, untracked file
> such as `.env`, which is already covered by `.gitignore`.

## Repository conventions

- Keep credentials and device inventories for real networks out of version
  control.
- Commit generated output (logs, configuration backups) only when it is
  intentionally part of an example.
