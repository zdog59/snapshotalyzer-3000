# snapshotalyzer-3000

Demo project to manage AWS EC2 instance snapshots

## About

this project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty ises the configuration file created by the AWS cli. e.e

`aws configure --profile shoty`

## Running

`pipenv run python shotty/shotty.py <command> <--project=PROJECT>`

*command* is instances, volumes, snapshots
*subcommand* - depends on command
*project* is opotional