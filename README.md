# sublime-text-3-settings
This is Kelly's Repo for storing and syncing the settings of sublime-text-3. The syncing method can be found in [Here](https://packagecontrol.io/docs/syncing#git).

# Main features
侧边栏文件夹支持（虽然不大好用）  
Material Design Dark♂主题  
SublimeREPL，轻量的在sublime里运行python等的一个插件  
自动补全支持，主要是Python  
Markdown的编辑，预览  
转换UTF-8编码，字数统计  

# Usage
同步的原理其实就是同步配置文件，并预装好Package Control，它会根据包配置自动安装包，这在各个平台的sublime都是有效的。  
安装Package Control的脚本：  
```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```
[Package Control](https://packagecontrol.io/installation)
## Ubuntu
git clone https://github.com/KellyHwong/sublime-text-3-settings
cp -rf ./sublime-text-3-settings/* ~/.config/sublime-text-3/*
Warning: -rf means your own setting will be overwritten
If you want to merge, use cp -ri instead

## Ubuntu
```
git clone https://github.com/KellyHwong/sublime-text-3-settings  
cp -ri ./sublime-text-3-settings/* ~/.config/sublime-text-3/* 
```
Warning: -rf means your own setting will be overwritten  
If you want to merge, use cp -ri instead  

Also, with ctrl + h to show hidden files at ${HOME} you can find the config path, and drag it.  

## Mac
```
git clone https://github.com/KellyHwong/sublime-text-3-settings  
cp -ri ~/Library/Application\ Support/Sublime\ Text\ 3/* 
```

in ~/Library/Application\ Support/Sublime\ Text\ 3

Note: ~/Library/Application\ Support/Sublime\ Text\ 3 for cd in terminal  
~/Library/Application Support/Sublime Text 3 for finder goto  
**Escapes*** are needed for terminal  

Also you can just drag it with Finder if you prefer  

## Windows
in %AppData%  
just drag it with Windows Explorer(资源管理器)  

## Automatic bash/cmd scripts TODO
For Mac/Ubuntu:  
```
sudo bash ./nil.sh (it should decide darwin/linux, for path, others are same)
```
For Windows:  
TODO  
```
# i guess
run as balabala some shit syntax of windows cmd .\(also diff seperator)nil.bat
```

## Contribution
Any bugs/questions/problems, please create issues:  
https://github.com/KellyHwong/sublime-text-3-settings/issues/new

