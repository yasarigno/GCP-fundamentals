# GCP fundamentals

Tools of GCP such as Workflows, PubSub, DataFlow, BigQuery using Terraform

----

## Workflows

1. Workflows official [documentation](https://cloud.google.com/workflows/docs)
2. Workflows official [examples](https://cloud.google.com/workflows/docs/samples)
3. Execute a workflow using an Eventarc trigger that receives events using ``Pub/Sub`` [official example](https://cloud.google.com/eventarc/docs/workflows/quickstart-pubsub) and [another example](https://github.com/GoogleCloudPlatform/workflows-demos/tree/master/workflows-eventarc-integration/workflows-pubsub)
4. Basic workflow [YouTube](https://www.youtube.com/playlist?list=PLh5sxVbRzNp7H2wVwfejxbI3Xh5Z1CxE4)
5. Image processing pipeline with Eventarc and Workflows [complete pipeline example](https://codelabs.developers.google.com/codelabs/cloud-event-driven-orchestration#0)
6. ``Eventarc`` examples by google [Eventarc Samples](https://github.com/GoogleCloudPlatform/eventarc-samples)
7. [This](https://github.com/GoogleCloudPlatform/workflows-demos/tree/master/workspace-integration/sheets-to-workflows) can be interesting: Triggering Workflows from Google Sheets
8. A good example [Build a serverless BigQuery ingestion pipeline using Cloud Workflows](https://medium.com/codeshake/build-a-serverless-bigquery-ingestion-pipeline-using-cloud-workflows-f893f6b701ee) and yet another [Automate the execution of BigQuery queries with Cloud Workflows](https://medium.com/google-cloud/automate-the-execution-of-bigquery-queries-with-cloud-workflows-9fffe0557dbb)

## PubSub

1. PubSub official [documentation](https://cloud.google.com/pubsub/docs/overview)
2. Trigger Workflows using Pub/Sub messages [example](https://cloud.google.com/eventarc/docs/workflows/quickstart-pubsub)
3. A simple example bigquery + pubsub [link](https://towardsdev.com/using-google-cloud-workflows-to-run-bigquery-and-cloud-functions-jobs-in-a-pipeline-bfecfab36e42)
4. [Methods](https://cloud.google.com/workflows/docs/reference/googleapis/pubsub/v1/projects.topics/publish)

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
2. Connector for Bigquery [link](https://cloud.google.com/workflows/docs/samples/workflows-connector-bigquery)
3. Bigquery jobs (insert, query etc.) [link](https://cloud.google.com/workflows/docs/reference/googleapis/bigquery/v2/jobs/insert)

## Error reporting

1. When a workflow throws an error during execution, it can be caught and handled. [See how to catch the errors](https://cloud.google.com/workflows/docs/reference/syntax/catching-errors)
2. Logging [Send logs to Cloud Logging](https://cloud.google.com/workflows/docs/log-workflow) See also ``Logs Explorer``
3. ``sys.log`` is a part of it [link](https://cloud.google.com/workflows/docs/reference/stdlib/sys/log)
4. Here is [a good example](https://stackoverflow.com/questions/67801547/gcp-workflows-and-bigquery)

## Misc

1. [Online UUID Generator](https://www.uuidgenerator.net/version4)
2. 

