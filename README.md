# linux_automation_section1

## linux commands necessary to create a new linux user

- sudo adduser bob	: To create the user named bob
- id bob		: To view the ids of user bob
- su bob		: To make user bob the super user


## To install postfix package

- sudo apt install mailutils -y
- mail --version
- sudo service postfix status
- sudo service postfix start

## To send mail
- echo "Body of mail" -s "Subject of mail" example@mail.com

