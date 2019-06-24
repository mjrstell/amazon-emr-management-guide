# EMR Notebooks Security and Access Control<a name="emr-managed-notebooks-security"></a>

Several features are available to help you tailor the security posture of EMR Notebooks\. This helps ensure that only authorized users have access to an EMR notebook, can work with notebooks, and use the notebook editor to execute code on the cluster\. These features work along with the security features available for Amazon EMR and Amazon EMR clusters\. For more information, see [Security in Amazon EMR](emr-security.md)\.
+ You can use AWS Identity and Access Management policy statements together with notebook tags to limit access\. For more information, see [Condition Keys](security_iam_emr-with-iam.md#security_iam_emr-with-iam-id-based-policies-conditionkeys) and [Example Identity\-Based Policy Statements for EMR Notebooks](emr-fine-grained-cluster-access.md#emr-managed-notebooks-tags-examples)\.
+ EC2 security groups act as virtual firewalls that control network traffic between the cluster's master instance and the notebook editor\. You can use defaults or customize these security groups\. For more information, see [Specifying EC2 Security Groups for EMR Notebooks](emr-managed-notebooks-security-groups.md)\.
+ You specify an AWS Service Role that determines what permissions an EMR notebook has when interacting with other AWS services\. For more information, see [The IAM Role for EMR Notebooks](emr-iam-roles.md#emr-managed-notebooks-service-role)\.