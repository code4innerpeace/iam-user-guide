# Actions, Resources, and Condition Keys for Amazon Athena<a name="list_amazonathena"></a>

Amazon Athena \(service prefix: `athena`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](http://docs.aws.amazon.com/athena/latest/ug/)\.
+ View a [list of the API operations available for this service](http://docs.aws.amazon.com/athena/latest/APIReference/)\.
+ Learn how to protect this service and its resources by [using IAM](http://docs.aws.amazon.com/athena/latest/ug/access.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon Athena](#amazonathena-actions-as-permissions)
+ [Resources Defined by Athena](#amazonathena-resources-for-iam-policies)
+ [Condition Keys for Amazon Athena](#amazonathena-policy-keys)

## Actions Defined by Amazon Athena<a name="amazonathena-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. By using policies, you define the permissions for anyone performing an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\. For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
| [BatchGetNamedQuery](http://docs.aws.amazon.com/athena/latest/APIReference/API_BatchGetNamedQuery.html) | Gets information about one or more named queries\. |   |  |  |  | 
| [BatchGetQueryExecution](http://docs.aws.amazon.com/athena/latest/APIReference/API_BatchGetQueryExecution.html) | Gets information about one or more query executions\. |   |  |  |  | 
| CancelQueryExecution | Deprecated\. Applies only to AWS services and principals that use Athena JDBC driver earlier than 1\.1\.0\. Use StopQueryExecution otherwise\. |   |  |  |  | 
| [CreateNamedQuery](http://docs.aws.amazon.com/athena/latest/APIReference/API_CreateNamedQuery.html) | Creates a named query\. |   |  |  |  | 
| [DeleteNamedQuery](http://docs.aws.amazon.com/athena/latest/APIReference/API_DeleteNamedQuery.html) | Deletes a named query specified\. |   |  |  |  | 
| GetCatalogs | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to databases and tables\. |   |  |  |  | 
| GetExecutionEngine | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to databases and tables\. |   |  |  |  | 
| GetExecutionEngines | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to databases and tables\. |   |  |  |  | 
| [GetNamedQuery](http://docs.aws.amazon.com/athena/latest/APIReference/API_GetNamedQuery.html) | Gets information about the specified named query\. |   |  |  |  | 
| GetNamespace | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to databases and tables\. |   |  |  |  | 
| GetNamespaces | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to databases and tables\. |   |  |  |  | 
| [GetQueryExecution](http://docs.aws.amazon.com/athena/latest/APIReference/API_GetQueryExecution.html) | Gets information about the specified query execution\. |   |  |  |  | 
| GetQueryExecutions | Deprecated\. Applies only to AWS services and principals that use Athena JDBC driver earlier than 1\.1\.0\. Use ListQueryExecutions otherwise\. |   |  |  |  | 
| [GetQueryResults](http://docs.aws.amazon.com/athena/latest/APIReference/API_GetQueryResults.html) | Gets information about the results of the specified query execution\. |   |  |  |  | 
| GetTable | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to tables\. |   |  |  |  | 
| GetTables | Applies only to AWS services managed policy and principals that use an Athena JDBC driver\. Enables access to tables\. |   |  |  |  | 
| [ListNamedQueries](http://docs.aws.amazon.com/athena/latest/APIReference/API_ListNamedQueries.html) | Returns a list of named queries in Amazon Athena for the specified AWS account\. |   |  |  |  | 
| [ListQueryExecutions](http://docs.aws.amazon.com/athena/latest/APIReference/API_ListQueryExecutions.html) | Returns a list of query executions for the specified AWS account\. |   |  |  |  | 
| RunQuery | Deprecated\. Applies only to AWS services and principals that use Athena JDBC driver earlier than 1\.1\.0\. Use StartQueryExecution otherwise\. |   |  |  |  | 
| [StartQueryExecution](http://docs.aws.amazon.com/athena/latest/APIReference/API_StartQueryExecution.html) | Starts a query execution using a SQL query provided as a string\. |   |  |  |  | 
| [StopQueryExecution](http://docs.aws.amazon.com/athena/latest/APIReference/API_StopQueryExecution.html) | Stops the specified query execution\. |   |  |  |  | 

## Resources Defined by Athena<a name="amazonathena-resources-for-iam-policies"></a>

Athena has no service\-defined resources that can be used as the `Resource` element of an IAM policy statement\.

## Condition Keys for Amazon Athena<a name="amazonathena-policy-keys"></a>

Athena has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](http://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.