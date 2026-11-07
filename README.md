# Home TV Launcher

A lightweight, remote-friendly TV home screen inspired by the clean layouts of
VIDAA launchers. It is a standalone web page with a live clock, Home/Apps/Inputs
views, app tiles, settings, and keyboard navigation.

## Run in a browser

Open `index.html` in a browser, or serve this directory locally:

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

Then visit `http://localhost:8000`. To load it on a TV, use the computer's
local-network IP instead of `localhost`.

Use the arrow keys or TV remote to move focus, Enter/OK to select, and
Escape/Back to close Settings or return from Apps and Inputs. The Home key
returns to this launcher's Home view. The clock format can be changed in
Settings.

## Use on a VIDAA TV

On VIDAA models that support the debug app installer, open `hisense://debug` in
the TV browser and install this page's network URL as an app/channel. This lets
you launch the page as a full-screen TV interface.

VIDAA does not provide a standard setting for replacing its system Home screen.
Installing this page does not intercept the TV's Home button or automatically
launch the page at startup; that requires a separate TV-control integration,
which is not included here. Likewise, app and input tiles currently show a
confirmation message rather than opening apps or switching TV inputs.