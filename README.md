# ml-project-3



# git 주요 명령어
## Lacal Repository 생성 후 Remote Repository 등록
- Lacal Repository 생성
+ - 각자 PC에서 프로젝트 폴더 만든다(폴더명은 ml-project-3로 통일)
+ - 그 프로젝트 폴더 안으로 들어가서 마우스 오른쪽 클릭 -> Git Bash Here 클릭 -> 창 뜨면 Remote Repository 등록
<br>
- Remote Repository 등록
+ - $ git remote add origin https://<user name>:<본인 토큰>@<https:// 제외 깃헙 주소>
<br>
- 잘 되었는지 확인
+ - $ git remote -v  ==> fetch랑 push 나오면 잘 된것
<br>
- 유저이름 잊어버렸을 때 ==> $ git config --global --list 하면 정보 나열된다.
<br><br>

## Lacal Repository 변경내용을 Remote Repository에 반영하기
- $ git push origin main

<br>

## Remote Repository 변경내용을 Lacal Repository에 반영하기
- $ git pull origin main
<br><br>

## 간편하게 GitHub에 파일 올리는 방법
- 깃헙 페이지에서 원하는 푤더 들어간 다음 -> Add file -> Upload files
- -> 박스 공안데 드래그앤드롭 -> Commmit changes 눌러주면 등록 완료!

