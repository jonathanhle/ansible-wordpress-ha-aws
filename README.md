# ansible-wordpress-ha-aws

##Notes
1. RDS module only works if running Ansible from source (not PIP, Apt, or PPA packages) as of 4/15/2014.  Some kind of issue with Boto.
2. Needs AWS CLI installed locally.
3. Need to have ENV vars set for AWS CLI tool
4. Need to have ENV vars set for Boto
5. Group All Vars should be set to whatever you need.
6. WP is installed from latest.tar.
7. This was an exercise to pickup Ansible, and if you're looking for something Production ready - this will need some tweaking.

