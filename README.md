#ubuntu 必备软件 

##sudo apt-get update
##sudo apt-get upgrade

**vim**<br/> 
```
sudo apt-get install vim
```

**搜狗拼音输入法**<br/>
[官网下载](http://pinyin.sogou.com/)<br/>

**chrome**<br/>
```
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list'
sudo apt-get update
sudo apt-get install google-chrome-stable
```
**shadowsocks**<br/> 
```
sudo add-apt-repository ppa:hzwhuang/ss-qt5
sudo apt-get update
sudo apt-get install shadowsocks-qt5
```
  [**GFW List**](https://github.com/FelisCatus/SwitchyOmega/wiki/GFWList)<br/>


**teamviewer**<br/>
[官网下载](https://www.teamviewer.com/zhCN/)<br/>

**pip**<br/>
```
sudo apt-get install python-pip
```
**oh my zsh**<br/>
```
sudo apt-get install zsh
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh
chsh -s /bin/zsh
```
***zsh主题修改***<br/>
修改个人目录下的.zshrc文件 [主题](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes)<br/>

**远程办公**<br />
[***MobaXterm***](http://mobaxterm.mobatek.net/)<br />
[***Sublime SFTP***](https://wbond.net/sublime_packages/sftp)<br />
[***Sublime注册码***](http://9iphp.com/web/html/sublime-text-3-license-key.html)<br />
[***SFTP破解***](http://trully.github.io/blog/2014/05/30/shi-yong-sublime-de-sftp/)<br />

**显示目录树**<br />
```
sudo apt-get install tree
```
