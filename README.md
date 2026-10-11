# Zero-shot time series forecasting with Chronos using Amazon Bedrock and ClickHouse

A serverless pipeline for zero-shot forecasting of time series data stored in ClickHouse using Amazon Chronos deployed on Amazon Bedrock. An AWS Lambda function queries the context data from ClickHouse, invokes the Bedrock endpoint, and returns probabilistic forecasts as mean and quantile predictions.

Full details in the [blog post](https://flaviagiammarino.com/blog/chronos_bedrock.html/).

<img src=https://machine-learning-blog.s3.eu-west-2.amazonaws.com/chronos_bedrock/architecture_diagram.png style="width:100%;margin-top:60px;margin-bottom:50px"/>

