# ai-prometheus-grafana
Set of playbooks to deploy Prometheus/Grafana operators on Openshift with Assisted Service Operator

1. Should be installed ansible on machine
# yum install ansible

2. Update main.yaml with correct kubeconfig_file: "/root/kubeconfig"

3. Running command
# ansible-playbook -vv main.yaml
