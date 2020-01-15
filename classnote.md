class note

## git

pwd : 지금 폴더 경로위치를 알려줌

ls : 하위폴더를 보여줌
ls -l : 자세히 하위폴더를 보여줌
ls -a : 숨김파일까지 보여줌

cd 폴더이름 : 폴더 위치 이동 (change directory)
cd .. : 상위 폴더로 이동
cd ~ : 유저의 최상단 폴더로 이동. 디폴트 폴더

mkdir 폴더이름 : 새 '폴더'를 만든다 (make directory)
touch 파일이름 : 새 '파일'을 만든다

rm 파일이름 : 파일삭제

rm -r 폴더이름 : 폴더삭제 (-r은 폴더속 파일과 폴더 전부삭제 의미함)

cp 파일이름 폴더위치 : 복사한다

mv 전이름 후이름 : 이름 바꾸기


# vim

vi 파일이름 : vim으로 파일 열기

i 를 누른후 작성가능
작성후 esc로 작성모드 종료
shift +: : vim 메뉴모드 (저장 종료 등)
 - :w 저장, :wq 저장후 종료, :q 종료, :!q 저장없이 종료

 vim 모드 종료 후...

 cat 파일이름 : 작성한 코드를 터미널(gitbash)에서 보여줌


# add > commit > push 
  (2. github에서 먼저 만든후 내 컴퓨터에 동기화하는 경우)
  
add       git add 파일명

commit    git commit (수정내용을 vim에서 설명함)

          git commit - m "간단설명글~~길게는엔터가능" (vim 생략하고 설명단축)

push      git push origin master (github에 올라감)  

  <-> (1. git int : 내 컴퓨터에서 먼저 만든 후, github에 똑같은 파일명을
       만들어서 동기화하는 경우. 동기화 하려는 파일위치에서 명령한다.)


# Clone
git clone 깃허브 주소 : 깃허브에 있는 남이 만든 코드를 맨 처음으로 다운받을 때 씀

(그후 ls를 통해 폴더를 확인 후 cd로 다운받은 폴더로 이동한다)

git pull origin master : 이미 끌고 온 코드정보를 업데이트 할때 씀


git remote : origin이 나옴 뭔지 모르겠음 확인차 하는 것

git remote get -url origin : 끌고온 깃허브 주소 확인할 때 씀


반대개념
/git push origin master : 업로드
/git pull origin master : 다운

code . : vs 열기


# 기타

h1 ~ h6 = # ~ ######
라이센스 : Apache, GPL 위험요소있음. MIT 라이센스 제약 없음
