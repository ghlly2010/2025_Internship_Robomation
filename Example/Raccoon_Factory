
# 라쿤 공장 자동화

**해당 문서는 Raccoon의 테스트 예제 설명 문서입니다.**

***

#### [하드웨어 설명](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/%EB%9D%BC%EC%BF%A4-%ED%95%98%EB%93%9C%EC%9B%A8%EC%96%B4-%EC%84%A4%EB%AA%85)

#### [블록 컴포저 바로가기](https://robomationlab.com/BlockComposer/)
  
#### [로보메이션 깃허브 바로가기](https://github.com/RobomationLAB)

#### [초보자를 위한 블록컴포저 환경설정 가이드](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/%EB%B8%94%EB%A1%9D%EC%BB%B4%ED%8F%AC%EC%A0%80-%ED%99%98%EA%B2%BD-%EC%84%A4%EC%A0%95-%EA%B0%80%EC%9D%B4%EB%93%9C)
<br>

***

<img width="400"  src="https://github.com/user-attachments/assets/b6e58540-5064-4397-b041-1f27fd8a28b0" />
<br>



**[작동 영상]**

<img width="400"  src="https://github.com/user-attachments/assets/c98b01d1-8045-4e58-b69f-3795bcd49049" />
  



**로봇팔 라쿤과 햄스터 2대를 이용한 공장자동화 예제**
***


## 1. 준비물

   | 제품명(수량) | 이미지 | 제품명(수량) | 이미지 | 
   | :---: | :---: | :---: | :---: |
   | 햄스터 S<br>( 2개 ) | <img width="200" height="200" alt="1_1햄스터" src="https://github.com/user-attachments/assets/9b1f9ac0-0d80-43fd-b951-1c713d7a5312" /> | 라쿤<br> ( 1개 ) | <img width="200" alt="1_2라쿤" src="https://github.com/user-attachments/assets/912bd02f-ecae-4c8c-b7e6-5f952edaa7d3" />
   | 햄스터 <br>경기장 세트 <br> ( 1개 )| <img width="200" height="200" alt="1_3경기장" src="https://github.com/user-attachments/assets/a8ffb788-cf88-4e53-a505-fc0660d05e78" /> | 햄스터 S <br>AI 카메라<br> ( 1개 ) | <img width="200" height="180" alt="1_4햄스터 S AI 카메라" src="https://github.com/user-attachments/assets/5c16ca9e-9835-4e82-86d5-10dd092320d2" />
   | 전용 맵<br> ( 1개 ) | <img width="200" height="150" alt="1_5전용맵" src="https://github.com/user-attachments/assets/e49cf29b-7883-4d0a-8d5d-dc369efce3e4" /> | 빨간색 블록<br> ( 3개 ) | <img width="200" height="150" alt="1_6빨간블록" src="https://github.com/user-attachments/assets/0d475f71-f8b0-4b34-b572-76395be0f2b2" /> |
   | 바스킷<br> ( 2개 ) |  <img width="200" height="150" alt="1_7바스킷" src="https://github.com/user-attachments/assets/6e0a72e2-87fb-48e5-83d9-10c65c229b1e" /> | 컨베이어<br>(1개) | <img width="200" height="200" alt="1_8컨베이어" src="https://github.com/user-attachments/assets/e939d713-d95f-4fdb-806a-8f25cb30faab" />



***
## 2. 초기 환경 구성
**1. 햄스터 경기장 세트를 조립한다.**
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/c549421b-2372-4ec2-b61c-297628da7279" width="400" height="350" />
   </div>
   <br>

**2. 햄스터 경기장 중앙에 맵을 깔아준다.**
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/0f201520-1e66-471a-a208-84767a520e23" width="400" height="350"/>
   </div>
   <br>

**3. 라쿤과 컨베이어를 위치에 맞게 배치한다.**
   <br>
    라쿤은 앞쪽 모서리, 컨베이어는 각각의 모서리가 작은 정사각형에 맞도록 배치한다.
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/1bb387a5-ceec-4fc7-a761-76d2b84b5fc7" width="400" height="350"/>
   <img src="https://github.com/user-attachments/assets/1994dbee-12c1-41dd-a183-89e81042d6d2" width="400" height="350" />
   </div>
   <br>
   
