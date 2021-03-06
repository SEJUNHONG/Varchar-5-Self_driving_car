![](https://img.shields.io/github/license/okyou1000/self-driving-car-project)

![stars](https://img.shields.io/github/stars/okyou1000/self-driving-car-project)

![fork](https://img.shields.io/github/forks/okyou1000/self-driving-car-project)

#  카메라를 활용한 자율주행자동차 물체 인식 구현 (파이널 프로젝트)

### 팀명 : Varchar(5)

### 팀원 : **김동현**, 노용철, **정성훈**, 홍세준



## 프로젝트 주제 및 내용:

자율주행 자동차는 인간의 개입 없이 자동으로 주행할 수 있는 자동차이다. 레이더, LiDAR, GPS, 카메라로 주위의 환경을 인식하여 목적지를 지정하는 것만으로 자율적으로 주행을 할 수 있다. 여기서 핵심은 **LiDAR**와 **카메라 센서**를 통해 들어오는 영상 정보를 인식한 후 객체를 탐지하여 상황에 맞게 자동차에게 명령을 전달하여 자동차를 제어하는 것이 핵심이다. 



## 주제선정 및 배경

이번 프로젝트에서는 카메라로 들어온 영상 정보를 활용하여 Object Detection을 하는게 최우선 목표이다. 다양한 모델들을 통해 차량과 차선등의 주변 환경 detection을 해보고 정확도가 가장 높은 model을 선정한다. 이후, 최종 model 선정 후 강화학습을 통해 추가적으로 model을 향상시킨 후 라즈베리파이를 통해 명령어를 전달한다. 



### 결과의 유용성

- 소형화된 LiDAR센서와 고화질의 카메라 모듈을 통해 프로토 타입의 자율주행차를 제작하여 현업에서의 활용 가능성을 기대해보고 이를 바탕으로 무인 배송차, 방범용 로봇 등 무인화 가능한 전반적인 산업에 응용할 수 있다. 또한 최근 이슈화 되고 있는 어린이 보호구역에서의 사고 예방 등 산업을 떠난 일상의 안전에도 기여할 것으로 예상된다.

