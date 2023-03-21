# -JJTech-Ansible-Tower
# - 		Spin a red hat instance- Red Hat Enterprise Linux 8
		Instance type- t3.large
		Storage- 30gb
		Keypair-Yes
		Auto assign Public IP-Yes
		Security Groups
		SSH
		HTTP
		HTTPS
		Run the commands in this order
		1. Install wget.
		 # sudo yum install wget -y
		2. Unzip ansible tower installation files.
		 # wget  https://releases.ansible.com/ansible-tower/setup/ansible-tower-setup-latest.tar.gz
		3. ls to see the file.
		4 Run
		 # tar xvzf ansible-tower-setup-latest.tar.gz
		5 # ls
		6  # cd into the ansible tower folder-
		ansible-tower-setup-3!!!!!!
		7 vi inventory edit passwords and save
		admin_password=‘ansible’
		pg_password=’ansible
		8 install ansible tower
		sudo ./setup.sh
		9. ping your public ip when setup is complete
		10. click on proceed
		11. Enter login details
		username-admin
		password-ansible
		12 Ansible Tower console
		enter your login details and get free subscription license
		accept agreement and proceed.
