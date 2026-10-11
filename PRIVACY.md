# Privacy

TTG MotionGauge is local-first. It does not require a TechTimeGuy Designs account and does not send videos, telemetry, artwork, layouts, API keys, or usage analytics to a TechTimeGuy Designs service.

## Data stored on the PC

- Application preferences, layouts, imported custom gauge artwork, optional logo artwork, export settings, and the optional MapTiler API key are stored in the current Windows account's local application data.
- Selected video and telemetry files remain at their original locations unless the user deliberately exports a new video, overlay, layout, or gauge pack.
- Normal uninstall retains local application data so settings are available after reinstall.

The MapTiler API key is stored locally for convenience. Anyone with access to the Windows account or its application-data files may be able to retrieve it. Use a key with appropriate MapTiler limits and restrictions.

## Network use

Video, telemetry, gauge rendering, and encoding are performed locally. When the optional map is enabled, TTG MotionGauge requests map tiles directly from MapTiler. Those requests necessarily disclose the requested tile coordinates, IP address, and API key to MapTiler and are governed by MapTiler's terms and privacy practices.

TTG MotionGauge currently has no analytics, advertising, account service, cloud upload, or automatic updater. Future network features will be documented before public release.

## Removal

Normal uninstall removes the installed application and shortcuts but retains settings. Users can delete the application's local WebView2/application-data directory separately when they want to remove retained preferences and the stored MapTiler key.
