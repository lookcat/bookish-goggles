```
查看当前Ruby版本
ruby -v

升级Ruby环境，首先需要安装rvm
curl -L get.rvm.io | bash -s stable 

source ~/.bashrc

source ~/.bash_profile

查看rvm版本
rvm -v 

列出ruby可安装的版本信息
rvm list known

安装一个ruby版本
rvm install 2.6.3

设置为默认版本
rvm use 2.6.3 --default

更换源
sudo gem update --system

gem sources --remove https://rubygems.org/

gem sources --add https://gems.ruby-china.com/

安装CocoaPods
sudo gem install -n /usr/local/bin cocoapods

sudo xcode-select -switch /Applications/Xcode.app/Contents/Developer

安装本地库
pod setup

```


```
新建一个Xcode工程，使用终端cd到工程目录下创建Podfile文件
pod init
open Podfile
pod 'AFNetworking'
pod install

```