# ansiblerole-awsinspectoragent-windows on ubuntu
# --How to Install and Configure Ansible on Ubuntu?--
# pre-requisites:
step 1:Ansible Installation
step 2:SSH Key Exchange
step 3:Ansible Client Setup
step 4:Ansible Test
#--How to install Ansible on Windows?---
1-Cygwin install
2-Double click on Cygwin Terminal icon from the desktop and type ansible --version
# windows server: 
  Step 1: Create Ansible Windows User
  Step 2: Setup Libraries and WinRM
  Step 3: Update the Ansible Inventory file
  Step 4: Update the Ansible Group Variables
  Step 5: Configure Windows Servers to Manage
  Step 6: Test Connectivity to the Windows Server
# ansibolerole-to-inspector-agent:
# Role Name:
A brief description of the role goes here.
# Requirements:
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
# Role Variables:
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
# Dependencies:
A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.
# Example Playbook:
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
# This tasks installs AWS Inspector agent
- name: install inspector agent
- hosts: win
  roles: 
      - { riponbanik.ansible_role_aws_inspector_agent } 
