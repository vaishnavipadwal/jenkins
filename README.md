# jenkins lab Setup
1. Create EC instance with ubuntu AMI (22.4 version), t2.medium/micro, 22GB RAM and 8080,ssh security group
2. launch instance on AWS terminal -> connect via SSH -> su -i (login in root user) vim jenkins.sh (craete sh scrpit file for jenkins installation)
3. jenkins website: https://in.search.yahoo.com/search?fr=mcafee&type=E210IN714G0&p=jenkins  --> download -> serach script for ubuntu copy that scrpit and paste it on jenkins.sh (in cloudshell)
4. Go to cloudshell -> bash jenkins.sh
5. Now install Java form same jenkins site -> copy that script and paste it on cloudshell
6. check java --version -> systemctl start jenkins
7. Copy instance IP paste it on browser with :8080 port
8. paste location menstioned in jenkins server for access password
9. go in cloudshel -> cat /location/
10. Copy password and paste it on jenkins server -> select plugins to install -> None -> install -> set credentials -> start jenkins 
11. 
