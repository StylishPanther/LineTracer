# Line Tracer

[단국대학교 MAZE](https://maze.co.kr) 라인 트레이서 개발 내용

1차 개발 기간 : 2016. 01 ~ 2016. 09

2차 개발 기간 : 2018. 07 ~ 2018. 09

3차 개발 기간 : 2018. 10 ~ 2018. 12

4차 개발 기간 : 2019. 07 ~ 2019. 09

## 로봇 설명

라인트레이서는 검정 바탕의 경기장에 그려진 흰 색 라인을 따라서 움직이는 마이크로 로봇입니다.
라인트레이서는 다음과 같은 세 부분으로 나뉠 수 있다.

- 로봇의 위치와 라인의 형태를 판별하는 센서부

- 센서에서 수집된 데이터를 분석하여 제어 명령을 내리는 제어부

- 로봇의 이동을 담당하는 구동부

라인 트레이서는 로봇 제작을 처음 시작하고 어려워하는 사람들에게 추천되는 로봇입니다. 다른 로봇에 비해 접근이 쉽지만 깊이 들어갈수록 역학, 제어, 신호 처리 등 다양한 분야의 지식을 필요로 하게 되며 최단 경로를 찾는 알고리즘에 따라 로봇의 성능이 다르게 나타나게 됩니다.

따라서 라인트레이서는 폐곡선 내의 주행 기록을 단축시키는 것을 목표로 합니다.

## 대회 결과

[대회 영상 1](https://www.youtube.com/watch?v=NpS87icKOfI) ,  2016 제 19회 서울시립대 전국 라인트레이서 경연대회

[대회 영상 2](https://www.youtube.com/watch?v=NpS87icKOfI) ,  2018 제 15회 단국대학교 전국 마이크로로봇 경연대회

[대회 영상 3](https://youtu.be/VRm0IGDmIaM) ,  2018 제 34회 전 일본 마이크로로봇 경연대회 [[PDF]](./PDF/2018_일본 기록인증서.pdf)

[대회 영상 4](https://www.youtube.com/watch?v=eTKhToyow0Y) ,  2018 제 21회 서울시립대 전국 라인트레이서 경연대회 [[PDF]](./2018_서울시립대학교_EXPERT부문_장려상.pdf)

[대회 영상 5](https://www.youtube.com/watch?v=kEDe5cqG3js) ,  2019 제 22회 서울시립대 전국 라인트레이서 경연대회 [[PDF]](./PDF/2019_서울시립대학교_ExpertDC부문_장려상.pdf)

## 작품 목표    

- 검은 바탕 위의 흰 선으로 되어있는 폐곡선을 가장 빠른 시간에 주행하는 것.

### 하드웨어 품목  

|Hardware Type|Model Name|Datasheet|  
|:---:|:---:|:---:|
|DSP|TMS320F2809PZA|[PDF](./PDF/tms320f2809pza.pdf)|  
|Infrared Sensor|SI-5312H, ST-3811|[PDF](SI-5312H.pdf), [PDF](./PDF/ST3811.pdf)|  
|Amplifier|ULN2803APG|[PDF](./PDF/ULN2809APG.pdf)|
|Motor|Maxon Motor RE-25 (118751)|[PDF](./EN-21-146.pdf)|    
|Motor Drive|LMT18200T|[PDF](./PDF/LMT18200T.pdf)|  
|Encoder|MR Encoder (225805)|[PDF](./PDF/EN-21-478.pdf)|
|Regulator|LM2576|[PDF](./PDF/LM2576_datasheet.pdf)|


### 개발환경 

|Tool Name|Description|  
|:---:|:---:|  
|Source Insight|프로젝트 텍스트 에디터|

### SDK

|SDK|Description|  
|:---:|:---:|  
|IQmath Library| IQmath 제공|
|DSP280x|TMS320F280x Series Framework 제공|  


## 개발 내용

## HARDWARE

## SOFTWARE
