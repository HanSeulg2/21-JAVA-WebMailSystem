# JAVA-웹 메일 시스템
- Language : JAVA
- Tools : NetBeans IDE, Docker
- Server : Tomcat 9.0 , Apache James 2.3.2
- Techs : JavaMail api 7.0
- Database : MySQL 8.0.23
- 형성관리 : gitHub

# 주요기능 
- 사용자 관리 (사용자 추가,삭제, 수정)
- 회원가입 (가입, 탈퇴) 
- 로그인 (비밀번호 수정, 로그아웃)
- 메일 쓰기 (내게쓰기, 전달하기 , 첨부파일)
- 메일 읽기
- 주소록 (즐겨찾기)
- 메일함 (보낸 메일함, 내게 쓴 메일함)

# 유지보수
### * 교정 유지보수
- 오류로 인한 유지보수
### * 적응 유지보수
- 데이터 환경과 인프라 환경 변화 적응을 위한 유지보수
 1. NetBeans에서 JDBC 접속하지 않고 Docker을 사용하여 MySQL연동
 
![image](https://user-images.githubusercontent.com/71927210/131784685-7a45fec5-9768-4f77-a308-20cbdeee37d1.png)
![image](https://user-images.githubusercontent.com/71927210/131784605-ffed49fa-4f55-47d7-be1c-ee3a533227f1.png)
![image](https://user-images.githubusercontent.com/71927210/131784610-2948b391-eb1c-448c-87f5-6b4d71118e0d.png)
![image](https://user-images.githubusercontent.com/71927210/131784722-137a5209-6e2e-437c-aa3c-444defcc9d5a.png)
#### 유스케이스
![image](https://user-images.githubusercontent.com/71927210/131784820-18adade1-2658-4dd4-b5f9-02b6ceb939f7.png)

#### 통신다이어그램
![image](https://user-images.githubusercontent.com/71927210/131784813-01b1cb1d-e495-40f9-ac79-c5a64b856036.png)
 2. 메일 삭제 완료 알림
![image](https://user-images.githubusercontent.com/71927210/131784966-ab176755-e678-4e38-8bca-6beee712dd14.png)

### * 완전화 유지보수
- 기능이나 성능 향상을 위한 개선을 위한 유지보수
 1. 회원가입 
 
![image](https://user-images.githubusercontent.com/71927210/131785712-e3b4379f-e480-4bb4-8742-b18b6928b0b3.png)
![image](https://user-images.githubusercontent.com/71927210/131785523-d6bf0dbd-7601-4ed1-b38e-6c8184374baa.png)
![image](https://user-images.githubusercontent.com/71927210/131785620-1a497b16-bb8c-4dda-8e23-28f7d05bd161.png)


#### 유스케이스 
![image](https://user-images.githubusercontent.com/71927210/131785086-10865b1b-fe7e-4592-93fc-6c6324b6e1de.png)

#### 시스템 순차 다이어그램 
![image](https://user-images.githubusercontent.com/71927210/131785110-84ce9504-5dfb-49bb-86b0-a4e13f44bb83.png)

#### 도메인 모델 
![image](https://user-images.githubusercontent.com/71927210/131785142-fa84370d-eff6-4788-9ce7-9f0cc204a42f.png)

#### 통신다이어그램
![image](https://user-images.githubusercontent.com/71927210/131785381-91c66941-f6a6-4a59-8ff5-484288f1cbd2.png)

 2. 사용자 관리
 
![image](https://user-images.githubusercontent.com/71927210/131785946-b15883db-584c-4ff4-afcf-a7de77a488cc.png)
![image](https://user-images.githubusercontent.com/71927210/131785959-36d12be4-d8d6-4188-b3d9-dcac7f63d182.png)
![image](https://user-images.githubusercontent.com/71927210/131785967-a9339889-2011-45b6-bd31-33946fb33c8b.png)

 3. 주소록 (즐겨찾기)
 
![image](https://user-images.githubusercontent.com/71927210/131786106-71fa833e-2b26-4d18-a4d8-b1a72853e7de.png)

##### 추가

![image](https://user-images.githubusercontent.com/71927210/131786114-e525d6fa-2761-4015-8623-7f5fb59d5d36.png)
![image](https://user-images.githubusercontent.com/71927210/131786118-12a10017-491f-47b3-bead-ce69e57eb135.png)

##### 중복체크

![image](https://user-images.githubusercontent.com/71927210/131786207-8d9913f8-f5d6-4e96-b540-5026f4c74b25.png)
![image](https://user-images.githubusercontent.com/71927210/131786215-92d747c2-ee5d-423b-8c10-11d40cd57070.png)


##### 삭제

![image](https://user-images.githubusercontent.com/71927210/131786398-01eb388e-f0ae-405d-9795-b8e3ef39af80.png)
![image](https://user-images.githubusercontent.com/71927210/131786423-538dea3d-ef87-499b-9239-2d1258ed3db8.png)

### * 예방 유지보수
- 이해성과 유지보수성을 개선을 위한 유지보수
