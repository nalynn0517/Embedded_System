# 임베디드시스템 1주차 요약
## 목차
1. [MCU와 SoC (마이크로컨트롤러와 시스템 온 칩)](#1-mcu와-soc-마이크로컨트롤러와-시스템-온-칩)
2. [컴퓨터 기술 용어 (Computer Technology Terms)](#2-컴퓨터-기술-용어-computer-technology-terms)
3. [임베디드 소프트웨어 개요](#3-임베디드-소프트웨어-개요)
4. [임베디드 시스템](#4-임베디드-시스템)

---
### 1. **MCU와 SoC (마이크로컨트롤러와 시스템 온 칩)**
- **MCU (Microcontroller)**: 마이크로컨트롤러는 CPU, 메모리(RAM, ROM 또는 플래시 메모리), 입출력 포트(I/O)를 단일 칩에 통합한 소형 컴퓨터
  - MCU는 주로 전자 기기나 자동차, 가전제품 제어 등 특정 작업을 수행하는 임베디드 시스템에서 사용 - 저전력 소모, 비용 효율성, 단일 목적 수행에 최적화된 설계)
  - Arduino 보드와 같은 소형 컴퓨팅 장치에서 주로 사용되며, 단순한 작업을 반복적으로 처리하는 데 적합
  
- **SoC (System on Chip)**: SoC는 하나의 칩에 CPU, 메모리, 입출력 장치뿐만 아니라 GPU, DSP, 모뎀, 보안 모듈 등 복잡한 시스템 구성 요소를 통합한 고성능 시스템
  - SoC는 주로 스마트폰, 태블릿, IoT 장치 등에서 사용되며, 다수의 작업을 동시에 수행할 수 있는 다목적 시스템으로 설계
  - 장점: 고성능과 통합성 덕분에 다양한 작업을 동시에 처리하며, 전력 효율성과 공간 절약이 가능
  - 단점: MCU에 비해 복잡한 설계가 필요, 전력 소모 大

### 2. **컴퓨터 기술 용어 (Computer Technology Terms)**
- **CPU (Central Processing Unit)**: CPU는 컴퓨터 시스템의 핵심 처리 장치, 명령어를 해석하고 실행하는 역할
  - ALU(산술논리연산장치), 제어 장치 등으로 구성 => 컴퓨터나 전자 기기에서 모든 연산과 제어를 담당
  
- **MPU (Microprocessor)**: MPU는 CPU의 기능을 단일 반도체 칩에 통합한 형태, 컴퓨터뿐만 아니라 다양한 전자 기기에 사용
  - 소형화된 CPU (ex: 인텔 코어 시리즈나 AMD 라이젠 같은 제품)

- **MCU (Microcontroller)**: MCU는 CPU, 메모리, 입출력 장치를 하나의 칩에 통합한 소형 컴퓨터 시스템, 특정 작업에 최적화
  - ex) Arduino와 같은 마이크로컨트롤러 - 간단한 전자 프로젝트나 임베디드 시스템에서 자주 사용

- **SoC (System on Chip)**: SoC는 MCU보다 더 복잡하고 고성능인 시스템, 스마트폰이나 태블릿 같은 고성능 기기에서 사용
  - 프로세서, 메모리, 그래픽 처리 장치 등을 모두 하나의 칩에 통합하여 다양한 기능을 효율적으로 처리

### 3. **임베디드 소프트웨어 개요**
- **임베디드 시스템**: 임베디드 시스템은 특정한 기능을 수행하기 위해 설계된 하드웨어와 소프트웨어의 결합체
  - 의료 기기, 로봇 청소기, 스마트폰 등의 제품에 내장, 주로 대량 생산 제품에 포함되어 특정 목적을 수행
  - 하드웨어와 밀접하게 연관, 다양한 장치에서 매우 중요한 역할

- **임베디드 소프트웨어**: 임베디드 소프트웨어는 하드웨어를 제어하는 소프트웨어로 정의, '내장된' 소프트웨어라는 의미 보유
  - 초기: 어셈블리 언어를 사용해 하드웨어를 직접 제어
  - 최근: 고급 프로그래밍 언어와 다양한 운영체제를 통해 개발
  - 일반적인 소프트웨어와 달리, 하드웨어를 직접적으로 제어

### 4. **임베디드 시스템**
- **임베디드 시스템**: 임베디드 시스템은 특정 작업에 최적화된 소형 컴퓨터 시스템(ex. 자동차의 ABS 시스템이나 가전제품의 제어 패널)
  - 장점: 특정한 목적을 위해 설계된 시스템을 포함 - 저전력 소모, 소형화된 설계, 그리고 특정 작업을 효율적으로 처리하는 능력 보유
  - 단점: 시스템 업그레이드가 어려울 수 있음

- **응용 분야**: 자동차, 의료, 가전제품, 산업 자동화 등 다양한 분야에 사용 (ex. 자동차의 엔진 제어 시스템이나 의료 기기의 환자 모니터링 시스템, 가정용 로봇 청소기)

### 결론
- MCU : 주로 단순하고 저전력인 임베디드 시스템에 사용되며, SoC는 복잡한 작업을 처리하는 고성능 시스템
- 임베디드 소프트웨어 : 하드웨어를 직접적으로 제어하는 소프트웨어로, 다양한 산업에서 중요한 역할을 함
- 임베디드 시스템 : 자동차, 가전제품, 의료 기기 등에서 실시간 반응과 최적화된 작업 수행을 위해 필수적인 요소

<hr/>

# 1주차 수업 후기

### 새롭게 알게 된 점 
우선, MCU와 SoC에 대해 간단히 알고 있던 것들을 이번에 좀 더 깊이 있게 배울 수 있었다. 특히 IoT나 스마트 디바이스에서 중요한 역할을 하는 SoC가 단순한 프로세서가 아니라, CPU뿐만 아니라 GPU, 메모리, 다양한 입출력 장치들이 통합된 시스템이라는 것을 알게 되어 놀라웠다. 또한, 임베디드 시스템이라는 개념이 단순히 특정 장치에만 국한되는 것이 아니라, 일상생활에서 우리가 사용하는 다양한 기기, 예를 들어 스마트폰, 자동차의 제어 시스템, 가전제품 등에 널리 적용되고 있다는 사실을 배우게 되었다. 이러한 시스템들이 어떻게 실시간 반응성과 효율성을 유지하면서도 최적의 성능을 발휘하는지를 알게 된 것은 매우 유익했다.
### 느낀 점 
하드웨어나 전자 시스템에 대해 아직 부족한 부분이 많아 이번 학습을 통해 이러한 기술에 대한 이해를 점점 더 넓혀갈 수 있을 것이라는 기대감이 생겼다. IoT나 스마트 디바이스와 관련된 기술을 조금 더 깊이 있게 다룰 수 있게 된 점에서 즐거운 부분도 있으며, 이를 통해 실제로 일상 속에서 이러한 시스템들이 어떻게 작동하고 있는지를 더 잘 이해할 수 있을 것 같다. 앞으로도 이와 같은 기술적 지식을 쌓아가면서, 내가 부족한 하드웨어 관련한 지식도 함께 보충해 나갈 수 있기를 기대하고 있다.
