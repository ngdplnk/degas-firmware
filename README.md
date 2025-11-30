# Degas Firmware Dump

This repository contains extracted Fastboot firmware files for the Xiaomi 14T codenamed **"degas"**.

## How to Find Your Firmware

All firmware files are available on the **[Releases](https://github.com/nicodotgit/degas-firmware/releases)** page of this repository.

Each release is tagged by its version and region code (e.g., `vOS2.0.205.0.VNEEUXM-eea`). You can download individual files directly from the "Assets" section of each release.

## Available Regions

This repository tracks firmware for the following regions:

| Region      | Code        |
|-------------|-------------|
| Global      | `global`    |
| Europe      | `eea`       |
| Russia      | `ru`        |
| Indonesia   | `id`        |
| Taiwan      | `tw`        |
| Turkey      | `tr`        |
| Global DC   | `global_dc` |

## About This Repository

This is an automated archive. A GitHub Actions workflow automatically downloads the official `.tgz` Fastboot ROM, extracts all of its contents, and uploads every individual file to a new release. This provides easy access to specific firmware files without needing to download the entire package.


**~Made with luv by Nico**
