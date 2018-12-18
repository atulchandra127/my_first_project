# my_first_project
Here is the Assignment which is done by the best of my knowledge.
I created one repository named as "my_first_project" on my github account. And cloned it on my system.
Next I created two ec2 instances on ubuntu16.04 server named as
1) MSR-test-Instance-1 &&  
2) MSR-test-Instance-2

Then I logged in with the use of .pem file and installed required packages mentioned in Assignment.
Created playbook for deploying Assignment tasks. In playbook I created two hosts files where I mentioned each hosts. Then created roles too for both tasks named apache & couchdb. In each roles, I used docker-compose.yml file to deploy. After completion of creating playbook, deployed it with the help of ansible-playbook. 