**4. 카메라를 세팅한다.**
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/22d983cb-afc2-4e87-87a4-ba550ddebe9e" width="225" height="225" /><img src="https://github.com/user-attachments/assets/6c9b544a-acd3-4a06-a3ec-0761457173e4" width="300" /><img src="https://github.com/user-attachments/assets/dce69ef6-ef1a-4a4a-a004-19ea32b73f67" width="300" />
   </div>
   <br>
   사진과 같이 카메라의 빨간 점 부분이 위쪽을 향하게 배치한다.
   <br>

   **주의사항 :** 다른 카메라 사용시 카메라마다 고유한 픽셀 값이 다르기에 코드를 수정할 필요가 있을 수 있다.
   <br>
   
**5. 햄스터와 바스킷을 연결한다.**
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/4b2a66b8-1df2-42c1-9011-d75c1f839a06" width="300" /><img src="https://github.com/user-attachments/assets/c6b089b5-e550-45b5-b05a-3645aa497368" width="300" />
   </div>
   <br>

**6. 햄스터와 블럭을 알맞은 위치에 놓아준다.**
   <br>
   <div align="center">
   <img src="https://github.com/user-attachments/assets/dcdc5d0c-fbfe-4d45-8041-94959582cca7" width="300" />
   <img src="https://github.com/user-attachments/assets/56edd492-ee7a-44da-b919-d5810da60854" width="300" />
   <br>
   <img src="https://github.com/user-attachments/assets/01cb594b-36d0-4ed8-9b86-c6292bb8c342" width="300" />
   <img width="300" alt="2_1-12" src="https://github.com/user-attachments/assets/3f38a215-063d-4543-b0ec-8fe4b969665f" />
   </div>
   <br>
   이때 햄스터가 정지선 밖에 존재하도록 놓아준다.
   <br>

