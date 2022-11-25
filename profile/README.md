<!-- Copyright Yahoo. Licensed under the terms of the Apache 2.0 license. See LICENSE in the project root. -->

![Vespa Cloud logo](https://cloud.vespa.ai/assets/logos/vespa-cloud-logo-full-black.png)

# Vespa Cloud Sample Applications
Welcome to the [Vespa Cloud](https://cloud.vespa.ai/) sample applications repository!

First-time users should go through the [getting-started](https://cloud.vespa.ai/en/getting-started) guide first.

The [Vespa.ai](https://vespa.ai/) sample applications are created to run both self-hosted 
and on [Vespa Cloud](https://cloud.vespa.ai/) -
check the repository at [Vespa.ai sample apps](https://github.com/vespa-engine/sample-apps).
You can easily deploy Vespa.ai the sample applications without changing the files -
just follow the same steps as for [vector-search](#vector-search), adding security credentials.

Below, find sample applications written _specifically_ for Vespa Cloud.


## vector-search
There is a growing interest in AI-powered vector representations of unstructured multimodal data
and searching efficiently over these representations.
[vector-search](https://github.com/vespa-cloud/vector-search)
describes how your organization can unlock the full potential of multimodal AI-powered vector representations
using Vespa Cloud -- the industry-leading managed Vector Search Service.


## cord-19-search
[cord19.vespa.ai](https://cord19.vespa.ai/) is a full-featured application - see
* [cord-19](https://github.com/vespa-engine/cord-19): frontend
* [cord-19-search](https://github.com/vespa-cloud/cord-19-search): search backend


## vespa-documentation-search
[vespa-documentation-search](https://github.com/vespa-cloud/vespa-documentation-search) is a search application -
refer to this for pointers on AWS integration / GitHub Actions automation.
This sample app is a good start for [automated deployments](https://cloud.vespa.ai/en/automated-deployments),
as it has system, staging and production test examples.
It uses the [Document API](https://docs.vespa.ai/en/document-api-guide.html)
both for regular PUT operations but also for UPDATE with _create-if-nonexistent_.
