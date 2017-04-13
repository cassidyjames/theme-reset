# theme-reset
Quickly reset your GTK+ and Icon themes

Possibly an abuse of the `.desktop` spec. :wink:

1. Download [`com.github.cassidyjames.theme-reset.desktop`](https://github.com/cassidyjames/theme-reset/releases/download/1.0/com.github.cassidyjames.theme-reset.desktop),
2. Open your file manager app :file_folder: and go to Downloads, then
3. Click the **Reset Themes** icon.

Your system GTK+ and Icon themes should reset to the OS defaults.

# NOTE: No longer works on elementary OS Loki

Since executing arbitrary scripts from a `.desktop` file could be considered a pretty large security risk, elemnetary OS no longer allows it in the default file manager. So that stops this from working (but it's a decision I agree with!). It was fun while it lasted.
