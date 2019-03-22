# google-analytics-nginx-reverse-proxy
nginx reverse proxy for google analytics to evading various blocker

Note:
Prevent GA making requests to DoubleClick(that's to say sometimes GA will return 302 sometimes to making request to stats.g.doubleclick.net to get more info for advertising which will trigger the blocker),you need to disable Google Signals.Go to GA -> Admin -> Tracking info -> Data Collection -> disable both toggles and click on save. It can take up to 24 hours for the changes to take effect.