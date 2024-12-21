## Misty colorful theme for fcitx5.  


**中文** | [**English**](README.md)  

-- **misty**  **迷幻多彩主题。**  
![screenshot](screenshot/misty.png)  
-- **misty-skyblue** & **misty-seagreen** | 天蓝＆海绿  
![screenshot](screenshot/misty-skyblue.png)  
![screenshot](screenshot/misty-seagreen.png)  

-- **misty-orange** & **misty-lemon** & **misty-grape** & **misty-peach** | 香橙＆柠檬＆葡萄＆蜜桃  
![screenshot](screenshot/misty-orange.png)  
![screenshot](screenshot/misty-lemon.png)  
![screenshot](screenshot/misty-grape.png)  
![screenshot](screenshot/misty-peach.png)  

-- **misty-carambola** & **misty-blueberry** | 杨桃＆蓝莓  
![screenshot](screenshot/misty-carambola.png)  
![screenshot](screenshot/misty-blueberry.png)  

----  

### 📦 Installation 安装  

实际的配置文件的路径应该根据你自己的 `fcitx5` 进行修改。  
以下的配置文件的路经基于`Arch Linux`。  

#### Install manually 手动安装  

Clone the repo to your fcitx5 config dir :  
```sh  
cd ~/.local/share/fcitx5/themes/  
git clone https://github.com/ovwxxwvo/misty.fcitx5.git  
```  

Link the theme dir :  
```sh  
cd ~/.local/share/fcitx5/themes/  
ln -sf  ./misty.fcitx5/misty            ./  
ln -sf  ./misty.fcitx5/misty-blueberry  ./  
ln -sf  ./misty.fcitx5/misty-carambola  ./  
ln -sf  ./misty.fcitx5/misty-grape      ./  
ln -sf  ./misty.fcitx5/misty-lemon      ./  
ln -sf  ./misty.fcitx5/misty-orange     ./  
ln -sf  ./misty.fcitx5/misty-peach      ./  
ln -sf  ./misty.fcitx5/misty-seagreen   ./  
ln -sf  ./misty.fcitx5/misty-skyblue    ./  
```  

----  

### 🛠️ Configuration 配置  

Customize your configuration file.  
```sh  
vi ~/.local/share/fcitx5/conf/classicui.conf  
```  

~/.local/share/fcitx5/conf/classicui.conf  
```dosini  
Theme=misty  
DarkTheme=misty  

PreferTextIcon=True  
ShowLayoutNameInIcon=True  
UseInputMethodLanguageToDisplayText=True  

Font="Sans 12"  
MenuFont="Sans 12"  
TrayFont="Sans Bold 12"  

TrayTextColor=#d0ffa0  
TrayOutlineColor=#002020  
```  

----  

### 📚 Suggestion 建议  

你的应用，你说了算。不要害怕修改文件。  

----  

### 📜 [MIT](LICENSE) License 许可证  


