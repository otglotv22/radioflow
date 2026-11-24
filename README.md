# RadioFlow

![RadioFlow](docs/RadioFull%20-%20Full%20App%20Logo.png)

**Internet radio from your Mac keyboard.** RadioFlow is an Alfred workflow for discovering, saving, and playing internet radio stations without opening a separate radio app.

The workflow runs in [Alfred](https://www.alfredapp.com/) and uses [mpv](https://mpv.io/) to play live streams.

## What it does

- Find radio stations by name and browse stations available near you.
- Save stations to favourites and organize how they appear.
- Play and stop live radio from Alfred.
- See track details when a station provides them, then search music services for the track.
- Rename stations and use custom station logos.
- Back up and restore your stations, logos, favourites, and settings.

## Requirements

- A Mac running macOS.
- [Alfred](https://www.alfredapp.com/) with a [Powerpack licence](https://www.alfredapp.com/powerpack/) to use workflows.
- [mpv](https://mpv.io/), the media player RadioFlow uses for live streams.

To install mpv with [Homebrew](https://brew.sh/), open Terminal and run:

```sh
brew install mpv
```

## Install RadioFlow

1. Download [`RadioFlow.alfredworkflow`](public/downloads/RadioFlow.alfredworkflow) from this repository.
2. Open the downloaded file and confirm the import in Alfred.
3. Open Alfred, type `rd`, and choose a station.

If Alfred does not recognize the `rd` keyword, check that the workflow appears in Alfred Preferences and that your Powerpack licence is active.

## Use RadioFlow

| Type in Alfred | What it does |
| --- | --- |
| `rd` | Open RadioFlow and browse or search your favourite stations. |
| `rd all` | Discover stations available near your location. Location is inferred from your internet connection. |
| `rd saved` | Browse every station saved in RadioFlow. |
| `rd track` | View the current track and search for it on your chosen music services. |

Choose a station to open its options. Use the play action to start it; the main `rd` view then shows the station currently playing. Use the stop action to stop the live stream.

### Station discovery and favourites

Browse nearby stations with `rd all`, or type a station name after `rd` to search. Add a station to favourites from its options to keep it in your main list. Use `rd saved` to browse your complete saved-station list.

### Track information

RadioFlow displays track information when a station includes it in its stream metadata. Some stations do not send track details, so information may be unavailable. In Settings, choose which track-search services appear and change their order.

### Back up or restore your data

Open **Settings** from the main `rd` menu. Choose **Back up RadioFlow** to export your stations, station logos, favourites, and preferences. Choose **Import a backup** to restore an exported `.radioflowbackup` file. The backup is a RadioFlow data file; it is not a ZIP archive.

## Version history

### 0.2.0 — Current

- Discover stations near you and search for stations online.
- Rename stations, set custom logos, and manage favourites.
- View track information and search music services.
- Configure favourite-list and track-search preferences.
- Back up and restore RadioFlow data.

## Website and help

<!-- Add the published RadioFlow website URL here when it is ready. -->

<!-- Add the published Help & Guides URL here when it is ready. -->

