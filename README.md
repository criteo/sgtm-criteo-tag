# Server-side Google Tag Manager Criteo Tag

The purpose of this Tag is to forward the web events directly to Criteo servers when triggered from the Google Tag Manager server-container, directly to Criteo servers.
Please note that no formatting is done on the events, it simply forwards the events it receives, while adding some fields.

# Installation

> :warning: **If you want User Identification to work optimally**: please also install [Criteo User Identification](https://github.com/criteo/gtm-criteo-useridentification/) on your Google Tag Manager web-container!

Please get in touch with your Criteo contact to fill the following parameters: 

* **applicationId** (which is used to identify and properly format your event in Criteo format on our end, recommended format for this field is ***com.advertiserName.sgtm***)
* **partnerId**
* **callerId** (which is used for User Identification)
