# CIS_benchmark_Ubuntu_16_1.1.0
sudo apt-get update && apt-get install software-properties-common -y && apt-add-repository ppa:ansible/ansible -y && apt-get update && apt-get install ansible git -y ;
 git clone https://github.com/srirams1225/CIS_benchmark_Ubuntu_16_1.1.0.git && cd CIS_benchmark_Ubuntu_16_1.1.0 && ansible-playbook CIS.yml
