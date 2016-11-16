---
- hosts : devl214250005
  remote_usr : RHEL 7
  gather_facts : false
  tasks :
  - name : Installing HTTPD Server
    yum : name=httpd state=latest
