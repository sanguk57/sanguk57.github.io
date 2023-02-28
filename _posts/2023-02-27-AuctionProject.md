## 경매시스템 프로젝트

 ### 개요
  1.  개발기간 : 2023.01.19 ~ 2023.02.15(1개월)
  2.  개발인원 : (개인프로젝트)
  3.  개발환경
      * 사용언어 및 기술: Java(jdk 11), jstl, JavaScript, CSS/HTML
      * 프레임워크 : Spring Legacy, MyBatis, Jquery, Ajax
      * 라이브러리 : commons
      * 서버 : Apache Tomcat 9.0
      * DB : MySQL
      * 편집툴 : STS, Sequel Pro

### 프로젝트 구성
  

 ### 🎯프로그램 구현
  1.  로그인페이지(gif)
  
  ![ezgif com-video-to-gif (1)](https://user-images.githubusercontent.com/113499796/221567246-71a11e8f-6998-4e51-a874-8820e2546fe2.gif)


  2.  경매상품 목록
  
  ![ezgif com-video-to-gif (2)](https://user-images.githubusercontent.com/113499796/221568380-6ebf3433-c4b2-4f77-8f60-81e78b740aa4.gif)


  ![image](https://user-images.githubusercontent.com/113499796/221569018-2153b5b5-691b-4c92-b25d-01fb462c8bc7.png)

  3. 상품등록 
  
  * 상품관렴 정보 입력
    
  ![ezgif com-video-to-gif (4)](https://user-images.githubusercontent.com/113499796/221570470-bf49fbbd-db2f-4892-9c22-73f79b76bd29.gif)
  4. 경매 시작전
  
  5. 경매 시작
  * 승인처리시 DB 밒 캘린더 API 반영

  ![ezgif com-video-to-gif (5)](https://user-images.githubusercontent.com/113499796/221571781-771ea6a5-6d1e-42d2-ae8b-8d123a43958b.gif)

  6. 경매현황
  
  ![image](https://user-images.githubusercontent.com/113499796/221572582-1fd5b6fd-3245-41de-85dd-a44aead4dd78.png)

  5. 경매종료 
  
  ![image](https://user-images.githubusercontent.com/113499796/221573074-f7f2ab09-6967-4989-85c5-8eff484dd2d9.png)
  
  6. 
  
  ![ezgif com-video-to-gif (6)](https://user-images.githubusercontent.com/113499796/221574491-744b262b-188b-4038-a474-7c8d265f0e03.gif)

 ### 🔖주요데이터 흐름
  1.  경매시스템 구성
  
  ![dataFlow](https://user-images.githubusercontent.com/125232122/221724891-b0ca80ef-13fa-42ff-8521-13f921645fef.png)
  
  * 경매 상품등록 버튼 클릭 상품관련 정보 입력폼으로 이동 
  * 등록한 상품이 경매 목록에 등록 
  * 경매시작전 상품관련 모든 부분 수정가능
  * 경매 시작시간에 맞춰 경매시작
  
  2.  근무신청 구성
  
  ![image](https://user-images.githubusercontent.com/113499796/221574777-a3343304-9487-4e75-ad23-e1e6157a7f0a.png)
  
  ![image](https://user-images.githubusercontent.com/113499796/221574810-2b87ced9-794d-4a86-bb01-e4f374698fb6.png)
  
  * 사원은 근무형태를 신청
  * 시작/종료 일자, 근무형태, 사유를 기입 후 결재자를 지정
  * 결재자는 승인/반려 처리, 승인시 캘린더 API에 반영
  * 팀별 근무신청 조회 가능
  
 ### 💾데이터베이스 구조

![auct](https://user-images.githubusercontent.com/125232122/221728490-8983a4d9-023b-477a-8178-30c6f735aba1.png)
