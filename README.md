# Zero-shot time series forecasting with Chronos using Amazon Bedrock and ClickHouse

A serverless pipeline for zero-shot forecasting of time series data stored in ClickHouse using Amazon Chronos deployed on Amazon Bedrock. An AWS Lambda function queries the context data from ClickHouse, invokes the Bedrock endpoint, and returns probabilistic forecasts as mean and quantile predictions.
