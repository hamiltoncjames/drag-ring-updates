# Drag Ring

A Mac utility: press and hold on a file in Finder, press Shift, and a ring of
conversions and actions opens at the pointer.

## Install

**[Download Drag Ring](https://github.com/hamiltoncjames/drag-ring-updates/releases/latest/download/DragRing.dmg)**
(Apple Silicon Mac, macOS 14 or later)

1. Open the downloaded `DragRing.dmg` and drag Drag Ring into Applications.
2. Open Drag Ring. macOS says it can't check it: click Done.
3. Open System Settings ▸ Privacy & Security, click **Open Anyway** next to Drag Ring,
   then Open.
4. The welcome window walks you through the rest.

After that, Drag Ring updates itself (Settings ▸ Updates).

## About this repository

Releases only, not source code. Each release holds the signed `.dragringupdate`
package, `latest.json` for the app's update check, and `DragRing.dmg` for first
installs. The app installs an update only if it carries its author's Ed25519
signature.
