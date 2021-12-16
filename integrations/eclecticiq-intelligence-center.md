---
description: >-
  Ingest threat intelligence from Obstracts into the EclecticIQ Intelligence
  Center.
---

# EclecticIQ Intelligence Center

### Prerequisites

[An Obstracts plan that supports use of our API.](https://www.obstracts.com/pricing/)

### Setup <a href="#setup" id="setup"></a>

![EclecticIQ incoming feed setup](../.gitbook/assets/obstracts-eiq.png)



1. Navigate to the incoming feed setup page
2. Select add new feed
3. You can set most fields as you wish, the key ones are
   1. **Transport type:** TAXII 2.1 poll
   2. **Content type:** STIX 2.1
   3. **API Root URL:** https://app.obstracts.com/taxii/taxii2/YOUR-GROUP-UUID _(_YOUR-GROUP-UUID[ ](https://app.stixify.com/user/manage\_group)[can be btained on the Group Management page in the Obstracts web app](https://app.obstracts.com/user/manage\_group)_)_
   4. **Collection ID:** FEED-UUID (FEED-UUID [can be obtained from the Feed List page in the Obstracts web app](https://app.obstracts.com/feed/list/))
   5. **Username:** Obstracts username
   6. **Password:** Obstracts API key
   7. **Added after:** _should be no more than 7 days_ because our TAXII feed does not return any more data than this
   8. **Objects per run (max):** 50
   9. **Download time frame:** advancing

Now click save, and you should see intelligence being ingested.&#x20;

### Usage

Once incoming feed is enabled, the ingested threat intelligence can be used in the EclecticIQ Intelligence Center.
