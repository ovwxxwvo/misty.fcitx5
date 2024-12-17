## Misty Colorful theme for fcitx.  

迷幻多彩主题。  

-- **misty**  
![screenshot](screenshot/misty.png)  
-- **misty-skyblue** & **misty-seagreen**  
![screenshot](screenshot/misty-skyblue.png)  
![screenshot](screenshot/misty-seagreen.png)  

-- **misty-orange** & **misty-lemon** & **misty-grape** & **misty-peach**  
![screenshot](screenshot/misty-orange.png)  
![screenshot](screenshot/misty-lemon.png)  
![screenshot](screenshot/misty-grape.png)  
![screenshot](screenshot/misty-peach.png)  

-- **misty-carambola** & **misty-blueberry**  
![screenshot](screenshot/misty-carambola.png)  
![screenshot](screenshot/misty-blueberry.png)  

----  

### 📦 Installation 安装  

The path of the actual config file should be modified according to your own `fcitx5`.  
The following config file path base on `Arch Linux`.  

实际的配置文件的路径应该根据你自己的 `fcitx5` 进行修改。  
以下的配置文件的路经基于`Arch Linux`。  

#### Install manually 手动安装  

Clone the repo to your fcitx5 config dir :  
```  
cd ~/.local/share/fcitx5/themes/  
git clone https://github.com/ovwxxwvo/misty.fcitx5.git  
```  
Add this line to your fcitx5 config file `~/.config/fcitx5/config.fcitx5` :  
```  
source ~/.config/fcitx5/plugins/misty.fcitx5/init.fcitx5  
```  

----  

### 🛠️ Configuration 配置  

Customize your configuration file.  
```sh  
mkdir ~/.config/fcitx5/config  
touch ~/.config/fcitx5/config/misty.fcitx5  
vi    ~/.config/fcitx5/config/misty.fcitx5  
```  
Add this line to your fcitx5 config file `~/.config/fcitx5/config.fcitx5` :  
```fcitx5  
source ~/.config/fcitx5/config/misty.fcitx5  
```  

Or you can just directly modify the config file in the plugin :  
```sh  
vi ~/.config/fcitx5/plugins/misty.fcitx5/color.fsh  
vi ~/.config/fcitx5/plugins/misty.fcitx5/style.fsh  
```  

----  

### 📚 Suggestion 建议  

Your app, Your rule. Feel free to modify the files.  
你的应用，你说了算。不要害怕修改文件。  

----  

### 📜 [MIT](LICENSE) License 许可证  


