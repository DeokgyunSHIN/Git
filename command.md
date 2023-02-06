# Git 명령어 

### Git  초기화 및 삭제 

Git 초기화 

> 명령어 : git init 
> 
> 초기화 할 대상 폴더에서 명령어(git init) 입력 
> 
> Git 초기화 시 폴더 안에 숨기 폴더로 .git폴더 생성(Local Config 등으로 구성)

Git 삭제

> 단순히 .git 폴더를 삭제 
> 
> mac의 경우 폴더를 삭제하는 명령어 입력 : rm -rf.git


정리 - Git 초기화는 해당 폴더 안에 들어가는 파일, 소스 등등을 Git으로 관리하겠다고 선언하는것이다.

  Git 삭제는 단순하게 Git을 삭제한다. 라는 뜻을 가지고 있다.
  
 
 ### 실습 
 
<img width="372" alt="스크린샷 2023-02-06 오후 7 24 07" src="https://user-images.githubusercontent.com/104719555/216947930-3e0e3844-fbc9-413f-a616-388f09c3f904.png">

위의 사진을 보면 무제폴더라고 ls -al을 검색하게되면 아무런 파일이 없는것을 확인할수 있다. 

여기서 gin init의 명령어를 치고 난뒤 ls -al로 다시 파일 내부를 보게 되면 

<img width="590" alt="스크린샷 2023-02-06 오후 7 24 19" src="https://user-images.githubusercontent.com/104719555/216948174-bdf15968-738e-4c58-b5c2-4ccf063d7820.png">

.git 폴더가 생겨진것을 확인 할수 있다.

<img width="413" alt="스크린샷 2023-02-06 오후 7 37 09" src="https://user-images.githubusercontent.com/104719555/216951731-cd4ad3e7-4a4f-4b50-929f-a5525bd33ff9.png">

.git 내부 파일의 모습이고 지우기 위해서 다시 cd .. 의 명령어를 한 다음 git 삭제 명령어를 해주면 

<img width="429" alt="스크린샷 2023-02-06 오후 7 44 05" src="https://user-images.githubusercontent.com/104719555/216951908-7606ee37-9253-4d83-8f89-fdf86b06c993.png">

위의 사진 처럼 지워지는것을 볼수 있따.
