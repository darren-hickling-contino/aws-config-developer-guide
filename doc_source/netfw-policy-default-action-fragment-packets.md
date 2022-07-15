# netfw\-policy\-default\-action\-fragment\-packets<a name="netfw-policy-default-action-fragment-packets"></a>

Checks if an AWS Network Firewall policy is configured with a user defined stateless default action for fragmented packets\. The rule is NON\_COMPLIANT if stateless default action for fragmented packets does not match with user defined default action\. 

**Identifier:** NETFW\_POLICY\_DEFAULT\_ACTION\_FRAGMENT\_PACKETS

**Trigger type:** Configuration changes

**AWS Region:** All supported AWS regions except China \(Beijing\), China \(Ningxia\), AWS GovCloud \(US\-East\), AWS GovCloud \(US\-West\), Asia Pacific \(Jakarta\) Region

**Parameters:**

statelessFragmentDefaultActionsType: CSV  
Comma\-separated list of values\. You can select a max of two\. Valid values include 'aws:pass', 'aws:drop', and 'aws:forward\_to\_sfe'\.

## AWS CloudFormation template<a name="w79aac11c32c17b9d379c15"></a>

To create AWS Config managed rules with AWS CloudFormation templates, see [Creating AWS Config Managed Rules With AWS CloudFormation Templates](aws-config-managed-rules-cloudformation-templates.md)\.