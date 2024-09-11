# Figma 기초
|Figma 기본 화면|
|-|
|![image](https://github.com/user-attachments/assets/80d8260d-c5b8-48ce-a283-02d0a38857b2)|
- 눈금선 노출 : Shift + R

  - 상단 눈금선 hover 시, 커서모양이 ↕ 로 변경됨
 
    - 원하는 위치까지 끌어내려서 헤더 및 푸터 위치 잡기 가능

<br>

프레임 만들기
---
|Frame (F)|
|-|
|![image](https://github.com/user-attachments/assets/58a5f854-a428-41dc-b551-2fed1d15597a)|
|![image](https://github.com/user-attachments/assets/b8b32205-d4cd-42bc-ae15-ef50500c5fb6)|

- 격자무늬 버튼 클릭시 우측에 Frame 옵션 노출

  - 웹개발시 Presentation → Slide 16:9 (1920x1080) 주로 사용!

<br>

레이아웃 그리드
---
|Layout grid|
|-|
|![image](https://github.com/user-attachments/assets/ed4c37f5-c280-494e-9ea0-723a221a5881)|
|![image](https://github.com/user-attachments/assets/39ace75f-f04e-4922-9097-dd180e33d658)|
|![image](https://github.com/user-attachments/assets/47369753-5d7e-475c-819a-263b90a93951)|
|![image](https://github.com/user-attachments/assets/db6f57b8-49e4-4f1b-9d83-7224656bb51f)|

- 프레임 선택하고 싶으면 Ctrl + 해당 프레임

- 프레임 선택 후 우측 Design 탭에서 Layout grid 항목의 + 버튼 클릭

  - Layout grid setting 클릭하여 Grid 를 Column 으로 변경
 
    - 보통 Count 를 4, 6, 8 로 만들어두므로 Layout grid 를 3개 만들어야 함

  - Layout grid setting 에서 Margin 을 320 으로 변경
       
    - 웹 페이지의 양 사이드에는 마진 넣어주는 것이 일반적
   
      - 프레임 크기(1920px) - 웹페이지 크기(1280px) = 마진 크기(640px)
     
      - 양 옆의 마진 크기를 합한 것이 640px 이므로 한 사이드당 마진 크기는 320px     

- Layout grid 항목들의 눈동자 표시를 통해 원하는 그리드만 노출시킨 후 작업 가능

<br>

헤더 고정
---
|Rectangle (R)|
|-|
|![image](https://github.com/user-attachments/assets/a4aa2584-8999-4323-87cf-16fc2452f705)|
|![image](https://github.com/user-attachments/assets/48152510-d5ae-44cc-86b7-191802c77138)|
|![image](https://github.com/user-attachments/assets/68db1bb8-37e7-44e3-9f13-11c77c6d57f0)|

- 네모 모양 버튼으로 사각형 도형 추가 가능

- 헤더 만들기

  - 사각형 도형 추가
  
  - 우측 Design 탭에서 width 를 1920 으로 바꾸고 Position 에서 Align horizontal centers, Align top 선택
 
- 푸터 만들기

  - 사각형 도형 추가
 
  - 우측 Design 탭에서 width 를 1920 으로 바꾸고 Position 에서 Align horizontal centers, Align bottom 선택

- 헤더고정을 확인하기 위해 height를 늘리고 헤더와 푸터 사이에 색 다르게 여러 사각형 추가하기

  - Alt + 도형 선택 후 drag 하면 copy
 
- 해당 프레임 선택 후 우측 Present(▷) 버튼 누르면 실행

  - 우측 상단 조정버튼 클릭하여 Full Screen 을 Actual Size 로 변경
 
- 스크롤 내려보면 헤더도 함께 내려가는 상태

  - 헤더 부분 클릭 후 우측 Prototype 탭에서 Scroll behavior 의 position 변경
 
    - Scroll with Present → Fixed

- 해당 프레임 선택 후 다시 실행해보면 헤더 고정된 상태인 것 확인 가능

<br>
