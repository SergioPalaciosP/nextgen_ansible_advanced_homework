# Ansible Advanced Homework

## Description
Repo with information about final LAB for the Red Hat Delivery Specialist—Ansible Advanced accreditation.
Required next OPENTLC lab environments:
- Ansible Advanced - Homework
- Ansible Advanced NG - OpenStack
- Ansible Advanced - Three Tier App

Note that "Ansible Advanced - Three Tier App" environment is provisioned as a task during lab execution, so is not needed to deploy manually.


## Environment preparation
Login as root in the control node in the "Homework" environment is required to setup environment variables:

```bash
[root@control ~/nextgen_ansible_advanced_homework]# cat ~/labrc
export TOWER_GUID=<Tower env GUID>
export OSP_GUID=<OSP Env GUID>
export OSP_DOMAIN=<OSP Env domain name>
export OPENTLC_ID=<username-example.com>
export MAIL_ID=<username@example.com>
export OPENTLC_PASSWORD=<Your OPENTLC Password>
export GITHUB_REPO=https://github.com/<github username>/nextgen_ansible_advanced_homework.git
export JQ_REPO_BASE=http://www.opentlc.com/download/ansible_bootcamp
export REGION=us-east-1
```

Set the env vars from ~/labrc

```bash
[root@control ~]# source ~/labrc 
```



