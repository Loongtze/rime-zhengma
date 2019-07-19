# RIME郑码（rime-zhengma） -- Zhengma input method


## 说明
此郑码方案需要 [RIME | 中州韵输入法引擎](https://rime.im/)

default.yaml 文件为用户重要配置文件，其中schema_list字段后是所有可选配方，可自行增删（行首用“#”号注释表示不引入）。

### rime-zhengma中包含四个郑码码表
### 安静郑码码表
zhengma.schema.yaml  
zhengma.dict.yaml  
### 极点超集郑码码表
zmjd.schema.yaml  
zmjd.dict.yaml  
### 单字郑码码表
zmb.schema.yaml  
zmb.dict.yaml  
### 巨集郑码码表，包含极点超集郑码，并引入 60w左右[清华大学开放中文词库](http://thuocl.thunlp.org/)，供有需要的选择，词库已按词频排序。
zmbig.schema.yaml  
zmbig.dict.yaml  

## 注意,拼音123为以上四个方案编码反查所必需，所以应保留以下两个文件。
pinyin123.schema.yaml  
pinyin123.dict.yaml  


## 安裝
安装rime后，把码表复制到 Rime用户设定目录，然后重新部署。

#### macosx 其他方式    
  打开terminal,运行下面代码(需先安装homebrew):  
brew cask install squirrel  
curl -fsSL https://git.io/rime-install | bash -s openvingen/rime-zhengma  
用快捷键 control + option + ~ 重新布署    
