# Claude Cowork Plugin for Tin Man Server

A plugin that connects [Tin Man Server](https://calibratedsoftware.com) to Claude Cowork, giving Claude direct access to professional media tools for film and video production workflows.

Available for macOS and Windows.

## Requirements

- [Tin Man Server](https://calibratedsoftware.com) installed and licensed
- [Claude Cowork](https://claude.ai) desktop app

## Installation

1. Download the `.zip` for your platform from [Releases](../../releases/latest).
2. Add the plugin to Claude Cowork.

## Tools

**tinman-server:scan** — Quick scan of a folder or drive. Returns filename, size, codec, resolution, frame rate, duration, and timecode for every clip.

**tinman-server:query_metadata** — Full metadata extraction. Camera make/model, serial number, firmware, ISO, white balance, tint, shutter angle, lens model, lens serial, aperture, color space, timecode, slate info, and more.

**tinman-server:generate_report** — Generate formatted clip reports with thumbnails. Supports PDF, HTML, JSON, CSV, and XLSX. Configurable dark mode, Rec 709 tonemapping, custom fields, and thumbnail count.

**tinman-server:thumbnail** — Generate JPEG thumbnails from media files. Configurable size, quality, number per clip, and Rec 709 tonemapping.

**tinman-server:export** — Transcode/convert media using 57 professional presets. ProRes, DNxHD, DNxHR, H.264, H.265, and more. Custom file naming with tokens.

**tinman-server:copy** — SHA256 verified file copy. Every file checksummed after copy to guarantee integrity.

**tinman-server:cancel** — Gracefully stop a running export or copy.

**tinman-server:generate_config** — Returns the default report configuration template as JSON for customizing reports.

**tinman-server:list_export_presets** — Lists all 57 available transcode presets.

## Knowledge

The plugin also includes built-in knowledge that helps Claude understand professional media workflows:

**tinman-server:camera-formats** — Camera brands, RAW formats, codecs, colorspaces, log curves, and LUTs.

**tinman-server:video-workflows** — DIT workflows, on-set data management, dailies, color management, and editorial handoff.

**tinman-server:tinman-server-tools** — Best practices for using the Tin Man tools effectively.

## Links

- [Tin Man Server](https://www.calibratedsoftware.com/tin-man-server/)
- [Calibrated Software](https://www.calibratedsoftware.com)
