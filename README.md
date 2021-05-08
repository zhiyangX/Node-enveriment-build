# Node-enveriment-build 我的react.js开发环境配置 macbookpro m1

## nvm卸载正在使用的node  nvm command:

nvm deactivate

nvm uninstall <version>

## git setting:

code ~/.gitconfig

打开clashx，点击设置，查看代理端口。并添加进vs code打开的文件中  find port in clashx add them in file like:

[http "https://github.com"]
	proxy = socks5://127.0.0.1:7890

or use command

 git config --global http.https://github.com.proxy socks5://127.0.0.1:7890

    
