# Forecasting time series in ClickHouse with Chronos on Amazon Bedrock

A serverless pipeline for forecasting time series data stored in ClickHouse using Amazon Chronos deployed on Amazon Bedrock. An AWS Lambda function queries the context data from ClickHouse, invokes the Bedrock endpoint, and returns zero-shot probabilistic forecasts.

Full details in the [blog post](https://flaviagiammarino.com/blog/chronos_bedrock.html/).

<img src=https://machine-learning-blog.s3.eu-west-2.amazonaws.com/chronos_bedrock/architecture_diagram.png style="width:100%;margin-top:60px;margin-bottom:50px"/>

