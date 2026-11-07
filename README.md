# Home TV Launcher

A lightweight, remote-friendly TV home screen inspired by the clean layouts of
VIDAA launchers. It is a standalone web page with a live clock, Home/Apps/Inputs
views, app tiles, settings, and keyboard navigation.

## Run

Open `index.html` in a browser, or serve this directory locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

Use the arrow keys to move focus, Enter to select, and Escape or Backspace to
close settings. The clock format can be changed in Settings.

This is a front-end demo: selecting an app displays a confirmation toast rather
than launching an app, and the page does not connect to VIDAA TV APIs or control
TV hardware.