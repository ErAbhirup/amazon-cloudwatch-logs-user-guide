# Amazon CloudWatch Logs User Guide

-----
*****Copyright &copy; 2018 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What is Amazon CloudWatch Logs?](WhatIsCloudWatchLogs.md)
   + [Amazon CloudWatch Logs Concepts](CloudWatchLogsConcepts.md)
   + [CloudWatch Logs Limits](cloudwatch_limits_cwl.md)
+ [Getting Set Up](GettingSetup_cwl.md)
+ [Getting Started with CloudWatch Logs](CWL_GettingStarted.md)
   + [Use the Unified CloudWatch Agent to Get Started With CloudWatch Logs](UseCloudWatchUnifiedAgent.md)
   + [Use the Previous CloudWatch Logs Agent to Get Started With CloudWatch Logs](UsePreviousCloudWatchLogsAgent.md)
      + [Quick Start: Install and Configure the CloudWatch Logs Agent on a Running EC2 Linux Instance](QuickStartEC2Instance.md)
      + [Quick Start: Install and Configure the CloudWatch Logs Agent on an EC2 Linux Instance at Launch](EC2NewInstanceCWL.md)
      + [Quick Start: Enable Your Amazon EC2 Instances Running Windows Server 2016 to Send Logs to CloudWatch Logs Using the CloudWatch Logs Agent](QuickStartWindows2016.md)
      + [Quick Start: Enable Your Amazon EC2 Instances Running Windows Server 2012 and Windows Server 2008 to Send logs to CloudWatch Logs](QuickStartWindows20082012.md)
      + [Quick Start: Install the CloudWatch Logs Agent Using AWS OpsWorks and Chef](QuickStartChef.md)
      + [Report the CloudWatch Logs Agent Status](ReportCWLAgentStatus.md)
      + [Start the CloudWatch Logs Agent](StartTheCWLAgent.md)
      + [Stop the CloudWatch Logs Agent](StopTheCWLAgent.md)
   + [Quick Start: Use AWS CloudFormation to Get Started With CloudWatch Logs](QuickStartCloudFormation.md)
+ [Working with Log Groups and Log Streams](Working-with-log-groups-and-streams.md)
   + [Encrypt Log Data in CloudWatch Logs Using AWS KMS](encrypt-log-data-kms.md)
+ [Searching and Filtering Log Data](MonitoringLogData.md)
   + [Filter and Pattern Syntax](FilterAndPatternSyntax.md)
   + [Creating Metric Filters](MonitoringPolicyExamples.md)
      + [Example: Count Log Events](CountingLogEventsExample.md)
      + [Example: Count Occurrences of a Term](CountOccurrencesExample.md)
      + [Example: Count HTTP 404 Codes](Counting404Responses.md)
      + [Example: Count HTTP 4xx Codes](FindCountMetric.md)
      + [Example: Extract Fields from an Apache Log](ExtractBytesExample.md)
   + [Listing Metric Filters](ListingMetricFilters.md)
   + [Deleting a Metric Filter](DeletingMetricFilter.md)
   + [Search Log Data Using Filter Patterns](SearchDataFilterPattern.md)
+ [Real-time Processing of Log Data with Subscriptions](Subscriptions.md)
   + [Using CloudWatch Logs Subscription Filters](SubscriptionFilters.md)
   + [Cross-Account Log Data Sharing with Subscriptions](CrossAccountSubscriptions.md)
      + [Create a Destination](CreateDestination.md)
      + [Create a Subscription Filter](CreateSubscriptionFilter.md)
      + [Validating the Flow of Log Events](ValidateLogEventFlow.md)
      + [Modifying Destination Membership at Runtime](ModifyDestinationMembership.md)
+ [Sending Logs Directly to Amazon S3](Sending-Logs-Directly-To-S3.md)
+ [Exporting Log Data to Amazon S3](S3Export.md)
   + [Export Log Data to Amazon S3 Using the Console](S3ExportTasksConsole.md)
   + [Export Log Data to Amazon S3 Using the AWS CLI](S3ExportTasks.md)
+ [Streaming CloudWatch Logs Data to Amazon Elasticsearch Service](CWL_ES_Stream.md)
+ [Authentication and Access Control for Amazon CloudWatch Logs](auth-and-access-control-cwl.md)
   + [Overview of Managing Access Permissions to Your CloudWatch Logs Resources](iam-access-control-overview-cwl.md)
   + [Using Identity-Based Policies (IAM Policies) for CloudWatch Logs](iam-identity-based-access-control-cwl.md)
   + [CloudWatch Logs Permissions Reference](permissions-reference-cwl.md)
+ [Using CloudWatch Logs with Interface VPC Endpoints](cloudwatch-logs-and-interface-VPC.md)
+ [Logging Amazon CloudWatch Logs API Calls in AWS CloudTrail](logging_cw_api_calls_cwl.md)
+ [CloudWatch Logs Agent Reference](AgentReference.md)
+ [Monitoring Usage with CloudWatch Metrics](CloudWatch-Logs-Monitoring-CloudWatch-Metrics.md)
+ [Document History](DocumentHistory_cwl.md)
+ [AWS Glossary](glossary.md)