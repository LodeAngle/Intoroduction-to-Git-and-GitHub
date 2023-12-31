# Introduction to Git&GitHub 
***
# 1. Git&GitHub 이용 목적
- 버전 컨트롤
- 과제 제출
- 코드 리뷰

## 1.1 버전(version)이란?
1. 원하는 시점(point in time)으로 이동 할 수 있게 해주는 것 → 버전
2. 메타데이터(metadata, 데이터를 설명해 주는 데이터) 
  - 파일 작성자(The author of the file)
  - 저장 위치(Where it is located)
  - 파일 형식(The file type)
  - 저장 시점(When it was last saved) 
<p align="center">
<img src="https://www.hanbit.co.kr/data/editor/20230512160223_whmadsed.png" width="70%" height="70%" alt="버전관리란?"> 
<br />
버전 관리란? (출처:hanbit.co.kr)  
  
3. 협업 프로젝트에서는 버전 관리가 특히 중요!
4. 버전 관리란?
  - 변경 사항 관리 → 변경 사항 기록/추적 
  - 동시 파일 개발 → 다른 버전 파일 결합  
  - 특전 버전 식별
  - 변경 사항 되돌리기 
<p align="center">
<img src="https://blog.kakaocdn.net/dn/8Fh1Y/btqzjg2OQx6/2ge5VZ8AV3O8H7niW0YW8K/img.png" width="400" height="300" alt="카카톡 예시">
<br />
카카오톡 버전 히스토리 (출처:https://tip-blog.tistory.com)  

## 1.2 Git과 GitHub란?
1. Git과 GitHub란?
  - Git(깃)은 **버전 관리 시스템**이고, GitHub(깃허브)는 Git으로 관리하는 **프로젝트를 업로드 및 다운로드 할 수 있는 사이트**
3. Git은
  - 일반적으로 사용되는 버전 관리 프로그램
  - 컴퓨터 프로그래밍 및 데이터 프로젝트
  - 오픈 소스
3. Git은 GitHub가 아니지만 일반적으로 Git은 GitHub와 함께 사용 됨
4. Git 호스팅 사이트: GitHub.com
<Br />

## 1.3 Git의 장점   
1. GitHub에 소스 코드를 올려 두면 시간, 공간의 제약 없이 협업할 수 있음
  - 다른 사람 컴퓨터와 동기화 가능
2. 프로젝트를 공개 저장소로 만들면 전 세계 개발자와 협업할 수 있음
3. 공개 저장소에 저장(오픈 소스)해 두면 파일을 잃어버리지 않음
4. 깃 없는 세상?
  - 변경 내역 확인이 어려움
  - 버전을 되돌리기 어려움
  - 협업이 어려움

<p align="center">
<img src="https://i0.wp.com/leechoong.com/wp-content/uploads/2017/12/101-6.png?w=618" width="300" height="150" alt="버전관리 중요성 설명용">
<br />
버전 관리의 중요성 (출처:http://leechoong.com/posts/2017/git_vcs/)

# 2. Git 시작하기 
## 2.1 Git 설치하기
- Git 설치 주소 [Link](https://git-scm.com) 
- Git 설치부터 설치 확인하기까지 참고 [Link](https://allhpy35.tistory.com/38)   

## 2.2 Git 초기설정
- "이름"과 "이메일"설정 [Link](https://articles09.tistory.com/48)  

# 3. Git 처리구조
1. Git은 4개의 주요 공간으로 구성되어 있음
<p align="center">
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbwH6Ln%2Fbtq3z4NgrB1%2F6DfZ5X5s3doQjxRo3kHeN1%2Fimg.png"  width="600" height="350" alt="Git 처리 구조">
<br />
Git의 처리 구조 (출처:https://jforj.tistory.com/119)  

2. 용어 설명(수정 전) 
- Working Directory: 개발자의 현재 시점으로 소스코드를 수정하며 개발하는 공간을 의미
- Staging Area: Working Directory에서 작업한 파일을 Local Repository에 전달하기 위해 파일들을 분류하는 공간 
- Local Repository: 로컬 저장소이며 작업한 파일들을 저장해두는 내부 저장소 (.git 폴더)
- Remote Repository: 원격 저장소이며 인터넷으로 연결되어 있어 있는 외부 저장소 (웹 페이지에서 보이는 공간)
- Branch: Remote Repository의 현재 상태를 복사하여 master 브랜치와 별개의 작업을 진행할 수 있는 공간 (보통 브랜치를 생성하여 개발을 진행하고 개발을 완료하면 master 브랜치에 병합하여 개발 완료된 소스코드를 합침)
- Head: 현재 작업중인 브랜치의 최근 커밋된 위치
- Index: Staging Area를 의미

# 3. GitHub 시작하기
## 3.1 깃허브 호개 
- 깃허브는? 개발자의 SNS
- GitHub는 원격에서 Git 저장소를 호스팅해주시는 서비스
- 로컬 컴퓨터에 있는 소스를 1) 백업 2) 협업 3) 공유하기 위해서는 github 사용이 필수
  
## 3.2 깃허브 가입하기
- 깃허브 가입하기 [Link](https://goddaehee.tistory.com/218)
- 학생인증 [Link](https://goddaehee.tistory.com/219)

## 3.3 깃허브 살펴보기
- 스타 개발자의 깃허브 탐방하기~!
    - 깃의 창시자 리누스 토르발스 계정은? https://github.com/torvalds
    - 이번에는 검색창에 'tensorflow'를 쳐보세요~
    - 깃허브에서 'Star'는 SNS에 '좋아요'와 같습니다.
- 나만의 프로필을 꾸미고 싶다면, 우측 상단 동그란 아이콘을 클릭하고 Settings-Profile 메뉴에 들어가 보세요.
- README.md는 해당 프로젝트의 설치 방법, 사용 방법 등을 담고있습니다.
- Issues로 오류 제보 또는 기능 제안을 할 수 있습니다. 
## 3.4 저장소 만들기
- 회원가입 후 Create repository를 누르면 아래와 같이 나타남.
<p align="center">
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FqwmAj%2FbtrsVKhfIHx%2F8kuvj9ZUEcWTbEcpApssr0%2Fimg.jpg"  width="40%" height="40%" alt="새 원격 저장소 만들기">

  - Repository name : 저장소의 이름
  - Description : 해당 저장소의 설명글 작성(선택)
  - Public / Private : 공용/개인 저장소 선택. 우리는 Public 사용
  - Initialize this repository with : 저장소 생성 과정에서 자동으로 생성시킬 파일 선택
  - README : 저장소 내용을 소개하는 파일.
  - .gitignore : Git 저장소 작업 시 무시하고 싶은 특정 이름/파일 등
  - license : 저장소의 라이센스 파일을 추가
  - Create repository를 누르면 새 저장소 생김
  
# 4. 명령어로 깃 다루기 
---
명령어 모음
- git init: 로컬 저장소 만들기
- git status: 작업 디렉터리 상태 확인하기
- git add: 스테이지에 올리기
- git commit: 커밋하기
- git log: 커밋 조회하기
- git tag: 태그 추가/조회/삭제하기
---
## 4.1 깃 개념
- 깃 동작 개념 [Link](https://wikidocs.net/149672)
- 브랜치 개념 [Link](https://wikidocs.net/153114)

## 4.2 git init: 로컬 저장소 만들기
- 작업 디렉토리 생성 및 이동
    - 방법 1: 작업 디렉터리를 생성 후 해당 경로에서 마우스 오른쪽 버튼을 클릭한 후 Git Bash Here를 클릭하여 깃 배시를 연다.
    - 방법 2: 시작 메뉴에서 Git Bash를 실행한 뒤 cd <경로> 명령으로 원하는 경로로 이동한다.
- git init를 입력한다.
    - "Initialized empty Git repository in <작업 디렉토리 경로>"라는 메시지가 뜨면 성공!
    - 작업 디렉토리에 .git 폴더가 생겼다면? 성공!  </br>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/ad232972-9830-400c-9492-0d2fd36b5d8c)

## 4.3 git status: 작업 폴더 상태 확인하기
- git status는 현재 작업 디렉터리의 상태를 알려준다.
- 따라하기!
    - 작업 디렉토리에 a.txt 파일을 생성한다.
    - a.txt를 열어 A입력 후 Enter(줄바꿈) 및 저장한다.
    - git bash에 git status를 입력하면, 아래와 같은 결과가 나온다. </br>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/9a05606f-7b7b-4a48-9b23-7bbf90258a2c)
        - On branch master: 현재 master 브랜치에 있다는 의미
        - No commits Yet: 현재 커밋을 하지 않았음
        - Untracked files: 변경 사항을 추적하지 않은 대상. 즉, 여기에 a.txt가 표시된 것은 a.txt가 기존에 버전을 관리한 적 없는 새로운 파일이 생성 되었음을 의미함.
## 4.4 git add: 스테이지에 올리기 
- a.txt 파일을 스테이지에 추가해보자.
    - git add <스테이지에 추가할 대상> → git add a.txt
    - 다시 git status 명령어를 입력해본다. <br/>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/88660fad-0193-4112-bd16-3d98c54a6651) <br/>
    - Change to be committed: 항목에 a.txt가 추가 된 것을 확인할 수 있음.
    - Tip! 스테이지에 올릴 대상이 여러개라면 git add . 명령어로 현재 디렉터리(작업 디렉터리)에 있는 모든 파일을 스테이지에 업로드 할 수 있음.
## 4.5 git commit: 커밋하기
- 스테이지에 변경 사항을 추가했다면 마지막으로 커밋만 하면 됨!
- 새로운 버전을 만드는 명령어는 git commit -m "커밋 메시지" 또는 git commit --message "커밋 메시지" 명령어를 입력한다.
    - 커밋 메시지는 메모, 주석 과 같은 것! 꼭 알아볼 수 있게 적어야 함!
- 따라하기!
    - git commit -m "First commit" 을 입력한다. </br>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/a2b39fd5-1c94-4be7-a77c-6409673150f4)
    - git log를 입력하면 해시, 만든사람, 커밋이 만들어진 날짜, 메시지가 출력 됨. </br>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/0eab5fab-eab5-41e2-a4b1-636048a7dc22)
    -  a.txt 파일을 열어 A 다음 줄에 B를 추가한다.</br>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/58c203f2-63a2-43ae-beb9-82fe55f93402)
    -  git status 로 상태를 확인하면 'modified: a.txt'라고 수정 된 파일이 나타 난다.
    -  다시 새 버전을 만들기 위해 git commit -am "second commit" 을 입력한다.
    -  git log를 입력해보면 두번째 커밋도 성공한 것을 확인할 수 있다.
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/841420e1-2219-4dfb-9ba0-3165be445d21)

