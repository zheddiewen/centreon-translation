### 中文翻译
- Maintain by eddiewen <eddiewen@icanwne.com>
- 在Centreon中创建语言目录
```shell
sudo mkdir -p /usr/share/centreon/www/locale/zh_CN/LC_MESSAGES 
sudo cp message.mo /usr/share/centreon/www/locale/zh_CN/LC_MESSAGES
sudo chown -R apache.apache /usr/share/centreon/locale/zh-CN/LC_MESSAGES
sudo systemctl restart httpd (CentOS7/Debian)
sudo service httpd restart (CentOS6)
```
<img width="700" alt="home" src="https://user-images.githubusercontent.com/30824531/43068686-c19941c0-8e9d-11e8-8f79-0b9ed040dbf3.png">
<img width="698" alt="translate" src="https://user-images.githubusercontent.com/30824531/43068692-c6b6c146-8e9d-11e8-853c-0a78ab31057e.png">
- Nagvis可以很好的集成到Centreon中
<img width="708" alt="nagvis" src="https://user-images.githubusercontent.com/30824531/43068700-cb5e1d98-8e9d-11e8-99c5-0d85149a741c.png">

