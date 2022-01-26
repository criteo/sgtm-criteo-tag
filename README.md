# Server-side Google Tag Manager Criteo Tag

This Tag sends the web events for which it is triggered on the Google server-container, directly to Criteo servers.
No formatting is done on the events, as everything is done on Criteo Side, it simply forwards the events it receives, while adding some fields.

# Installation

> :warning: **If you want User Identification to work optimally**: please also install [Criteo User Identification](https://github.com/criteo/gtm-criteo-useridentification/) on your Google Tag Manager web-container!

Please get in touch with your Criteo Account Strategist to fill the following parameters: 

* applicationId (which is used to identify and properly format your event in Criteo format on our end, recommended format for this field is **com.advertiserName.sgtm**
* partnerId
* callerId (which is used for User Identification)