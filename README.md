# Ibrahim's Audio Maker

**Made on Earth by Ibi**

A responsive black-and-gold frontend for an AI video-to-audio studio.

## Included
- Responsive studio interface with black and gold visual identity.
- High-contrast gold favicon for visibility on dark browser chrome.
- Video file picker and drag-and-drop selection.
- Audio prompt and negative prompt fields.
- MMAudio model selector, inference steps and guidance settings.

## Current limitations
The GPU inference API, subscription authentication, job queue, progress updates and secure download delivery are **not connected yet**. The Generate button deliberately does not upload files or pretend to generate audio until a secured backend is deployed.

## Enable GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Select **Deploy from a branch**.
3. Choose **main** and **/ (root)**, then Save.
4. Wait for GitHub Pages to publish the site.

## Backend security
Connect the frontend to a private job API. Never place Kaggle credentials or API secrets in browser JavaScript. Before using Kaggle for unattended customer-facing processing, verify that the workflow is permitted by Kaggle's current terms and supported access methods. The API should authenticate subscribers, validate uploads, queue jobs, report progress and provide MP4/FLAC downloads.
