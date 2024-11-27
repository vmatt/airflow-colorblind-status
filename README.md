# Airflow Task Instance Status Enhancer
This userscript enhances the visual representation of task instance statuses in Apache Airflow by replacing color-based status indicators with clear symbols. It's particularly helpful for colorblind users or anyone who prefers symbolic representation over color-coding.

## Features
- Replaces color-coded status indicators with intuitive symbols
- Works with dynamic content updates
- Compatible with Shadow DOM elements
- Maintains state consistency across page navigation

## Status Symbol Mappings
- ⌛ Queued
- ⚙️ Running
- ✓ Success
- 🔄 Restarting
- ❌ Failed
- 🔁 Up for retry
- ⏳ Reschedule
- ⚠️ Upstream failed
- ⤵️ Skipped
- 🗑️ Removed
- ⏰ Scheduled
- ⏸️ Deferred

## Installation
1. Install a userscript manager (like Tampermonkey or Greasemonkey)
2. Click the installation button on this page
3. Confirm the installation in your userscript manager

## Compatibility
- Works with most modern browsers
- Tested with Apache Airflow 2.x
- Compatible with URLs containing 'dags' or 'airflow' in the path

## Known Issues
- May need a page refresh on initial load if symbols don't appear immediately
- Some custom Airflow deployments might require URL pattern adjustments

## Version History
- 0.5: Started git versioning
- 0.4: Added class transition tracking and improved Shadow DOM support
- 0.3: Enhanced performance with throttled updates
- 0.2: Added support for dynamic content
- 0.1: Initial release

## Support
For issues or feature requests, please create an issue on the repository.

## Author
Mate Valko - [namilink.com](https://namilink.com)

## License
This script is provided as-is under MIT open license. Feel free to modify and share!
