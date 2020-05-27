# snapshotalyzer-30000

Demo project to manage AWS EC2 instances snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile python`

## Running

pipenv run python pipenv run python "shotty\shotty.py" <command> <subcommand> <--project=PROJECT>

*command* is instances, volumes, or snapshots
*subcommand* depends on Command
  for command instances, subcommand is list, start, stop, or snapshot
  for commands volumes or snapshots is list
*project* is optional

# just a test to see if it continues to work after changing SSH key
