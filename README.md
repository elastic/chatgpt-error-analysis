# chatgpt-error-analysis
This repository provides a sample watcher script that can be used to send log messages from [Elasticsearch](https://github.com/elastic/elasticsearch) to [ChatGPT] for analysis 

The script in this repository can be used as described in this following blog online. 

If you plan on following this blog, here are some of the components and details we used to set up the configuration:

- Ensure you have an account on Elastic Cloud and a deployed stack (see instructions here).
- Kubernetes cluster, but you can use any Kubernetes cluster service (on-prem or cloud based) of your choice.
- Application of your choice running on the  Kubernetes cluster to generate a load. We would recommend using [OpenTelemetry Demo] (https://github.com/elastic/opentelemetry-demo) that is also pushing logs (minimally) into Elastic.
- Pick an OpenAI service. Either Azure OpenAI service (which is used in this configuration) or OpenAI service it self.
- Access to Elastic's dev tools, the console to be specific.
- Access to create a new index to store the results from the OpenAI query.

## Disclaimer

See the full documentation online in this [Elastic Blog Post] (https://www.elastic.co/blog/). **https://github.com/elastic/chatgpt-error-analysis** is an Elastic Labs project. Elastic Labs projects are for illustrative and experimental purposes only. This Elastic Labs project is not part of any product or services offering provided or supported under a commercial license or subscription. This project is made available as-is under the terms of the license associated with this project.
The release and timing of any features or functionality described in this project remain at Elastic's sole discretion. Any features or functionality not currently available may not be delivered on time or at all.

## License

`elastic/chatgpt-error-analysis` is available under the Apache 2.0 license.
For more details see [LICENSE](https://github.com/elastic/chatgpt-error-analysis/blob/main/LICENSE).



