<p align="center">
    <img src="https://github.com/genquiky/genURLblock/blob/main/items/logos.jpg" alt="logo" height="120" />
</p>


### URLhaus block list for Little Snitch

This document is an active database dump from [URLhaus](https://urlhaus.abuse.ch), which includes only online (active) malware URLs. The data is formatted for use with the Little Snitch application and contains one URL per line. This format is particularly useful if you want to utilise the dataset as an Indicator of Compromise (IOC). You can compare these URLs against specific log files from your security perimeter, such as web proxy logs. Additionally, this list can serve as a blocklist with a low false-positive rate.

The dumps are generated every 5 minutes from the source DB, but the formatted JSON file is generated daily.

* The filter is only compatible with [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) for Mac.
* Source Database [URLhaus](https://urlhaus.abuse.ch)
* Little Snitch [JSON RAW file](https://raw.githubusercontent.com/genquiky/genURLblock/refs/heads/main/new_format.json) for subscription.

----

### Subscription to Little Snitch

1. Open `Little Snitch Rules...` from the Little Snitch icon in the menu bar
2. In the sidebar, look for `Rule Groups` when hovering on this, a `+` button appears
3. Click the `+` button
4. Paste the URL from below:
```
https://raw.githubusercontent.com/genquiky/genURLblock/refs/heads/main/new_format.json
```
5. Press `Subscribe...`
6. Change `update` to daily
7. Check the `active` checkbox
8. Press `Subscribe`
---

<p align="center">
    <a href="https://github.com/genquiky/genURLblock/commits/main"><img src="https://img.shields.io/github/last-commit/genquiky/genURLblock" alt="last commit"></a>
    <a href="https://github.com/genquiky/genURLblock/commits/main"><img src="https://img.shields.io/github/commit-activity/m/genquiky/genURLblock" alt="commit activity"></a>
</p>
