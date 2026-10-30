# within-uptime

Checks https://app.withinline.com/up every 5 minutes from GitHub's runners, outside the
servers it watches. Three failed tries 20 s apart open an issue labelled `down` (assigned, so
GitHub notifies by email and the mobile app); the next good check closes it.
