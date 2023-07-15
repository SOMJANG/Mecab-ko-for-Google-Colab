# Mecab-ko-for-GoogleColab

![Colab에서 Mecab-ko-dic 설치를 쉽게 도와주는 Shell-Script입니다.](/images/intro.png "Optional title")

### Colab에서 Mecab-ko-dic를 쉽게 설치할 수 있도록 도와주는 Shell-Script입니다.
### 영구적인 설치가 아닙니다.
### 새 노트(새로운 런타임)를 사용할때마 새로 설치해주어야합니다.

### 은전한닢 프로젝트 : https://bitbucket.org/eunjeon/mecab-ko-dic/src/master/

### 📚 Colab에서 Mecab-ko-dic 사용자 사전 추가 방법 : [상세설명 바로가기](https://somjang.tistory.com/entry/Google-Colab%EC%97%90%EC%84%9C-mecab-ko-dic-%EC%82%AC%EC%9A%A9%EC%9E%90-%EC%82%AC%EC%A0%84-%EC%B6%94%EA%B0%80%ED%95%98%EA%B8%B0-2023%EB%85%84-%EC%97%85%EB%8D%B0%EC%9D%B4%ED%8A%B8-%EB%B2%84%EC%A0%84) 📚 

### 업데이트 기록
- 👏 2021년 1월 19일 Dogdriip님께서 불필요한 제거 업데이트, 설치작업 과정을 제외한 light 버전 추가 👍
- 🐛 2022년 1월 11일 combacsa님께서 NameError: name 'Tagger' is not defined 문제 해결 👍
- 🎩 2022년 4월 29일 mecab-python 추가 설치하여 NameError: name 'Tagger' is not defined 문제 해결
- ✨ 2023년 7월 15일 사용 방법 업데이트

## 1. 설치되는 Mecab-ko-dic 버전
> mecab-0.996-ko-0.9.2<br>
> mecab-ko-dic-2.1.1-20180720

## 2. 사용법
#### 1. 초록색 #### 1. 초록색 <> Code 버튼을 클릭후 HTTPS 에 적혀있는 주소를 복사합니다.
![git clone](/images/copyurl-new.png "Optional title")


#### 2. 복사한 주소와 git clone 명령어를 활용하여 Colab notebook에서 다운로드 받습니다.
```Bash
!git clone https://github.com/SOMJANG/Mecab-ko-for-Google-Colab.git
```
![git clone](/images/gitclone.png "Optional title")


#### 3. Mecab-ko-for-Google-Colab  directory로 이동합니다.
```Bash
cd Mecab-ko-for-Google-Colab
```
![cd](/images/cd.png "Optional title")


#### 4. bash 명령어를 활용하여 실행
```Bash
!bash install_mecab-ko_on_colab_light_220429.sh
```
![install](/images/install_1.png "Optional title")
![install](/images/install_2.png "Optional title")


#### 5. 설치가 완료되었다면 아래의 새로 셀을 만들어 아래의 코드를 입력하여 사용합니다.
```
from konlpy.tag import Mecab
mecab = Mecab()
```
![install](/images/last.png "Optional title")

#### 6. nouns, morphs와 같은 다양한 형태소 분석 method를 사용할 수 있습니다.


