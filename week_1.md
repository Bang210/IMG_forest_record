## 팀 구성원, 개인 별 역할

---

강병우, 정진영 - article 도메인 구현

민찬홍, 오제민 - member 도메인 구현

류형수, 최동철 - comment 도메인 구현

## 팀 내부 회의 진행 회차 및 일자

---

1회차(2024.01.15) 디스코드 미팅 진행
    - 참여인원: 강병우, 민찬홍, 오제민, 정진영, 최동철

2회차(2024.01.16) 디스코드 미팅 진행
    - 참여인원: 강병우, 민찬홍, 오제민, 정진영, 류형수

3회차(2024.01.17) 디스코드 미팅 진행
    - 참여인원: 강병우, 민찬홍, 오제민, 정진영, 류형수

4회차(2024.01.18) 디스코드 미팅 진행
    - 참여인원: 강병우, 민찬홍, 오제민, 정진영, 류형수

5회차(2024.01.19) 디스코드 미팅 진행
    - 참여인원: 강병우, 민찬홍, 오제민, 정진영, 류형수

6회차(2024.01.20) 오프라인 미팅 진행
    - 참여인원: 오제민, 민찬홍



## 현재까지 개발 과정 요약 (최소 500자 이상)

---

현재까지 진행하고 있는 개발 현황을 기능별 목표, 목표달성률, 성과자체평가(상세히) 작성해주세요.


- article 도메인
    - CRUD: 80%
    - multipartFile을 입력받아 Image객체로 저장하는 로직 구현중에 있음.

- member 도메인
    - CRUD: 100%

## 개발 과정에서 나왔던 질문 (최소 200자 이상)

---

- refreshToken이랑 accessToken 이  처음에 두개가 같이 생성되는지
- 클라이언트가 api 접근을 하면 프론트에서 accessToken 발급하는거를 처리하는지
- 서버에서 refreshToken을 저장해뒀다가 프론트에서 요청하면 서버에서 꺼내주는지
- 로직을 보면 refreshToken을 저장해놨다가 accessToken이 만료되면 꺼내서 주는게 아니라 refreshToken이 있는지 확인을 하고 있으면 다시 accessToken을 발급해서 response쿠키에 담아서 주던데 이 방법이 맞는지, 그렇다면 refreshToken의 역할은 뭔지 
- Dto를 통해 프론트와 통신할 때, Dto에 담아보낸 Article 객체가 있다면 프론트에서 aticle.image.fileName처럼 내부 속성에 접근할 수 있는지

## 개발 결과물 공유

---

Github Repository URL: https://github.com/four-Rest/Img_Forest