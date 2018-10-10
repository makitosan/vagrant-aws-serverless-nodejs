#
Vagrant example for AWS & serverless & nodejs env

# REFERENCE

- https://knowledge.sakura.ad.jp/2882/
- https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html
- github.com repositories
  - https://github.com/djyugg/ansible-role-nodebrew
  - https://github.com/suzuki-shunsuke/ansible-nodebrew

## PROVISIONING

- box: ubuntu/xenial64
- node v8.10.0 (fixed)
  - you can change the version in group_vars/all
- awscli 1.16.30 (latest as of 2018-10)
- serverless 1.32.0 (latest as of 2018-10)
