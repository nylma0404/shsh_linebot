### 【程式設計】用LINEBot改善校園生活
#### 安裝Django及line-bot-sdk
```
$ pip install Django
$ pip install line-bot-sdk
$ pip install virtualenv
```
#### 開啟第一個Django專案
```
$ cd C:/
$ django-admin startproject "專案名稱"
$ cd "專案名稱"
```
#### 建立虛擬環境
```
#建立虛擬環境方式
$ virtualenv "虛擬環境名稱"

#啟動虛擬環境方式
$ .\"虛擬環境名稱"\Scripts\activate
```
#### 建立Django APP
```
python manage.py startapp "APP名稱"
```
#### 新增資料夾
```
md templates
md static
```
#### 更改settings.py
##### 把LINE的Channel Access Token跟Channel Secret新增到Secret_Key之前
```

```