- Tip! add와 comit을 합쳐서 git commit -am "커밋 메시지"로 사용할 수 있음.  
- 저장소 만들기부터 Push하기까지 [Link](https://leeporter.tistory.com/41)
## 4.6 git log: 조회하기
- git log --oneline: 요약 보기
- git log -p: 변경사항 보기 
- git log --graph: 커밋을 그래프 형태로 보기
- git log --branches: 모든 브랜치의 커밋을 조회
## 4.7 git tag <태그>: 태그 추가하기
- 두 번째 커밋에 v.1.0.0이라는 태그를 붙히려면?
- git tag <태그>는 HEAD(현재 브런치의 최신 커밋)가 가리키는 커밋에 태그를 붙이는 명령어
- git tag v1.0.0 → 커밋을 조회하면 태그가 붙은 것을 확인할 수 있다.
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/fa70dccc-70af-4f04-9ad8-e77411ad651a)
- 특정 커밋에 태그를 붙이고 싶다면 git tag <태그> <커밋>
- <커밋>은 git log 또는 git log --oneline 명령어에 해서 태그로 확인 가능하다.
- git tag v0.0.1 <첫 번째 커밋> 하면 첫 번째 커밋에도 태그가 추가 된 것을 확인 가능하다.
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/3881737a-098e-4b1f-ae3c-d3842edb6fb6)
- git tag -l: 태그 조회하기
- git tag -d <태그>: 태그 삭제하기

