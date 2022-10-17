# GCP fundamentals

Tools of GCP such as Workflows, PubSub, DataFlow, BigQuery using Terraform

----

## Workflows

1. Workflows official [documentation](https://cloud.google.com/workflows/docs)
2. Workflows official [documentation](https://cloud.google.com/workflows/docs/samples)
3. Execute a workflow using an Eventarc trigger that receives events using ``Pub/Sub`` [official example](https://cloud.google.com/eventarc/docs/workflows/quickstart-pubsub) and [another example](https://github.com/GoogleCloudPlatform/workflows-demos/tree/master/workflows-eventarc-integration/workflows-pubsub)
4. Basic workflow [YouTube](https://www.youtube.com/playlist?list=PLh5sxVbRzNp7H2wVwfejxbI3Xh5Z1CxE4)
5. Image processing pipeline with Eventarc and Workflows [complete pipeline example](https://codelabs.developers.google.com/codelabs/cloud-event-driven-orchestration#0)


## PubSub

1. PubSub official [documentation](https://cloud.google.com/pubsub/docs/overview)
2. Trigger Workflows using Pub/Sub messages [example](https://cloud.google.com/eventarc/docs/workflows/quickstart-pubsub)

## Terraform

1. Terraform official [documentation](https://www.terraform.io/docs)
2. Set up GCP [here](https://learn.hashicorp.com/tutorials/terraform/google-cloud-platform-build?in=terraform/gcp-get-started)
3. Create a workflow by using Terraform [official doc](https://cloud.google.com/workflows/docs/create-workflow-terraform)
4. Define and deploy a workflow [example](https://github.com/GoogleCloudPlatform/workflows-demos/blob/master/terraform/import-yaml/main.tf). If there are multiple workflow yaml files we can do [this](https://cloud.google.com/blog/topics/developers-practitioners/deploying-multi-yaml-workflows-definitions-terraform) or [this](https://github.com/GoogleCloudPlatform/workflows-demos/tree/master/terraform)
5. Define variables [link](https://cloud.google.com/docs/terraform/best-practices-for-terraform#variables); it looks like [this](https://www.terraform.io/language/values/variables)
6. A blog explaining terraform [Apprendre et Maitriser Terraform](https://blog.stephane-robert.info/post/introduction-terraform/)

## Dataflow

1. Dataflow [documentation](https://cloud.google.com/dataflow#section-5)
2. Word count [example](https://cloud.google.com/workflows/docs/reference/googleapis/dataflow/Overview) and other **templates** [here](https://cloud.google.com/dataflow/docs/guides/templates/running-templates)
3. Orchestrate a Dataflow pipeline with GCP Workflows [example](https://dev.to/stack-labs/orchestrate-dataflow-pipelines-easily-with-gcp-workflows-1i8k)

## BigQuery

1. Syntax https://cloud.google.com/bigquery/docs/reference/standard-sql/dml-syntax
2.
