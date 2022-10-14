### Terraform AWS ECS Jenkins

This project provides a relatively robust Jenkins based on AWS ECS fargateRun a Jenkins master in AWS ECS(fargate mode) 

More details:  [基于Terraform在AWS ECS中构建Jenkins持续集成体系|Alliot&#39;s blog](https://www.iots.vip/post/terraform-aws-ecs-jenkins.html)

```shell
terrform init
terraform apply -var-file=variables/prod.tfvars
```
