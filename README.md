
<img src="https://cloud.vespa.ai/assets/logos/vespa-cloud-logo-full-black.svg" width="150px" alt="Vespa Cloud logo" />

# Vespa Cloud Sample Applications


### cord-19-search
[cord19.vespa.ai](https://cord19.vespa.ai/) is a full-featured application - see
* [cord-19](https://github.com/vespa-engine/cord-19): frontend
* [cord-19-search](cord-19-search): search backend

### vespa-documentation-search
[vespa-documentation-search](vespa-documentation-search) is a search application -
refer to this for pointers on AWS integration / GitHub Actions automation.
This sample app is a good start for [automated deployments](https://cloud.vespa.ai/en/automated-deployments),
as it has system, staging and production test examples.
It uses the [Document API](https://docs.vespa.ai/en/document-api-guide.html)
both for regular PUT operations but also for UPDATE with _create-if-nonexistent_.
