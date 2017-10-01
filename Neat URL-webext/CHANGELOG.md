2.1.2
=====
* Fix problem with URL decoding
* Keys are now case sensitive

2.1.1
=====
* Do not update a tab to an empty URL

2.1.0
=====
* Fix handling of addons.mozilla.org and mozilla.org again
* On Amazon product pages, all parameters are removed
* Add light icons for dark themes, can be set in the options

2.0.5
=====
* Fix handling of mozilla.org

2.0.4
=====
* Fix problem related to Google Docs - see https://addons.mozilla.org/nl/firefox/addon/neat-url/reviews/918997/
* Add _hsenc and mkt_tok to Neat URL defaults

2.0.3
=====
* Important bugfix preventing some users from getting upgraded parameters

2.0.2
=====
* Add utm_cid for mashable.com

2.0.1
=====
* Introduce $$ to force remove everything after a certain string
* Change $ behaviour to remove everything after a certain string only if there are no query parameters after reducing the query parameters (no longer breaks Amazon links)
* Drop utils/compareVersions.js (no longer needed)

2.0.0
=====
* Added domain wildcards
* Added support for anchor tags
* Made upgrading of parameters between versions more robust
* Fixed context menu listeners staying attached after removing them
* Add gs_l parameter retroactively
* Add new default parameters: pd_rd_r@amazon.*, pd_rd_w@amazon.*, pd_rd_wg@amazon.*, _encoding@amazon.*, psc@amazon.*, ved@google.*, ei@google.*, sei@google.*, gws_rd@google.*, cvid@bing.com, form@bing.com, sk@bing.com, sp@bing.com, sc@bing.com, qs@bing.com, pq@bing.com, feature@youtube.com, gclid@youtube.com, kw@youtube.com, $/ref@amazon.*
* Expanded README

1.2.0
=====
- Fix options.js resizing of textarea width under certain conditions
- Add parameter gs_l and provide an automatic upgrade path for users using earlier versions

1.1.0
=====
- Support for addons.mozilla.org - try https://addons.mozilla.org/firefox/addon/google-pdf-viewer/?src=search after adding src@addons.mozilla.org to parameters in the options page
- Fix support for google.co.uk (double domains)
- Introduce support for root domains with subdomains. This means you can use wildcards at the beginning of a parameter (*.mozilla.org)

1.0.1
=====
- Added utm_userid as default parameter

1.0.0
=====
- Fork of Lean URL, with features from Pure URL
- Added ability to set your own URL parameters on the options page (to reach feature parity with Pure URL)
- Fixed version of Lean URL, works with recent Firefox versions
- Added a nice animation in the toolbar (can be changed or disabled)
- Added domain-specific blocked parameters (to reach feature parity with Pure URL)
