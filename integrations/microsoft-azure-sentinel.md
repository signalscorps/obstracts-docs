---
description: >-
  Ingest threat intelligence from Obstracts into Microsoft Azure Sentinel for
  log matching.
---

# Microsoft Azure Sentinel

### Prerequisites

[An Obstracts plan that supports use of our API.](https://www.obstracts.com/pricing/)

### Setup

This integration uses the STIX/TAXII 2.x data Connector for Azure Sentinel which comes as standard in Azure Sentinel deployments.

![STIX/TAXII 2.x data Connector for Azure Sentinel](../.gitbook/assets/obstracts-azure-taxii-connector-setup.png)

You'll need to configure the following settings:

* **Friendly name (for server):** Will be shown against intelligence ingested, but can be anything you like
* **API root URL:** It’s easy to construct the Root URL. You just need your Obstracts Group UUID, [obtained on the Group Management page in the Obstracts web app](https://app.obstracts.com/user/manage\_group).
  * https://app.obstracts.com/taxii/taxii2/YOUR-GROUP-UUID
* **Collection UUID:** The Collection UUID is a Feed UUID in Obstracts and [can be obtained from the Feed List page in the Obstracts web app](https://app.obstracts.com/feed/list/).
* **Username:** your Obstracts username
* **Password:** your Obstracts API key
* **Import indicators:** Select, "At most one month old" (or sooner). _Important: We do not allow download of older indicators._
* **Polling frequency:** Select, "1 hour".

Now click save, and you should see intelligence being ingested.&#x20;

![Azure Sentinel Threat Intelligence](../.gitbook/assets/obstracts-azure-taxii-threat-intel.png)

### Usage

Once data connector is enabled, the ingested threat intelligence will be used by active rules in Azure Sentinel that utilise threat intelligence.
