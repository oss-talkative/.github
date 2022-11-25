# 🚸 실종자 온라인 제보 서비스

<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=Dart&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=Flutter&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/>

> 번거로웠던 실종자 신고 및 조회, 이젠 쉽고 간편하게

<br>

 ## 💡 Motivation of this project
 우리나라의 실종 아동 문제는 여전히 해결되지 않고 있으며, 연간 2만명의 실종자들에 대한 실종 접수가 들어오고 있습니다. 또, 지난 20년 간 장기 실종자는 수천명에 달합니다. 하지만 이러한 상황 속에서 실종자들에 대한 정보는 여전히 **종이 전단지 부착**이라는 비교적 시대에 뒤떨어진 방법으로 공유되고 있습니다. 현재 시간이 지날수록 실종자들에 대한 관심이 떨어지고 있는데, 저희 팀은 이러한 문제점을 실종자들에 대한 이슈를 오프라인에서 온라인으로 옮김으로써 해결할 수 있다고 생각했고, 그 결과 **실종자 온라인 제보 서비스**를 기획하게 되었습니다.
 
<br>

## 📑 Features of this project
 ### ⚙ It Provides:
* 실종자 정보를 [경찰청 안전Dream](www.safe182.go.kr)에서 Open API로 받아옵니다.
* Open API로 받아온 실종자 정보를 모바일 앱에서 조회할 수 있습니다.
* 경찰청에 등록된 실종자 발견시, 앱에서 바로 실종자 발견 제보를 할 수 있습니다.
* 제보된 실종자 발견 신고 내용은 서비스의 어드민 웹페이지에서 확인할 수 있습니다.
* 신규 실종자 발생 시, 앱에서 바로 신고하여 Open API를 통해 실제 경찰청에 실종자 신고를 할 수 있습니다.
* 🔎<https://missingChild.pythonanywhere.com> 통하여 발견접수된 실종자 리스트를 확인 가능합니다.

<br>

## 📲 How to Setup?
### 📱 [Mobile Client](https://github.com/oss-talkative/missing-mobile)

<br>

> You need to install Flutter on your environment before following next step. Please check [here](https://docs.flutter.dev/get-started/install?gclid=CjwKCAiA7IGcBhA8EiwAFfUDsSTBw2Tu7vlZbIAG_2OyUPzx4zBuucfDD9OMNvNJL7JsJ89eYtkcDxoCem4QAvD_BwE&gclsrc=aw.ds) to install Flutter.

### 1. Git clone
```shell
git clone https://github.com/oss-talkative/missing-mobile
```

### 2. Fetch flutter dependencies
```shell
flutter pub get
flutter pub upgrade
```

### 3. Launch application
```shell
# debug mode
flutter run

# release mode
flutter run --release
```

<br>

### ☁️ [Back-End Server](https://github.com/oss-talkative/missing-backend-re)
> You need to install [python3.10](https://www.python.org/downloads/release/python-3100/) and [git](https://git-scm.com/) on your environment before following next step.
### 1. Git clone
```shell
git clone https://github.com/oss-talkative/missing-backend-re
```
### 2. Open project & create virtual environment
> open project and terminal(git bash)
for Window os
```shell
python -m venv <name of virtual environment>
source <name of virtual environment>/Scripts/Activate
for Window mac
```shell
python -m venv <name of virtual environment>
source <name of virtual environment>/Scripts/Activate
```
### 3. migrate for DB
```shell
cd myproject
cd myproject
python manage.py makemigrations
python manage.py migrate
```
### 3. run server
```shell
python manage.py runserver
```
### 4. go into the local web
> Enter `http://localhost:8000/` into your web browser

<br>

### 🌐 [Web Front-End](https://github.com/oss-talkative/missing-web)

<br>

> Install react [here](https://reactjs-kr.firebaseapp.com/docs/installation.html)

### 1. Git clone
```shell
git clone https://github.com/oss-talkative/missing-web
```
### 2. Open web page
```shell
npm start
```

<br>


## 🛠 Technology stacks

### Mobile Client
- Dart
- Flutter
- Figma for design

### Back-End Server
- Python
- Django
- SQLite
- Pythonanywhere for distribution

### Web Front-End
- Javascript
- React

<br>

## 🧑‍💻 Project Members
 
 <div align="center">


### 🌫️ 말 많은 하늘과 같은 사람들 🌫️
  
 |<img src="https://avatars.githubusercontent.com/u/72238126?v=4" width="80">|<img src="https://avatars.githubusercontent.com/u/65147869?v=4" width="80">|<img src="https://avatars.githubusercontent.com/u/95032287?v=4" width="80">|<img src="https://avatars.githubusercontent.com/u/112372174?v=4" width="80">|
|:---:|:---:|:---:|:---:|
|[Yeojun Yoon](https://github.com/yjyoon-dev)|[푸른곰프앙이](https://github.com/kseenyoung)|[JeongYun Kim](https://github.com/pipi-shortstocking)|[yunasin](https://github.com/star1502)|
|**Team Leader**<br>Mobile Client|Back-end|Front-end Web|Mobile Client / Design|
  
 </div>
 
 <br>
 
 ## 🧾 License
  This project is licensed under the terms of the MIT license.
