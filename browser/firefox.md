# Move cache to another directory 

`browser.cache.disk.parent_directory`  =>  `/path/to/dir` \
_Key needs to be created._

# Disable camera and microfon
`media.navigator.enabled`  =>  `false` \
`media.peerconnection.enabled`  =>  `false`

# Disable geo-location 

`geo.enabled`  =>  `false`

# Disable session restore

`browser.sessionstore.resume_from_crash` => `false`

# Disable telemetry data

* Goto [about:telemetry](about:telemetry)
* Make sure _FHR data upload_ and _Extended Telemetry recording_ is disabled.

# Prevent pastejacking

`dom.event.clipboardevents.enabled` => `false`

Ref:
* [golem](http://www.golem.de/news/pastejacking-im-browser-codeausfuehrung-per-copy-and-paste-1605-121062.html)

# Show always the complete url

`browser.urlbar.trimURLs` => `false`