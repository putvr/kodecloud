# just for fun

git clone https://github.com/putvr/kodecloud.git && pip install ansible && cd kodecloud

wget https://raw.githubusercontent.com/putvr/kodecloud/master/ansible.cfg && \
wget https://raw.githubusercontent.com/putvr/kodecloud/master/hosts.yml && \
pip install ansible 


sshpass -p Bl@kW ssh natasha@ststor01 -o StrictHostKeyChecking=no