**7. 로봇의 전원을 연결한다. 이후 [작동하기](#3-작동하기) 부분으로 이동하여 진행한다.**
   <br>
    <div align="center">
   <img width="523" height="257" alt="2_7-5" src="https://github.com/user-attachments/assets/2bbc80a8-97cd-4d2e-abb1-71cf4865c81b" />
   <br>
   <img width="510" height="250" alt="2_7-6" src="https://github.com/user-attachments/assets/a0aa1a61-0a9d-49bc-b833-5c439bf0a550" />
   </div>
   <br>

**8. 로봇과 블루투스 동글과 연결한다.**
   <br>
   블루투스 동글을 PC에 연결한다.
   <br>
   PC에 동글을 연결후 로봇을 가까히 가져가면 블루투스 동글과 로봇이 연결된다.
   <br>
   <br>
    <div align="center">
   <img width="800"  alt="2_8-1" src="https://github.com/user-attachments/assets/1b5b9cd7-8fb1-43c7-a8d5-19159d7b503c" />
   </div>
   <br>
   라쿤은 블루투스가 연결되면 파란 LED가 켜진다.
   <br>
    <div align="center">
   <img width="800"  alt="2_8-2" src="https://github.com/user-attachments/assets/bc800341-6c30-46a1-9c1f-c2efd7739094" />
   </div>
   <br>
   햄스터는 블루투스가 연결되면 LED가 꺼진다.
   <br>
   
***

## 3. 작동하기
**1. [Block Composer](https://robomationlab.com/BlockComposer/) 사이트에 접속한다.**
   <br>

**2. 상단에 있는 파일에서 불러오기를 통해 첨부되어 있는 블록 파일을 불러온다.**
   <img width="900" height="300" alt="3_2-1" src="https://github.com/user-attachments/assets/bd3f981e-3f90-4622-bd5a-153464210650" />
   <br>

**3. 우측 상단에 있는 동글 찾기 버튼을 눌러 로봇을 추가해준다.**ㄴ
   <img width="900" alt="3_3-2" src="https://github.com/user-attachments/assets/4a87ea32-f7ef-4169-a9dd-947663880c26" />
   <img width="300" height="400" alt="3_3-3" src="https://github.com/user-attachments/assets/29d4ed95-08b7-46f3-94aa-426c717b36e2" />
   <br>
   위 과정을 3번 반복하여 로봇 추가가 완료되면 다음과 같이 로봇 연결 상태에 라쿤과 햄스터 2대가 연결된 모습을 확인할 수 있다.
   <img width="400" height="400" alt="3_3-4" src="https://github.com/user-attachments/assets/3799cc0e-e14d-4b2c-a9d9-5b667f4eb6fb" />
   <br>

**4. 카메라를 본인이 지정한 카메라로 정해준다.**
   <br>
      만일 햄스터 AI 카메라를 이용할 때에는 [햄스터 AI 카메라 퀵가이드](https://robomation.net/?p=9974)를 참고한다.
   <br>
   <img width="500" height="200" alt="3_4-1" src="https://github.com/user-attachments/assets/5d2f7662-b98b-4344-8d5c-b641ca90ae60" />
   <img width="400" height="150" alt="3_4-2" src="https://github.com/user-attachments/assets/951009ac-805f-46b6-8cf1-d1d4b1ca5bf7" />
   <br>

**5. 오른쪽 콘솔 탭에서 카메라를 선택하고, 카메라 켜기를 통해 카메라를 켜준다.**
   <br>
   <img width="500" height="300" alt="3_5-1" src="https://github.com/user-attachments/assets/182dbe4b-c4a0-44b7-bacf-57be924ae013" />
   <br>

   <br>

**6. 시작하기 버튼을 눌러 로봇을 작동시킨다.**
   <br>
   <img width="500" height="150" alt="3_6-1" src="https://github.com/user-attachments/assets/57ff2680-fbb7-4d10-b3eb-42d731776168" />
   <br>
   *작동을 하지 않을 경우 아래 [오류 발생시 해결 방법](#4-오류-발생시-해결-방법)란으로 이동한다.*
   <br>
***
## 4. 오류 발생시 해결 방법
### 1. 카메라가 안 뜨는 현상
   현재 열려있는 브라우저 창을 닫고, 카메라 연결한 후 브라우저에 다시 접속한다.
### 2. 햄스터는 움직이지만, 로봇은 안움직이는 상황
   통신 불량일 문제이다. 동글이를 로봇 근처로 옮기어 다시 진행을 해본다.
### 3. 햄스터는 안움직이지만, 로봇은 움직이는 상황
   햄스터에 노란색 불이 들어오면, 햄스터 로봇의 전압이 3.3v이하이기에 발생한 문제이다. 햄스터를 충전하고 사용하면, 문제가 해결된다.
### 4. 로봇이 물체를 못잡거나 너무 높은 곳에서 내려놓는 상황
   <div align="center">
   <img width="800" alt="4_4" src="https://github.com/user-attachments/assets/16fada18-35d1-481b-bf39-11ac7dd96b16" />
   </div>
   <br>
   역기구학의 Z좌표를 수정하여 알맞은 위치에 내려놓을 수 있도록 한다.

### 5. 로봇이 바구니와 컨베이어에 물체를 잘 못 놓거나 잡는 경우
   <div align="center">
   <img width="800"  alt="4_5" src="https://github.com/user-attachments/assets/b5f0fc5c-8e0f-4fc0-97b6-40c90a14d439" />
   </div>
   로봇마다 물성치의 차이가 있어 정확한 위치에 놓거나 잡는 문제가 발생한다. async inverse kinematics 함수의 좌표를 수정해주면 된다.
   
### 6. 컨베이어에 끝에 물체가 도달해도 물체를 잡지 못하는 상황
   카메라마다 픽셀 값이 다르기 때문에 픽셀차이 부분을 조정 하면 된다.
   <div align="center">
   <img width="1800" alt="4_6-1" src="https://github.com/user-attachments/assets/7a447ed2-a597-4b73-89d5-ef084107ee86" />
   </div>
   <br>
   위 사진을 참고하여 빨간색-노란색의 픽셀값을 조절해주면 된다

***
## 5. 작동 알고리즘
1. 햄스터는 바닥센서를 통해서 선을 따라가며, 정지선을 만나면 정지하는 알고리즘을 통해 구동한다.
2. 정지선에 도달하면 위치를 햄스터가 정지하고, 정지한 위치로 로봇팔을 이동시켜 물체를 잡는다. 
3. 로봇팔이 물체를 잡고 위로 올리면, 햄스터는 다시 라인을 따라 주행하고, 로봇팔이 잡은 물체는 컨베이어로 이동시킨다.
4. 바닥에 찍힌 노란 점과 빨간블록의 픽셀 연산을 통해서 컨베이어 말단까지 물체가 이동하였는지 확인한다.
5. 컨베이어 끝까지 물체가 이동했다면, 로봇팔이 물체를 잡고, 물체를 햄스터 바구니로 옮겨 준다.
***
## 6. 코드 설명
### 1. Hamster Line Tracing 함수
<details>
<summary><b>Hamster Line Tracing 함수</b></summary>
   <img width="1018" height="1061" alt="6_1" src="https://github.com/user-attachments/assets/6e08cecd-a1be-473c-8e36-bd32595ae2b0" />

   **Hamster Line Tracing 함수는 햄스터가 선을 따라가며, 일정 상황에 도달하면 정지하도록하는 함수이다.**

   1. 초기에 Hamster가 선을 감지했는지 알려주는 Line_Flag0와 Line_Flag1로 설정한다.
   2. 만약 햄스터0번의 왼쪽 바닥센서가 50이하이고 오른쪽 바닥센서가 50이하이면 선을 감지하였다는 것이기에 선을 감지라면 따라가기를 멈추고 Line_Flag0를 1로 바꾸어주고 파란 등을 점등해준다. 
   3. 이후 End_Flag0을 1로 바뀌면 다시 선을 따라가고 초록 등을 점등한다.
   4. 만약 햄스터1번의 왼쪽 바닥센서가 50이하이고 오른쪽 바닥센서가 50이하이면 선을 감지하였다는 것이기에 선을 감지라면 따라가기를 멈추고 Line_Flag1를 1로 바꾸어주고 파란 등을 점등해준다. 
   5. 이후 End_Flag1을 1로 바뀌면 다시 선을 따라가고 초록 등을 점등한다
   6. 만약 햄스터 0번의 왼쪽과 오른쪽의 근접 센서가 70보다 크면 앞에 로봇이 있다는 신호다. 그럴때는 선 따라기기를 멈추고 빨간등을 켜준다. 아닐 떈, 선을 따라가고 초록등을 켜준다.
   7. 만약 햄스터 1번의 왼쪽과 오른쪽의 근접 센서가 70보다 크면 앞에 로봇이 있다는 신호다.그럴때는 선 따라기기를 멈추고 빨간등을 켜준다. 아닐 떈, 선을 따라가고 초록등을 켜준다.
   8. 만약 햄스터 0번의 배터리가 3.3V이하로 떨어지면, 선 따라가기를 멈추고 양쪽 등을 노란색으로 점등한다.
   9. 만약 햄스터 1번의 배터리가 3.3V이하로 떨어지면, 선 따라가기를 멈추고 양쪽 등을 노란색으로 점등한다.
</details>

### 2. Conveyor_Detect 함수
<details>
<summary><b>Conveyor_Detect 함수</b></summary>
   <img width="1000" height="190" alt="6_2" src="https://github.com/user-attachments/assets/474492df-cca9-4ec0-9f37-413f6fc46a11" />
   
   **Conveyor_Detect는 컨베이어 끝에 물체가 왔는지 확인하는 함수이다.**
   먼저 필요한 정보인 노랑과 빨간색을 찾았는지 확인한다.
   이후 빨간색과 노랑색 x,y 좌표의 차이가 범위 내에 들어오면, 컨베이어 끝까지 물체가 이동했다는 것으로 Conveyor_Flag를 1로 바꾼다.
   이외의 경우에는 속도를 100으로 지정하여 컨베이어가 동작할 수 있도록 한다.
</details>

### 3.async Pick_and_Drop1 함수
<details>
<summary><b>async Pick_and_Drop1 함수</b></summary>
   <img width="200" height="200" alt="6_3" src="https://github.com/user-attachments/assets/33fcac6f-ba65-4908-9572-5570eec4b0ed" />

   **async Pick_and_Drop1는 location0에서 선을 감지할 때 실행하는 코드이다.**
   역기구학을 통해 물체를 잡을 위치까지 이동 후 물체를 잡는다.
   이후 로봇의 팔을 들고, 컨베이어 속도를 0으로하고. 다음 명령을 기다린다.
</details>

### 4.async Pick_and_Drop2 함수
<details>
<summary><b>async Pick_and_Drop2 함수</b></summary>
   <img width="500" height="200" alt="6 4" src="https://github.com/user-attachments/assets/cf057402-924a-4e02-9802-da57a734d6a1" />
   
   **async Pick_and_Drop2는 location1에서 선을 감지할 때 이용한다.**
   역기구학을 통해 이동을 완료후에 함수를 호출하면, 물체를 놓아 햄스터의 바구니에 물체가 들어가게 한다. 이후 로봇의 팔을 접고,atan2함수를 통해 계산된 위치로 관절 1을 이동시켜 다음 명령을 실행하도록 한다.
</details>

### 5. async Inverse_kinematics 함수
<details>
<summary><b>async Inverse_kinematics 함수</b></summary>


<img width="800" src="https://github.com/user-attachments/assets/769df4b5-4851-4a84-b3ae-9e9f609a8023" />

단위는 cm로 각 링크의 길이를 0, 10, 10, 9로 설정하고 기구학을 해석한다.  
각 링크의 각도를 \( J_1 \), \( J_2 \), \( J_3 \)라 하고 기구학을 풀이하면 다음과 같다.  

\[
J_1 = \tan^{-1}\left(\frac{y}{x}\right)
\]

이후 Gripper를 고려하여  

\[
x = x - 9 \cdot \cos(J_1), \quad y = y - 9 \cdot \sin(J_1)
\]

을 해준다. 이후 링크의 길이를 구하기 위하여 길이 \( D \)를 구하면 다음 공식과 같이 표현된다.  

\[
D = \sqrt{x^2 + y^2 + z^2}
\]

\( J_1 \)과 \( J_2 \)의 링크의 길이가 10이기에 다음 공식이 사용 가능하다.  
Cos 법칙을 통해 각도를 구하면 다음과 같다.  

\[
\cos(\theta_3) = \frac{D^2 - 200}{200}
\]

이 결과를 가지고 \( J_3 \)의 각도를 구하면  

\[
J_3 = \tan^{-1}\left( \frac{-\sqrt{1 - \cos^2(\theta_3)}}{\cos(\theta_3)} \right)
\]

(\( \cos^2 + \sin^2 = 1 \))  

2번의 각도를 구하기 위하여 \( \beta \)와 \( \alpha \)를 통해 구한다.  

\[
\beta = \tan^{-1}\left( \frac{z}{\sqrt{x^2 + y^2}} \right)
\]

\[
\alpha = \tan^{-1}\left( \frac{-\sqrt{1 - \left(\frac{D^2}{20D}\right)^2}}{\frac{D^2}{20D}} \right)
\]

따라서  

\[
J_2 = \beta - \alpha
\]

로 역기구학을 해석 가능하다.
자세한 내용은 [Inverse Kinematics](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/4Dof-Kinematics%EA%B8%B0%EA%B5%AC%ED%95%99)를 참고하면 된다.
</details>

### 6. Main 함수
#### 1. 초기 세팅 함수
   <details>
   <summary><b>초기 세팅 함수</b></summary>
      <img width="300" height="500" alt="image" src="https://github.com/user-attachments/assets/92b3e2d5-07de-49a8-8168-01048bb6fd9b" />

   **카메라 설정**
      다음 부분에서는 카메라를 설정한다.
      사용할 카메라를 지정하고,컨베이어의 끝으로 물체가 도달했는지 확인하기 위해, 노랑과 빨간색을 추가한다.
      이후 연속적으로 물체를 찾기 위해 연속으로 색깔 찾기를 시작한다.

   **햄스터 설정**
      사용할 햄스터의 초기 상태를 설정해준다.
      두 햄스터의 초기 속도를 7로하고
      선 따라가기 방향 변화량을 10으로 설정한다.

   **라쿤&컨베이어 설정**
      라쿤을 각도 제어모드로 사용하도록 설정한다.
      이후 물건을 잡을 수 있도록 말단장치를 수평으로 고정한다.
      컨베이어를 속도제어 모드로 사용한다.
      라쿤의 각도제어 속도를 100으로 지정한다.

   **변수 소개**
      **Obj_Flag**: 물체를 잡으면 1 안 잡으면 0
      <br>

   **location0**: 햄스터0번의 위치 0이면 선 외부, 1이면 선 내부
   <br>
   
   **location1**: 햄스터1번의 위치 0이면 선 외부, 1이면 선 내부
   <br>
   
   **case**: 경우를 나타낸 변수, 로그 출력하기로 어디가 실행 중인지 알 수 있다.
   <br>
   
   **Line_Flag0**: 햄스터 0번이 선을 감지했는지 확인하는 변수 0이면 미인지 1이면 인지
   <br>
   
   **Line_Flag1**: 햄스터 1번이 선을 감지했는지 확인하는 변수 0이면 미인지 1이면 인지
   <br>
   
   **End_Flag0**: 일정 내용을 실행 후 햄스터0번에게 수행이 완료됨을 알리는 변수, 1이면 실행할 내용이 있음 0이면 실행할 내용이 없음(수행완료)
   <br>
   
   **End_Flag1**: 일정 내용을 실행 후 햄스터1번에게 수행이 완료됨을 알리는 변수, 1이면 실행할 내용이 있음 0이면 실행할 내용이 없음(수행완료)
   <br>
   
   **Hamster_battery_stack0**: 햄스터 0번의 배터리 스택의 인덱스
   <br>
   
   **Hamster_battery_stack1**: 햄스터 1번의 배터리 스택의 인덱스
   <br>
   
   **list0**: 햄스터 0번의 배터리 전압을 저장할 배열
   <br>
   
   **list1**: 햄스터 0번의 배터리 전압을 저장할 배열
   <br>
   
   **Stack_start0**: 햄스터 0번의 배터리를 MAF를 통해 계산이 가능함을 알려주는 신호, 1이면 계산 가능 상태 0이면 계산 불가능한 상태
   <br>
   
   **Stack_start1**: 햄스터 1번의 배터리를 MAF를 통해 계산이 가능함을 알려주는 신호, 1이면 계산 가능 상태 0이면 계산 불가능한 상태
   <br>
      

   **변수 초기화**
      **변수를 초기화 해주는 부분이다.** 변수를 초기화하여 프로그램 내의 혼란을 줄인다.
      location0과 location1을 0으로 초기화 해줌으로써, 로봇이 두 선 사이에 있지 않음을 알려준다.
      Conveyor_Flag도 초기에 0으로 설정하여 컨베이어 끝에 빨간 물체가 도달하지 않음을 알린다.
   </details>

   #### 2. 시작하기 반복문 소개
   <details>
   <summary><b>시작하기 반복문 소개</b></summary>
   <img width="699" height="592" alt="6_5-2" src="https://github.com/user-attachments/assets/07bcccd1-eba0-4f69-99bc-659a215acfd7" />

   초기에 지속적으로 컨베이어 끝단에 물체가 왔는지 확인하는 Conveyor _Detect 함수를 수행한다.

   **만일 물체를 잡지 않은 상태 (Obj_Flag=0)이고 햄스터 0번이 라인을 감지할 경우에는 다음 과정이 진행된다.**
   1. 햄스터의 선 따라가기 속도를 6으로 바꾸어준다.
   2. Case를 1로 설정한다.
   3. 3.async Pick_and_Drop1을 수행하여 햄스터 위 물체를 잡는다.
   4. End_Flag를 1로 설정하여 작업 수행이 완료됨을 알린다.
   5. 1초 후 End_Flag를 0으로 초기화를 해준다.
   6. 햄스터0이 라인을 통과했기에 location0을 1만큼 바꾼다.
   7. 역기구학을 통해 잡은 물체를 컨베이어 위에 올려놓고 관절각을 이동하기 쉽게한다.
   8. 이후 컨베이어를 작동시키어 물체가 컨베이어 끝으로 이동하게 한다.
   9. 로봇이 컨베이어 끝의 물체을 잡기 편하도록 라쿤의 1번 관절 각도를 설정한다.
      
   <img width="716" height="522" alt="6_5-3" src="https://github.com/user-attachments/assets/4f9f0d40-76ce-4c42-80f3-82e2f4f49f4d" />

   **햄스터 1번이 라인을 감지할 경우에는 다음 과정이 진행된다.**
   1. 햄스터의 선 따라가기 속도를 8로 바꾸어준다.
   2. Case를 3로 설정한다.
   3. async Pick_and_Drop1을 수행하여 햄스터 위 물체를 잡는다.
   4. End_Flag를 1로 설정하여 작업 수행이 완료됨을 알린다.
   5. 1초 후 End_Flag를 0으로 초기화를 해준다.
   6. 햄스터1이 라인을 통과했기에 location1을 1만큼 바꾼다.
   7. 역기구학을 통해 잡은 물체를 컨베이어 위에 올려놓고 관절각을 이동하기 쉽게한다.
   8. 이후 컨베이어를 작동시키어 물체가 컨베이어 끝으로 이동하게 한다.
   9. 로봇이 컨베이어 끝의 물체을 잡기 편하도록 라쿤의 1번 관절 각도를 설정한다.

   <img width="666" height="435" alt="6_5-4" src="https://github.com/user-attachments/assets/ec4b3a79-4906-47b8-9987-3dfc7d898e49" />

   **만약 햄스터의 위치가 선을 통과하여 location0 또는 location1이 1이되는 경우에는 다음 과정을 실행한다.**

   컨베이어의 속도를 0으로 설정하여 정지시킨다.

   만일 Conveyor_Flag가 1이면 물체가 컨베이어 끝까지 도달했다는 의미로 이 경우에는 역기구학을 통해 컨베이어 끝으로 라쿤의 말단을 이동시키어 물체를 잡고, 물체를 놓을 위치를 역기구학을 통해서 이동시키고 대기한다.
   Conveyor_Flag를 0으로하여 물체가 컨베이어를 떠났다는 것을 알리고, Obj_Flag를 1로 바꾸어 물체를 잡았다는 신호를 준다.

   <img width="575" height="643" alt="6_5-5" src="https://github.com/user-attachments/assets/e923ecaa-5f76-48b4-8679-59ddb49063b7" />

   <br>
      
   **만일 Obj_Flag가 1로 물체를 잡은 상황에서 location0가 1이고 Line_Flag0가 1인 상태에서 물체를 놓을 위치에 햄스터 0번이 도달하면 다음 과정이 실행된다.**

   1. 햄스터 0번의 선 따라가기 속도를 5로 정한다.
   2. case를 2로 설정한다.
   3. async Pick_and_Drop2를 수행하여 물체를 놓는 동작을 진행한다.
   4. End_Flag를 1로 설정하여 작업 수행이 완료됨을 알린다.
   5. 1초 후 End_Flag를 0으로 초기화를 해준다.
   6. 햄스터0이 라인을 통과했기에 location1을 0으로 설정한다.
   7. Obj_Flag를 0으로 설정하여 물체를 잡지 않은 상태로 변수를 설정한다.
      
   **물체를 놓을 위치에 햄스터 1번이 도달하면 다음 과정이 실행된다.**

   1. 햄스터 1번의 선 따라가기 속도를 5로 정한다
   2. case를 4로 설정한다.
   3. async Pick_and_Drop2를 수행하여 물체를 놓는 동작을 진행한다.
   4. End_Flag를 1로 설정하여 작업 수행이 완료됨을 알린다.
   5. 1초 후 End_Flag를 0으로 초기화를 해준다.
   6. 햄스터1이 라인을 통과했기에 location1을 0으로 설정한다.
   7. Obj_Flag를 0으로 설정하여 물체를 잡지 않은 상태로 변수를 설정한다.

   <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/6c8599d1-72fa-419a-ae60-f6b78f9067c4" />

   <br>
      
   **MAF를 이용하여 배터리의 잔량을 계산하는 부분이다.** 
   <br>
   Hamster battery stack을 1만큼 증가시키고 만일 20보다 클 경우에는 stack counter를 1로 설정하여 연산을 할 수 있다는 것을 프로그램상으로 알려준다. 그리고 Hamster battery stack을 0으로 바꾸어주어 0번째 배열에 문자를 넣어주도록 한다. 리스트의 Hamster battery stack의 해당하는 배열에 햄스터 배터리를 넣어주고, 리스트의 합을 구하여 스택의 수 20으로 나누어주면, 배터리 전압의 평균이 나온다. 만일 이 평균이 3.3보다 작은 경우에는 Stop Flag를 주어 로봇이 정지하도록 명령을 내린다.
   </details>

### 7. 무한 반복하기 문
<details>
   <summary><b>무한 반복하기 문</b></summary>
   <img width="390" height="146" alt="6_6" src="https://github.com/user-attachments/assets/56b0c424-95f7-4433-8821-67bbf5d89489" />
   <br>
   무한 반복하기 문에서는 Hamster Linetracing 함수를 통해 무한으로 햄스터가 선을 따라가는 코드를 수행한다.

</details>

***

## 7. 관련 내용
[**1. MAF(Moving Average Filter)**](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/MAF(Moing-Average-Filter))

[**2. Computer Vision**](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/Computer-Vision)

[**3. 4DoF Kinematics**](https://github.com/RoboidStudioLAB/Wiki_Image/wiki/4Dof-Kinematics(%EA%B8%B0%EA%B5%AC%ED%95%99))
<br>

<img width="10000000" alt="Image" src="https://github.com/user-attachments/assets/aececf51-c059-4081-9fa8-87de0162b0b0" />

<br><br>
