CloudWatch Logs Agent for Debian
================================

Unfortunately, the current version (1.3.6) of the CloudWatch Logs Agent (found in
wget https://s3.amazonaws.com/aws-cloudwatch/downloads/latest/awslogs-agent-setup.py)
does not support Debian, and fails when installed in Debian 8 ('Jessie').

I made some small changes to the script so that it can be installed in Debian
instances. Use this script instead of the official installation script when
installing in a Debian instance.
