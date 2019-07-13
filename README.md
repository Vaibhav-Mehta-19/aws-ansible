# aws-ansible
This repository primarily focuses on creating an ansible playbook for starting and managing of different services provided by Amazon Cloud Services.

It aims at automating the process of starting and stopping the instances of different services provided by AWS like EC2 , EBS ,etc. Theansibe playbooks provided here can be used in integration with other project in order to automate the whole process of starting and creating new services on AWS.

Use these yml files as ansible playbooks and launch instances with them by providing the required details in the ansible playbooks like access key and secret key for your aws instance. Also the number of instances, the region of aws server , the name of instance, the type of os can be changed in the playbooks. For more help refer https://docs.ansible.com/ansible/latest/modules/ec2_module.html
