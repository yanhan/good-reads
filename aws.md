# About

AWS


## References

- https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonec2.html
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_actions-resources-contextkeys.html (Actions, Resources and Conditions for all AWS services)
- https://aws.amazon.com/ec2/spot/instance-advisor/ (shows interruption percentage of all spot instance types)


## Unclassified

- https://stackoverflow.com/questions/22188444/why-do-we-need-private-subnet-in-vpc
- http://docs.aws.amazon.com/AmazonVPC/latest/PeeringGuide/invalid-peering-configurations.html
- http://docs.aws.amazon.com/AmazonVPC/latest/PeeringGuide/vpc-peering-basics.html#vpc-peering-limitations
- https://serverfault.com/questions/786890/connecting-openvpn-client-over-peering-connection-to-different-vpc-aws
- https://serverfault.com/questions/845728/aws-vpc-to-vpc-connection-with-openvpn
- https://cloudacademy.com/blog/openvpn-aws-vpc/  (Provides some insight but there are errors so it is not totally good)
- http://docs.aviatrix.com/HowTos/Cloud_Networking_Ref_Des.html
- https://www.reddit.com/r/aws/comments/4bk7ne/vpn_in_vpc_a_to_private_instance_in_vpc_b/
- https://news.ycombinator.com/item?id=15799759 (VPC Endpoints for your Own Applications and Services)
- https://aws.amazon.com/blogs/security/how-to-add-dns-filtering-to-your-nat-instance-with-squid/
- https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html
- https://aws.amazon.com/blogs/aws/amazon-cloudfront-support-for-dynamic-content/
- https://aws.amazon.com/blogs/aws/new-amazon-dynamodb-transactions/
- https://docs.aws.amazon.com/general/latest/gr/aws_tasks-that-require-root.html
- https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-access-logs.html (NLB access logs only available for TLS listeners)


## EC2

- https://www.ec2instances.info/


## IAM policy writing

- https://iam.cloudonaut.io/
- https://start.jcolemorrison.com/aws-iam-policies-in-a-nutshell/
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_actionsconditions.html (For IAM; List of all actions by service)
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_variables.html#policy-vars-infotouse
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_elements.html#AccessPolicyLanguage_ConditionType


## Restricting access to IAM resources and API actions

- https://docs.aws.amazon.com/IAM/latest/UserGuide/list_identityandaccessmanagement.html (IAM API actions resources and condition keys reference)
- https://docs.aws.amazon.com/IAM/latest/UserGuide/access_iam-tags.html#access_iam-tags_control-resources
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_iam-condition-keys.html


## EC2 launch permissisons lock down

- https://aws.amazon.com/premiumsupport/knowledge-center/restrict-launch-tagged-ami/
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-supported-iam-actions-resources.html
- https://aws.amazon.com/premiumsupport/knowledge-center/iam-policy-tags-restrict/
- https://docs.aws.amazon.com/IAM/latest/UserGuide/access_iam-tags.html


## IAM

- https://www.youtube.com/watch?v=_wiGpBQGCjU (AWS re:Invent 2015: IAM Best Practices to Live By)
- https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_passrole.html
- https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html (Permissions Boundaries)
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_multi-value-conditions.html
- https://www.youtube.com/watch?v=suBsFAEJUIc (AWS re:Invent 2017: GPS: IAM Best Practices and Becoming an IAM Ninja (GPSTEC310))


## MFA

- https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_configure-api-require.html  (MFA for API calls)
- https://aws.amazon.com/premiumsupport/knowledge-center/authenticate-mfa-cli/


## SSM

- https://www.youtube.com/watch?v=zwS8lssaY_k&list=PLhr1KZpdzukeH5jKyYi55ef9tEWAllypB&index=1 (A set of videos by AWS on SSM)
- https://docs.aws.amazon.com/systems-manager/latest/userguide/sysman-rc-setting-up-cmdsec.html (Restrict Run Command to EC2 instances with specific tags)


## EKS

- https://medium.com/@marcincuber/amazon-eks-with-oidc-provider-iam-roles-for-kubernetes-services-accounts-59015d15cb0c


## RDS

- https://aws.amazon.com/premiumsupport/knowledge-center/duplicate-master-user-mysql/ (SQL command to create a new admin user)


## Lambda

- https://docs.aws.amazon.com/lambda/latest/dg/lambda-python-how-to-create-deployment-package.html
- https://docs.aws.amazon.com/lambda/latest/dg/vpc.html#vpc-configuring
- https://stackoverflow.com/a/53364266/732396 (where to find Function Access Policy)
- https://www.alexedwards.net/blog/serverless-api-with-go-and-aws-lambda
- https://medium.com/@adhorn/multi-region-serverless-backend-reloaded-1b887bc615c0 (Multi-region Lambda)


## S3

- https://aws.amazon.com/premiumsupport/knowledge-center/s3-large-file-encryption-kms-key/
- https://start.jcolemorrison.com/the-hitchhikers-guide-to-aws-ecs-and-docker/
- https://aws.amazon.com/premiumsupport/knowledge-center/s3-bucket-store-kms-encrypted-objects/ (enforce KMS object uploads)


## Elasticsearch

- https://aws.amazon.com/blogs/security/how-to-control-access-to-your-amazon-elasticsearch-service-domain/


## Spot instances

- https://aws.amazon.com/tw/blogs/aws/new-ec2-auto-scaling-groups-with-multiple-instance-types-purchase-options/


## Cost Cutting / Reduction

- https://segment.com/blog/the-million-dollar-eng-problem/


## T2 / T3 burstable instances

- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/unlimited-mode-examples.html


## Profiling

- https://aws.amazon.com/premiumsupport/knowledge-center/network-throughput-benchmark-linux-ec2/


## TLS

- https://medium.com/soluto-nashville/best-security-practices-for-amazon-rds-with-sequelize-600a8b497804


## IPSec

- https://www.youtube.com/watch?v=7ZB_luipmB (Cisco CSR1000V)
- https://www.youtube.com/watch?v=EqVpsnAen5I (AWS re:Invent 2015 NET405 Build a Remote Access VPN solution on AWS)
- https://www.youtube.com/watch?v=qmKkbuS9gRs (AWS re:Invent 2018 NET304 AWS VPN solutions)


## KMS

- https://www.edureka.co/community/17830/call-amazon-kms-decrypt-function-without-using-binary-file (aws kms decrypt: how to use)


## Gotchas

### EKS

- https://docs.aws.amazon.com/eks/latest/userguide/network_reqs.html (Tags required for subnets in order to create load balancer)

### Billing

- https://aws.amazon.com/blogs/security/dont-forget-to-enable-access-to-the-billing-console/
