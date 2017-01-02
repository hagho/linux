#ubuntu 必备软件

##sudo apt-get update
##sudo apt-get upgrade
<br/>

###vim<br/> 
sudo apt-get install vim<br/>

###搜狗拼音输入法 <br/> 
官网下载<br/>

###chrome <br/>
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -<br/>
sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list'<br/>
sudo apt-get update<br/> 
sudo apt-get install google-chrome-stable<br/>

###shadowsocks <br/> 
sudo add-apt-repository ppa:hzwhuang/ss-qt5<br/>
sudo apt-get update<br/>
sudo apt-get install shadowsocks-qt5

###teamviewer <br/>
官网下载 <br/>

###pip <br/>
sudo apt-get install python-pip <br/>
