# rds\-logging\-enabled<a name="rds-logging-enabled"></a>

Checks that respective logs of Amazon Relational Database Service \(Amazon RDS\) are enabled\. The rule is NON\_COMPLIANT if any log types are not enabled\. 

**Identifier:** RDS\_LOGGING\_ENABLED

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except China \(Ningxia\), Europe \(Milan\), Africa \(Cape Town\) Region

**Parameters:**

additionalLogs \(Optional\)Type: StringMap  
Comma\-separated list of engine names and log type names\.

## AWS CloudFormation template<a name="w24aac11c29c17b7d261c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.