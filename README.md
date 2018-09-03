# kopo2018
한국폴리텍대학 JSP 프로그래밍 수업을 위한 Git repository 입니다.

# step 1. Git 회원가입.
github 홈페이지에 회원가입을 합니다.
학생계정(***.ac.kr)의 경우 private 기능을 무료로 사용할 수 있기 때문에
학생계정으로 가입을 추천드립니다.
(학생계정으로 회원가입 방법 링크 : http://upglay.tistory.com/11)

# step 2. ssh key 생성 및 등록
회원가입 후 git을 사용 할 PC에 key 생성 및 github key를 등록하여
로그인 없이 등록된 PC ssh key를 통해 github와 연동 가능 합니다.

key 생성방법
 1. windows key + R
 2. cmd 엔터
 3. command 입력 : ssh-keygen -t rsa -C "이메일주소"
 
이렇게 등록된 키는 %USERPROFILE%\\.ssh 경로에 파일로 생성됩니다.
키 등록은
  1. github 로그인
  2. 우측 상단 자신의 정보를 수정할 수 있는 아이콘 클릭
  3. settings 클릭
  4. ssh & gpg keys 클릭
  5. new ssh key 클릭
  6. 등록할 key의 이름과 key를 등록 해 주면 됩니다.
   여기서 등록되는 키는 전 스텝에서 만든 key를 등록 해 주면 됩니다.
   %USERPROFILE%\\.ssh\\id_rsa.pub 을 메모장으로 연 후 안에 있는 text를 모두 복사하여 붙여 넣습니다.
   
이렇게 키를 등록하면 해당 pc는 자신이 연결한 git과 연동되어 사용 가능해 집니다.

# git repository 신청
텔레그램으로 자신이 github에 가입한 이메일을 공유해 주시면 권한을 드릴것입니다.
