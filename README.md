# github_connect💙💙💙

## 💙1. [깃설치] (https://git-scm.com/download/win)

      git을 통해서 github과 연결할수 있다.
 
 
 
 -깃에 올려야할 폴더에 가서 shift + 우클릭하여 PowerShell 창열기
      
    git init
      
      
 - .git폴더가 생성됨
------------------------------


## 💙2. 깃 설치후 Git bash 열기
🖼️![Untitled-2](https://user-images.githubusercontent.com/129016976/235417891-8242a9ee-a840-449b-9bfe-513851afea10.jpg) 🖼️

* 유저이름 설정

      git config --global user.name "KMJ"
      
* 유저 이메일 설정하기(반드시 github에 가입했던 이메일 주소와 동일해야함)
     
      git config --global user.email "rhalswjd7109@naver.com"



##  ⬆️   위의 연결은 해당컴퓨터에서 한번만 실행하면 됨
----------------------------------------------------------

# github에 코드 업로드하기
  
  * 초기화
     
     git init
  * 추가할 파일 (폴더안에 내용을 모두 올림)
     
     git add . (한칸띄우고 점쓰기 .점은 모든 파일을 의미)
  * 히스토리 만들기(-m 은 메세지를 의미함 ""안에는 히스토리이름을 적음)
      
      git commit -m "first commit(제목)" ex)"작업시작"
  * Github의 repository를 만들고 그주소와 연결하기
     
     git remote add origin https://github.com/1004minjeong/css_flex.git
  * 연결이 잘되 었는지 확인하기(사용안해도됨)
  
     git remote -v 
  * Github에 올리기
      git push origin master 


----------------------------------------------
##   수정하여 다시 업로드할때

1. 기존의 코드를 다운벋는 행위를 해야한다.
  
          git pull origin master
  
2. 다시 push 해야한다.
 
          git push origin master
          
    
    
    
    ---------------------------------------------------
    # Github 협업하는방법
    
    # 사원입장--------------------------------
    1. 소스코드 다운로드
    git clone 주소 (code 누르고 Https주소복사)
    git clone https://github.com/1004minjeong/HANACARD.git
    
    2. 브랜치(branch)만들기(checkout에 "따옴표 안써도되용)
    git checkout -b(브랜치이름)
    git checkout -b KO
     
     git add.
     
     git commit -m "하나카드"
     
     git push origin 브랜치
     git push origin KO (checkout 했을때이름쓰기 이것도 "따옴표 없이)
     
     ![image](https://github.com/1004minjeong/github_connect/assets/129016976/2362742d-1d72-40da-8f90-f0fe56688b3c)
     정상처리되면 compare & pull request

