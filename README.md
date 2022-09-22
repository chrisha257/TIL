# git허브 특강 (1일차)

![Git로고](https://user-images.githubusercontent.com/49775540/168756716-68f9aebb-380f-4897-8141-78d8403f6113.png)



## 0. config 설정 
-> 컴퓨터에서 딱! 한번만
->git에게 내가 누군지 알려주기 
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
git config --global --list

## 1. git init
git 으로 관리 시작
-> 디렉토리당 한번만
주의! 홈폴더나 바탕화면 x

## 2. git status (중요)
파일 상태 확인

## 3. git add 파일명
무대위로 올리기

## 4. git commit -m "커밋 사유"
변경사항을 기록
즉, 사진 찍기
(vim 빠져 나오는 것 esc + :q )

## 5. git log
커밋의 내역 확인
--oneline

## 6. 지난 버전 확인하기
git checkout 커밋ID

## 7. 커밋들을 비교하기
git diff 커밋ID 커밋ID

## 8. github와 연결
git remote add origin URL
git remote -v
  #remote 삭제
git remote rm origin

## 9. github에 local commits 올리기
git push origin master


