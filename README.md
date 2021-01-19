# Mecab-ko-for-GoogleColab

![Colab에서 Mecab-ko-dic 설치를 쉽게 도와주는 Shell-Script입니다.](/images/intro.png "Optional title")

### Colab에서 Mecab-ko-dic를 쉽게 설치할 수 있도록 도와주는 Shell-Script입니다.
### 영구적인 설치가 아닙니다.
### 새 노트(새로운 런타임)를 사용할때마 새로 설치해주어야합니다.

### 은전한닢 프로젝트 : https://bitbucket.org/eunjeon/mecab-ko-dic/src/master/

### 📚 Colab에서 Mecab-ko-dic 사용자 사전 추가 방법 : https://bit.ly/3k0ZH53 📚 
### 👏 2021년 1월 19일 Dogdriip님께서 불필요한 제거 업데이트, 설치작업 과정을 제외한 light 버전 추가 👍

## 1. 설치되는 Mecab-ko-dic 버전
> mecab-0.996-ko-0.9.2

> mecab-ko-dic-2.1.1-20180720

## 2. 사용법
1. 초록색 Clone or download버튼을 눌러 주소를 복사합니다.
![git clone](/images/copyurl.png "Optional title")


2. ! git clone https://github.com/SOMJANG/Mecab-ko-for-Google-Colab.git 명령어를 통하여 저장소를 복사해옵니다.
![git clone](/images/gitclone.png "Optional title")


3. cd Mecab-ko-for-Google-Colab 하여 Mecab-ko-for-Google-Colab  directory로 이동합니다.
![cd](/images/cd.png "Optional title")


4. ! bash install_mecab-ko_on_colab190912.sh 명령어로 실행합니다.
![install](/images/install_1.png "Optional title")
![install](/images/install_2.png "Optional title")


5. 설치가 완료되었다면 아래의 새로 셀을 만들어 아래의 코드를 입력하여 사용합니다.

6. from konlpy.tag import Mecab

7. mecab = Mecab()
![install](/images/last.png "Optional title")

8. nouns, morphs와 같은 다양한 형태소 분석 method를 사용할 수 있습니다.


