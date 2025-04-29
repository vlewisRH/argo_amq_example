This branch can be used to create a standalone broker on the OpenShift Container Platform using Ansible and OpenShift Pipelines.

To create the broker ArgoCD Application, use the command locally, use the command
`ansible-playbook --connection=local create_standalone_broker.yml`

This role expects the cluster url and api key variables to be named `cluster_url` and `api_token`.

Args can be provided through `roles/create-standalone/vars/main.yml` or a file specified in the `configs_src` variable.

