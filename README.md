# GitUsage

git bash : windows CLI(Command line interface) 처럼 동작하는 Git용 명령도구   
cd : 디렉토리 이동명령   
ex) cd c:\ --> c 드라이브로 이동   
git commit : local 저장소에 저장하는 명령.
git push : remote(원격) 저장소에 저장하는 명령.   
현재 원격 저장소 : github   
git commit -m text : commit할 때 message를 남겨서 저장.
git add . : 현재 디렉토리의 모든 변경점을 stage에 저장.
   
## github로부터 받아오는 방법   
git clone url   
   
## 내 변경점을 github로 올리는방법 , 순서대로 (Getting Started)   
1. bash를 실행해서 내 디렉토리로 이동한다.   
2. 내 변경점을 stage에 저장한다.   
  : git add .
3. 내 변경점을 local 저장소에 저장한다.   
  : git commit -m message
4. 내 변경점을 remote 저장소에 저장한다.   
  : git push origin

## Git 서버와 내 로컬 동기화
git fetch
git pull
