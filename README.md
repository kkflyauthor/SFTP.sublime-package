# SFTP.sublime-package
sublime在安装插件前需要安装package control组件，但是由于packagecontrol.io的限制，导致该组件无法下载（这里已提供Package Control.sublime-package），
有了Package Control.sublime-package任会出现问题（因为无法请求channel_v3.json），这里也提供了channel_v3.json包，可以看图2配置。
安装好package control后再安装SFTP时同样遇到了packagecontrol.io的限制，问题是无法请求https://packagecontrol.io/files/3-win/SFTP.sublime-package，
这里可以把SFTP.sublime-package放置在相应路径（http://www.xx.com/SFTP.sublime-package）,然后在channel_v3.json包中，通过该路径代替https://packagecontrol.io/files/3-win/SFTP.sublime-package即可，注意更改配置文件后要重启sublime。
