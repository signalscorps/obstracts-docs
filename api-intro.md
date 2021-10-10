---
description: Welcome to the Obstracts API documentation.
---

# Intro to our API's

Obstracts has two API's, each suited for different use-cases:

### REST API

* ➕ Much more flexible to extract data on a per feed or per alert basis, including custom extractions. 
* ➕ Can be used to integrate data into almost any other product that supports programmatic data import.
* ➖ Requires some level of technical knowledge to implement.

### TAXII API

* ➕ Natively supported as a transport type in many security products, thus you to only enter your Obstracts credentials to configure.
* ➖ Results can be filtered, but the filtering options are limited to TAXII specification.
* ➖ The TAXII specification is quite flexible in the way it can be implemented. Our implementation follows TAXII and STIX 2.1 standards, but not all software might follow the same approach which can cause issues.

## Prerequisites

![Upgrade your Obstracts account](../.gitbook/assets/obstract-no-key.png)

To access the REST API you must have an upgraded Obstracts account. After your account has been upgraded you will be able to generate new API keys at: [https://app.obstracts.com/integrations](https://app.obstracts.com/integrations)

## API Keys

![Generate Obstracts API key](../.gitbook/assets/obstract-with-key.png)

You can generate one or more API keys once your account has been upgraded.

You can can also delete API keys. Deleted API keys will immediately become unusable.

API keys are used for REST API or TAXII API.

