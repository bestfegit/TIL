# 헤딩

\# - 헤딩 제목

\# 갯수 - 글자 크기



* 리스트 쓰기

\ 백슬래시는 명령어가 아닌 문자로 바꿔줌

1. 첫번째
2. 두번째
3. 세번째



/-,/* 는 글자 앞에 점을 찍어줌

* 이렇게 글자 앞에 점

쉬프트+탭 은 들여쓰기 탈출!



```code block```

\``` 3개 코드 블럭

`code block`

\` 1개도 코드 블럭



[]() 인터넷 링크 제목과 주소



* 이미지 그냥 사이트에서 끌고와도 됨



**굵게** bold **

*기울* italic * 

~~취소~~ cancleln -- 물결표시

----

-- 선긋기



표그리기

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |



----



# Unix/Linux 명령어

* 현재위치의 폴더, 파일 목록보기 : ls
* 길 위치로 이동하기 cd <path>
* cd .. : 상위 폴더로 이동
* cd. : 현재 위치로 이동
* 폴더 생성 :  mkdir <name> 
* 파일 생성 :  touch <name>
* 삭제 rm <name>
* 폴더 삭제 rm -r <name>
* 깨끗한 화면 clear

-----

# Git 기본기

### Repsitory 

* git init 명령어로 로컬 저장소 생성

* .git 디렉토리에 버전관리에 필요한 모든 것이 들어있다.

* git status 현재 상태확인

* git add 뒤에 나오는 파일을 스테이징 에어리어로 올림

* git add . '.'은 현재 위치를 말함 <- 한칸 띄우고 . 찍기 - 현재 폴더 내 모든 파일을 스테이징 에어리어에 올림

* git commit -m "commit_message" 스테이지 올린거만 됨 : -m 은 메시지를 보내겠다는 뜻, 최대한 자세하게 적어줘야 무슨 작업을 한 파일인지 알수있음 ex 로그인 구현, 패스워드 구현

* git log 모든 커밋 출력

* git diff 두개의 커밋간의 차이를 보여줌

* git remote add origin {}  주소

* git push -u origin master 브랜치? 오리진 뒤부터는 생략가능

* git clone {} : 리모트의 것을 local로 복사

* git pull origin master : 리모트의 최신 커밋을 로컬로 땡겨옴

  -evertying up to date = 이미 최신화다 더 못 푸시한다

1 Working Directory - git으로부터 감시받지않는 상태

2 Staging Area - git added 하여 이 파일 버전을 무대 위로 올리기 / 관리할거라고 선언하는 것

3 Repository - 깃 commit을 해주고 Repository에 넣어줌



깃헙을 remote repository 라 함

깃헙과 로컬과 연결





# 단축키

* 윈도우키 쉬프트 s 키  드래그앤 스크린샷



# TIL

Today I Leaning

내가 성장할 수 있는 사람이다라는  하나의 지표

계속 꾸준히 하는게 중요

깃헙에 자꾸 하루에 하나 올려서 잔디를 채움

잔디밭 관리



























