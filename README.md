在安装前，请先准备好用户名，密码和两个端口（面板访问端口和流量监控端口）！
x-ui.sh上传到serv00根目录
权限命令chmod +x x-ui.sh
执行命令./x-ui.sh
安装失败修改x-ui.sh的第85行直接复制粘贴替换wget -N --no-check-certificate -O x-ui-${release}-${arch}.tar.gz https://github.com/parentalclash/x-ui-freebsd/releases/download/${last_version}/x-ui-${release}-${arch}.tar.gz 重新执行安装就可以了
