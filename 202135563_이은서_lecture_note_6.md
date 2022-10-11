
$git status -파일의 상태 확인
$git add[file_name] - working directory 에 변경내용을 추가
$git add . 변경 내용 넘기기
$git rm -cached [file_name]
---.gitignore file
*.a -ignore all .a files
!lib.a -do track lib.a
/TODO -ignore TODO file
build/ - ignore all files in any directory named build
doc/*.txt - ignore doc/notes.txt, but not doc.server/arch.txt
doc/**/*.pdf -ignore all .pdf files

$git commit -m "commit message"
