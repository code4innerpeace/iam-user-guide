# Actions, Resources, and Condition Keys for Amazon Kinesis<a name="list_amazonkinesis"></a>

Amazon Kinesis \(service prefix: `kinesis`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](http://docs.aws.amazon.com/kinesis/latest/dev/)\.
+ View a [list of the API operations available for this service](http://docs.aws.amazon.com/kinesis/latest/APIReference/)\.
+ Learn how to protect this service and its resources by [using IAM](http://docs.aws.amazon.com/kinesis/latest/dev/controlling-access.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon Kinesis](#amazonkinesis-actions-as-permissions)
+ [Resources Defined by Kinesis](#amazonkinesis-resources-for-iam-policies)
+ [Condition Keys for Amazon Kinesis](#amazonkinesis-policy-keys)

## Actions Defined by Amazon Kinesis<a name="amazonkinesis-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
| [AddTagsToStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_AddTagsToStream.html) | Adds or updates tags for the specified Amazon Kinesis stream\. Each stream can have up to 10 tags\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [CreateStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_CreateStream.html) | Creates a Amazon Kinesis stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [DecreaseStreamRetentionPeriod](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_DecreaseStreamRetentionPeriod.html) | Decreases the stream's retention period, which is the length of time data records are accessible after they are added to the stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [DeleteStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_DeleteStream.html) | Deletes a stream and all its shards and data\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [DescribeLimits](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_DescribeLimits.html) | Describes the shard limits and usage for the account\. |   |  |  |  | 
| [DescribeStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_DescribeStream.html) | Describes the specified stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [DisableEnhancedMonitoring](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_DisableEnhancedMonitoring.html) | Disables enhanced monitoring\. |   |  |  |  | 
| [EnableEnhancedMonitoring](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_EnableEnhancedMonitoring.html) | API\_EnableEnhancedMonitoring\.html |   |  |  |  | 
| [GetRecords](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_GetRecords.html) | Gets data records from a shard\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [GetShardIterator](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_GetShardIterator.html) | Gets a shard iterator\. A shard iterator expires five minutes after it is returned to the requester\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [IncreaseStreamRetentionPeriod](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_IncreaseStreamRetentionPeriod.html) | Increases the stream's retention period, which is the length of time data records are accessible after they are added to the stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [ListStreams](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_ListStreams.html) | Lists your streams\. |   |  |  |  | 
| [ListTagsForStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_ListTagsForStream.html) | Lists the tags for the specified Amazon Kinesis stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [MergeShards](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_MergeShards.html) | Merges two adjacent shards in a stream and combines them into a single shard to reduce the stream's capacity to ingest and transport data\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [PutRecord](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_PutRecord.html) | Writes a single data record from a producer into an Amazon Kinesis stream\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [PutRecords](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_PutRecords.html) | Writes multiple data records from a producer into an Amazon Kinesis stream in a single call \(also referred to as a PutRecords request\)\. |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [RemoveTagsFromStream](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_RemoveTagsFromStream.html) | Description for SplitShard |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [SplitShard](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_SplitShard.html) | Description for SplitShard |   | [stream\*](#amazonkinesis-stream)  |  |  | 
| [UpdateShardCount](http://docs.aws.amazon.com/kinesis/latest/APIReference/API_UpdateShardCount.html) | Updates the shard count of the specified stream to the specified number of shards\. |   |  |  |  | 

## Resources Defined by Kinesis<a name="amazonkinesis-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#amazonkinesis-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
| [stream](http://docs.aws.amazon.com/kinesis/latest/dev/) | arn:$\{Partition\}:kinesis:$\{Region\}:$\{Account\}:stream/$\{StreamName\} |  | 

## Condition Keys for Amazon Kinesis<a name="amazonkinesis-policy-keys"></a>

Kinesis has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](http://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.