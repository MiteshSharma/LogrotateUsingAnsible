# Logrotate using Ansible

As per Logrotate [Github page](https://github.com/logrotate/logrotate):
The logrotate utility is designed to simplify the administration of log files on a system which generates a lot of log files. Logrotate allows for the automatic rotation compression, removal, and mailing of log files. Logrotate can be set to handle a log file daily, weekly, monthly or when the log file gets to a certain size.


Logrotate can be used to do the following things:
1. Rotate a file based on size and time
2. Add date to the log file which helps during debugging
3. Create new log files with required permissions
4. Remove old log files
5. Run custom commands before and after log rotation
6. Compress log files to save space

playbook.yml is main ansible file which is executed by ansible command.

Steps to execute this project:
1. Clone this project on your local machine
2. Start your ubuntu instance with port 22 open to be accessed from your local machine
3. Update inventory file with correct IP address of an ubuntu instance
4. Execute Ansible command mentioned below:

Ansible command: **ansible-playbook playbook.yml**

More information about ansible can be found [here](https://www.ansible.com/).
