# TruLens sample notebook for Azure OpenAI

This repo contains a sample notebook forked from [here](https://www.trulens.org/trulens_eval/quickstart/) and that is customized to use [Azure OpenAI service](https://azure.microsoft.com/products/ai-services/openai-service).

To use it, clone this repo and copy the [.env.sample](/.env.sample) file by naming it `.env` and by customizing it with the values of your Azure OpenAI service.

Please make sure that inside the Azure OpenAI service you have created these two model deployments with these **exact names**:

- `text-embedding-ada-002`
- `gpt-35-turbo`
