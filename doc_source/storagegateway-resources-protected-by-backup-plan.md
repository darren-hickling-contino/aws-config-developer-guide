# storagegateway\-resources\-protected\-by\-backup\-plan<a name="storagegateway-resources-protected-by-backup-plan"></a>

Checks if AWS Storage Gateway volumes are protected by a backup plan\. The rule is NON\_COMPLIANT if the Storage Gateway volume is not covered by a backup plan\. 

**Identifier:** STORAGEGATEWAY\_RESOURCES\_PROTECTED\_BY\_BACKUP\_PLAN

**Resource Types:** AWS::StorageGateway::Volume

**Trigger type:** Periodic

**AWS Region:** All supported AWS regions except China \(Beijing\), Asia Pacific \(Jakarta\), Middle East \(UAE\), Asia Pacific \(Hyderabad\), Asia Pacific \(Osaka\), Asia Pacific \(Melbourne\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\), Europe \(Spain\), China \(Ningxia\), Europe \(Zurich\) Region

**Parameters:**

resourceTags \(Optional\)Type: String  
Tags for Storage Gateway Volumes for the rule to check, in JSON format\.

resourceId \(Optional\)Type: String  
ID of Storage Gateway volume for the rule to check\.

crossRegionList \(Optional\)Type: String  
Comma\-separated list of destination regions for the cross\-region backup copy to be kept

crossAccountList \(Optional\)Type: String  
Comma\-separated list of destination accounts for cross\-account backup copy to be kept

maxRetentionDays \(Optional\)Type: int  
The maximum retention period in days for the Backup Vault Lock

minRetentionDays \(Optional\)Type: int  
The minimum retention period in days for the Backup Vault Lock

backupVaultLockCheck \(Optional\)Type: String  
Accepted values: 'True' or 'False'\. Enter 'True' for the rule to check if the resource is backed up in a locked vault

## AWS CloudFormation template<a name="w2aac12c33c15b9d595c17"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.