# TeamCity CloudFormation Template

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=test&templateURL=https://raw.githubusercontent.com/JetBrains/teamcity-cloudformation-template/master/teamcity-server-ha.yaml)

Components + scheme

    Server
    Database
    Agents

High Availability

    ECS + ALB
    EFS
    readonly node

Security
    
    Internet facing
    SSL

Upgrade

Troubleshooting

    SSH Access
    Direct node links

