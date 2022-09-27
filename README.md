## RipCurrent
- Django를 이용한 웹사이트 생성
- 이안류란 해안으로 밀려들어오는 파도와 달리, 해류가 해안에서 바다쪽으로 급속히 빠져나가는 현상이다.
이안류는 해류의 폭이 좁고 유속이 빠른 해류로, 쉽게 말하면 거꾸로 치는 파도이다. 그렇기 때문에
이안류는 수영하는 사람까지도 먼 바다로 쓸어 나갈 수 있는 위험한 파도이며, 거꾸로 치는 공포의 파도라고도 불린다.
우리는 이러한 이안류의 위험성을 감지하고, 다가오는 여름철 많은 피서객들과 관광객들이 피서지를 가기 전 날씨를 알아보듯 가고자 하는
해수욕장의 이안류 지수를 사용자가 파악하여 사고를 미연에 방지해보자는 목적으로 이러한 웹 사이트를 제작

## 사용한 데이터
해양수산부에서 제공하는 이안류 정보를 JSON형태로 제공받음

## 데이터수집방법
- 관측은 30분에 한번씩 자동으로 크롤링하게 설정
- 윈도우에 탑재된 작업스케줄러를 이용하여 자동크롤링

## 데이터저장
크롤링하면서 동시에 DB에 저장하도록 설정

## 기타 데이터
- free templates 사용 (https://templatemo.com/tm-554-ocean-vibes)
- home버튼은 Bootstrap에서 사용 (https://www.w3schools.com/bootstrap5/bootstrap_buttons.php)

## 결과물
![웹사이트 시작화면](https://user-images.githubusercontent.com/108312250/192415183-e3231d35-47bc-4e20-8ea4-1f7835160a93.png)
![웹 사이트 구동 시 사용자의 현재위치 출력](https://user-images.githubusercontent.com/108312250/192415202-fac7a8ff-aa8b-4b4d-aa57-2ed320aac6e6.png)
![웹사이트 시작화면](https://user-images.githubusercontent.com/108312250/192415206-a9d831c0-ba73-4401-93bf-38a19c8ce6f4.png)
![해수욕장 선택 및 전국 해수욕장 위치](https://user-images.githubusercontent.com/108312250/192415209-63936cf7-a350-4ef4-8ede-f3034ff5bc9f.png)
![해수욕장 선택시 나오는 이안류 정보](https://user-images.githubusercontent.com/108312250/192415211-54a786f6-47c0-4977-9d4d-ea57136121bb.png)