## 4.8 그 외 자주 쓰이는 명령어
- git diff: 최근 커밋과 작업 디렉터리의 차이를 출력
- git diff --staged: 최근 커밋과 스테이지의 차이를 출력
- git diff <커밋> <커밋>: 커밋끼리 비교
- git diff <브랜치> <브랜치>: 브랜치끼리 비교
- git reset <커밋>: 해당 <커밋>으로 돌아가기
- git revert <커밋>: 해당 <커밋>이 취소된 새로운 커밋 생성
- git stash: 변경사항 임시 저장
- git stash list: 임시 저장한 내역 조회
- git branch <브랜치>: 브랜치 나누기
- git checkout <브랜치>: 체크아웃하기
- git merge <브랜치>: 브랜치 병합하기
- git rebase <브랜치>: 브랜치 재배치하기
- 더 이상의 자세한 설명은 생략... 스스로 공부하자...

## 4.9 참고자료
- [Link](https://subicura.com/git/guide/basic.html)
- [Link](https://gorokke.tistory.com/22)

# 5. 명령어로 깃허브 다루기
--- 
- 용어정리
    - 클론(clone): 원격 저장소를 복제하기
    - 리모트(remote): 원격 저장소를 추가/조회/삭제하기
    - 푸쉬(push): 원격 저장소에 밀어넣기
    - 패치(fetch): 원격 저장소를 가져만 오기
    - 풀(pull): 원격 저장소를 가져와서 합치기
---
## SSH 설정
- ssh-keygen: SSH Key 생성하기
    - 엔터만 눌러서 키를 생성!
    - Created directory '주소'에 가면 id_rsa(비공개 키), id_rsa.pub(공개키)가 있음.
- 깃허브 → Setting → SSH and GPG key → New SSH key [Link](https://github.com/settings/keys)
- git에 cat ~/.ssh/id_rsa.pub 를 입력하면 복사해 올 SSH key가 나온다. 이것을 복사해서 New SSH key에 입력하자.

## 5.1 git clone: 원격 저장소를 로컬 저장소로 복제하기
- git clone <원격 저장소 인터넷 주소>
- ls: 다운로드된 폴더 및 저장소와 연결 확인

## 5.2 git remote: 로컬 저장소-원격 저장소 연결하기
- git remote -v: 현재 연결 되어있는 원격 저장소 확인. 아직 연결하지 않았다면 아무것도 나타나지 않음
- git remote add <name> <url>: 원격 저장소 추가
    - <url> 확인하는 방법 <br/>
![image](https://github.com/LodeAngle/Intoroduction-to-Git-and-GitHub/assets/141135651/31b65749-5386-406d-9081-70fba3d8a84c)
<br/>
- git remote remove <name>: 원격 저장소 연결 끊기
- git remote rename <기존 원격 저장소 이름> <바꿀 원격 저장소 이름>

## 5.3 git push: 원격 저장소에 밀어넣기
- 따라하기!
    - 로컬 저장소 'test-repo'를 만든 뒤 문자 A가 적힌 a.txt파일을 생성 및 저장
        - 만들 줄 모르면 위에서부터 다시 정독...
    - 추가 된 파일을 first commit 이라는 커밋 메시지로 커밋!
        - 현재 상황은 '로컬 저장소 1커밋' '원격 저장소 0커밋'
    - 명령어로 푸쉬 하는 방법! 그대로 따라하기!
        - git remote add origin <주소>
            - <주소>를 origin 이라는 이름으로 추가! 
        - git branch -M main
            - git brance -M <브랜치 이름>은 현재 브랜치 이름을 <브랜치 이름>으로 바꾸는 명령어! 기존 브랜치 이름(master)를 main으로 바꿈! 과제 제출시 브랜치 이름을 적합하게 바꾸어서 내시오!
        - git push -u origin main
            - git push <원격 저장소 이름> <브랜치 이름>은 원격 저장소 이름으로 브랜치 이름을 푸쉬 하는 명령어! -u는 처음 푸쉬할 때만 사용하면 됨.

## 5.4 풀 리퀘스트 보내기!
- 풀 리퀘스트(pull request)란? 협업하는 상대에게 자신이 작성한 결과물을 보내는 것!
- 풀 리퀘스트 순서
    - 기여하려 계정으로 포크하기
    - 포크한 저장소를 클론하기
    - 브랜치 생성 후 생성한 브랜치에서 작업하기
    - 작업한 브랜치 푸쉬하기
    - 풀 리퀘스트 보내기
    - 참고자료 [Link](https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/)

# 6. 과제 제출 방법
> 과제는 기한까지 새 branch를 파서 Pull Request (PR)로 제출하는 것을 원칙으로 한다.
> 과제 제출은
1. 자신의 이름으로 된 repository를 clone 받기
2. 새 branch를 파서 개발하고 pull request 날리기 (브랜치 이름은 과제 번호와 이름-학번으로 구성, 예시) project1-sungju-park-22000020)
3. commit message를 아무렇게나 기술하지 않고, 브랜치 이름으로 commit 하기
