# Git 사용자 설정 및 세팅 

로컬에서 사용할 Git 사용자 이메일과 이름을 설정 

git config -> Git에 관한 설정을 추가, 변경, 삭제하는 명령어 이다.

설정파일 -System설정 파일/ Global 설정 파일 / 로컬 설정 파일 

```
  System 설정 파일 -> 모든 시스템 사용자에게 적용 (git config -- system)
  
  Global 설정 파일 -> 한 사용자의 전치 Git Repository에 적용 (git config --global)
  
  Local 설정 파일 -> 하나의 Repository에만 적용 (git config --local)
```


1. Global Git 사용자 설정 
```
 git config --global user.email "이메일 주소" ;

 git config --global user.name"이름";
```
<img width="799" alt="스크린샷 2023-02-06 오후 6 59 58" src="https://user-images.githubusercontent.com/104719555/216942237-e8a07dec-9101-4d5c-875c-2450f257892b.png">

위의 사진처럼 이메일과 이름을 적어준다. 여기서 엔터를 치면 올바르게 적었는지 알수가 없기 떄문에 확인을 해준다.

2.설정 확인 
```
 git config --list
```

<img width="367" alt="스크린샷 2023-02-06 오후 7 01 59" src="https://user-images.githubusercontent.com/104719555/216942778-532e367e-425e-4f8c-80fe-da9d24eb5216.png">

위의 사진처럼 명령어를 적게되면 내가 등록한 정보를 알수있다.

3. Github 계정에 ssh key 등록하기 

https://git-scm.com/book/ko/v2/Git-%EC%84%9C%EB%B2%84-SSH-%EA%B3%B5%EA%B0%9C%ED%82%A4-%EB%A7%8C%EB%93%A4%EA%B8%B0

4. Github 접속 후 오른쪽 상단 프로필 클릭 Setting -> SSH and GPg Keys

5. New SSH Key 클릭해 Title과 복사한 Key 입력 후 Add SSH Key 클릭 
