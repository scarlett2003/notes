# 使用1. Vagrant進入Ubuntu
1. cd rails10-va
2. vagrant up
3. vagrant ssh

4. cd /vagrant
>要在此共享文件夾中建立的project，才能在透過vagrent在mac下看到資料夾並使用mac的工具編輯

5. cd rails new project -d mysql
>建立新的rails專案並使用mysql數據庫

6. rails s
7. Ctrl + D 退出
8. vagrant halt
>關掉 vagrant

## VM基本指令
1. vagrant up 開機
2. vagrant ssh 登入
3. vagrant suspend 暫停
4. vagrant halt 關機
5. vagrant destroy 刪除

## Box基本指令
1. vagrant box list 列出
2. vagrant box add 新增
3. vagrant box remove 刪除
[ihover的教學](http://www.slideshare.net/ihower/vagrant-osdc)

