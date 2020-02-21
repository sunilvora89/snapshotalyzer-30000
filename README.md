# snapshotalyzer-30000

Demo project to list ec2 instances

# About
This project is a demo, and uses boto3 to manage EC2 instance snapshots

# Configuring
project uses configuration file created by the AWS cli. e.g.
`aws configure --profile default`

# Running
`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is list, start or stop
*subcommand* depends on the coammand
*project* is optional
