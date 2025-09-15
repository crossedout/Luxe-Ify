# Luxe-ify

A Chrome extension that enhances Current-RMS with color highlighting and streamlined task management.

## Features

- **Streamlined Task Format**: Use `@mentions` with natural text for task assignments
- **Smart Highlighting**: Automatic color coding based on progress and task type
- **Sidebar Controls**: Collapsible sidebar and activities sections
- **Question & Alert Detection**: Special highlighting for questions (?) and alerts (!)

## Task Format Examples

**Simple assignment**: `@John Smith Review contracts`
**With due date**: `@Sarah Johnson 9/20/2025 Call client`  
**With date range**: `@Mike Chen 9/14/2025-9/21/2025 Setup equipment`
**With progress**: `@Lisa Park 75% Final lighting touches`
**Complete example**: `@Brad Huntsman 9/14/2025-9/20/2025 66% Finalize vendor contracts`

## Color Coding

- **100% complete** → Pale green
- **1-99% progress** → Pale yellow  
- **0% or no progress** → Light red
- **No progress specified** → Medium orange
- **Questions (?)** → Light blue
- **Alerts (!)** → Bright red with yellow text

## Privacy

Luxe-ify stores all data locally on your device and does not transmit any information to external servers. See our [Privacy Policy](privacy-policy.html) for complete details.

## Installation

1. Download the extension files
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension folder

## Permissions

- **storage**: Save your preferences locally
- **activeTab**: Interact with Current-RMS tabs
- **host permission**: Run only on *.current-rms.com sites

## Support

For issues or feature requests, please contact [your email] or visit [your GitHub repository].