# ansible-iotanode

Easy one stop shop to deploying a full IOTA Node + GUI to multiple linux hosts (RHEL/Debain)

This will download, configure, and deploy all necessary packages to have a working full IOTA Node running with GUI. Tested in Redhat/CentOS 7 and Ubuntu 14.04/16.04 LTS

Update inventory file with node IP address.

SSH Key:
ansible-playbook -i inventory playbooks/iota_node.yml --user username --key-file ~/.ssh/key.pem

Username / Password
ansible-playbook -i inventory playbooks/iota_node.yml --user username -kK


This configuration is pre-configured with neighbors currently running. Feel free to PM me your node IP and I will add it to the list.






#####Generated in Ansible#####################################################

BTC: 1FfBp3f9q8zTR3MfNgJ2WmoEyWue1XaQRy                   
ETH: 0xf213043606e2eb9610b49298ec28428635814c06                
LTC: LfzJWAANaCXrC3sbV9Z53seB2VCUDvQypG                       
IOTA: BHLDWLPMPWXFNZSFQZULEHHURSRPZVUIGTES9JUMCUFNOXGK99MAGMUNXT9ZSJZZCSLNKPECHXJ9AMVAXRUAASQSPD
