# sublime-text-3-settings
This is Kelly's Repo for storing and syncing the settings of sublime-text-3. The syncing method can be found in [Here](https://packagecontrol.io/docs/syncing#git).

# Usage
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

