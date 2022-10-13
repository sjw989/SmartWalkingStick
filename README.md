# 💡프로젝트 소개

- **스마트 지팡이 시스템 개발**
- 시각 장애인 혹은 거동이 불편한 장애인을 위하여, 스마트 지팡이에 다양한 센서를 부착한 후 스마트 폰 등 디지털 기기와 연동을 통하여 최근 이슈화된 장애인 이동권 이슈와 관련하여 도움을 주고자한다.

# 🤼 구성원
[김수근](https://github.com/ILAPie)|[신지우](https://github.com/sjw989)| [김주용](https://github.com/Kim-JuYong)
|------------------------------------|-------------------------------------|-------------------------------------|
|![img](https://github.com/ILAPie.png?size=100?size=100) | ![img](https://github.com/sjw989.png?size=100?size=100) |![img](https://github.com/Kim-JuYong.png?size=100?size=100) |

# 🔑 구성도 및 주요 기능 

### 구성도
<img width="895" alt="image" src="https://user-images.githubusercontent.com/82700895/195525724-8a0b8aa2-ec06-43ca-b2e0-f9948ae83da8.png">


### Android

- 길 안내 및 주변 편의시설 안내 기능
- 객체 인식 모델을 활용한 혼잡도 안내 기능
- OCR API를 활용한 텍스트 안내 기능
- TTS API를 활용한 음성 안내 기능


### Arduino
- 초음파 센서를 활용한 장애물 감지 기능
- 서보 모터를 활용한 방향 지시 기능
- 모바일 어플리케이션과 연동을 위한 블루투스 기능과 버튼


# 🧸️ 사용법
Android APK

[앱 다운로드 바로가기](http://naver.me/FnifdpDC)

요구조건
- 안드로이드 OS
- 최소 조건: 안드로이드 SDK 버전 26 이상
# :pencil2: 회의내용
- 22.06.23(목) 
  1) 회의는 2주에 한 번 (회의시간에 머지) 
  2) 신지우 : 길찾기 기능 \
     김주용 : 앱 화면 분리, OCR 기능\
     김수근 : 센서 통신 및 동작 확인 
  3) 다음 회의 : 07.09(토) or 07.10(일)
  
- 22.07.10(일) 
  1) 중간발표 8/1까지 제출 (그전에 교수님께 심사받아서 그 서명받은 서류를 과사에 날짜맞춰서 제출해야함)
  2) 다음 회의 : 7/24(일) 20:00
  3) 각자 맡은거 최대한 완성시켜오기. 
  4) 신지우 : 지도가 꼭필요한가?, 시작지점은 무조건 현재위치 & 목적지는 리스트중에 선택 \
     김주용 : 실제디바이스에서 텍스트가 어떻게 읽힐지 예측이 안됨. 혼잡도 예측할 예정 \
     김수근 : 센서 통신 확인 완료, 하드웨어 구상

- 22.07.24(일)
  1) 각자 진행상황에 대한 소통
  2) 다음 회의 : 7/27(수) 20:00
  3) 중간보고서 통합을 위하여 각자 맡은 파트 작성해 올 것

- 22.07.27(수)
  1) 중간 보고서 작성 및 중간 평가표 작성을 위한 회의
  2) 다음 회의 : 미정
  3) 28일(목) 컨택 결과: 극찬 of 극찬.
                        최종발표 당일은 모두의 참석을 바람.
                        발표날 기기가 작동을 안 할 수 있으니, 미리 작동 영상을 촬영해두어
                        보여줄 수 있도록 할 것.

- 22.09.13(화)
  1) 아두이노 및 안드로이드 앱 통신 시도(I)
  2) 다음 회의 : 09.15(목)
  3) 아두이노 버튼 입력 시 Arduino bluetooth Controller로 문자가 입력되는 것 확인.
     SWS(SmartWalkingStick) 앱에서 블루투스(HC-06) 탐색 권한 획득 작업 중

- 22.09.15(목)
  1) 아두이노 및 안드로이드 앱 통신 시도(II)
  2) 다음 회의 : 미정
  3) SWS 앱을 통해 버퍼 값은 읽으나, 예상하지 못한 값을 읽어옴.
     Serial2.println()을 통해 문자를 전달하려 했으나, 실제론 버튼의 핀번호가 전송되는 것을 확인
     추가적인 분석의 필요성 
