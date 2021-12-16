### 유레카 프로젝트

# 0. Build 과정

1. **Github계정 & 원격/로컬 Repository 생성하기**
2. **Jekyll 설치하기**
3. **테마 입히기**
4. **테마와 Post 수정하기**
5. **favicon 수정하기**
6. **댓글 기능 추가하기**

---

# 1. Github계정 & 원격/로컬 Repository 생성하기

Github Page를 만들어야하기 때문에 Repository name을
<username.github.io>로 지정해 Repository를 하나 생성

git clone 명령어를 통해 원격저장소와 로컬저장소 연결


# 2. Jekyll 설치하기
리눅스용 루비 + 개발자킷(DevKit) 설치 프로그램을 다운로드 후 설치 루비 설치가 정상적으로 완료되면, Start Command Prompt with Ruby를 실행

gem install jekyll bundler 를 입력해 패키지 설치
jekyll -v 를 입력해 jekyll이 잘 설치되었는지 확인
자신의 블로그 디렉토리로 이동
jekyll new . 를 입력해 현재 디렉토리 내부에 블로그 파일 생성
jekyll serve 를 입력해 지킬 실행

위의 과정을 통해 Jekyll 환경을 구성함


# 3. 테마 입히기
http://jekyllthemes.org/

https://jekyllthemes.io/free

수업 notion의 두 사이트에서 마음에 드는 테마 선택
테마 링크로 이동해 ZIP으로 다운


# 4. 테마와 Post 수정하기
_config.yml의 title 을 수정함으로써 페이지의 제목을 바꿈

_includes 폴더의 header 파일에서 불필요한 header는 없애고 내 github로 교체

각 post 파일에 html 형식으로 글 작성

작성한 post 파일들을 _post 폴더에 넣음


# 5. favicon 수정하기
favicon이란? 즐겨찾기(favorites)와 아이콘(icon)의 합성어로, 주소창에 조그맣게 표시되는 아이콘
