# SQLD_2605
SQLD 자격대비반 26년 5월 강의를 자료를 위한 공간입니다.

# 환경구성
Code → Download zip → C:\multisqld에 압축 풀기
## Windows CLI 환경 진입
```
cmd
```
## 기존에 등록된 이미지 제거(교육장)
```
wsl --unregister Ubuntu
```
## 새로 설치(교육장)
```
wsl --install Ubuntu
```
## WSL 실행
```
wsl 
```
## 사용자 설정(초기설정)
- user: sqld / password: sqld
## 실습 파일 경로 접근
```
cd /mnt/c/mutlisqld
```
## docker 설치
```
sudo ./install_docker.sh
sudo chmod 666 /var/run/docker.sock
```
C:\multisqld\images\ 에 2개의 이미지 파일 두기
## 이미지 등록
```
./reg_img.sh
```
## 실습 환경 구동 
- 경로 이동(이미 실행한 상태면 생략 가능)
```
cd /mnt/c/multisqld
```
- 구동
```
./run.sh
```
- 접근 URL
```
http://localhost:8889/?token=multisqld
```
## 실습 환경 종료
```
./stop.sh
```
