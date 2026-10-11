# Compatibility

## Validated configuration

- Windows x64
- Microsoft Edge WebView2 runtime
- SRT telemetry from supported DJI recordings
- Timestamped GPX tracks
- FIT activity telemetry
- MP4 video input
- Burned-in H.264 MP4 export
- Transparent ProRes 4444 MOV export validated in Adobe Premiere Pro and CapCut
- Software encoding and supported detected hardware encoders
- MapTiler maps with a user-supplied API key

## External requirements

- FFmpeg is required for video export. It must be available on PATH, through a compatible local installation recognized by the application, or in a supported tools location beside the application.
- Map imagery requires internet access and a valid user-supplied MapTiler API key. Gauge-only workflows remain local and do not require map access.
- HEVC preview depends on Windows media support. FFmpeg export may still work when Windows cannot preview a particular HEVC file.

## Deliberate limits

- The initial public target is Windows x64.
- Automatic updating is not currently enabled.
- Imported SVG artwork is sanitized and intentionally supports a restricted SVG feature set.
- Gauge packs and artwork are subject to size and structure limits documented by the application.
- Compatibility names identify supported data sources and do not imply affiliation or endorsement.
