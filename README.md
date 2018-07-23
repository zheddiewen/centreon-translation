### Simple Chinese Translate
- Maintain by eddiewen<eddiewen@icanwne.com>
- Create directory in Centreon
```shell
sudo mkdir -p /usr/share/centreon/www/locale/zh_CN/LC_MESSAGES 
sudo cp message.mo /usr/share/centreon/www/locale/zh_CN/LC_MESSAGES
sudo chown -R apache.apache /usr/share/centreon/locale/zh-CN/LC_MESSAGES
sudo systemctl restart httpd (CentOS7/Debian)
sudo service httpd restart (CentOS6)
```
![Alt text][./translate.png]
![avatar][./home.png]
- Nagvis can be well integrated with centreon
![avatar][./nagvis.png]
