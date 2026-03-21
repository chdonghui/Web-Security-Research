# What is OSI?

ISO: International Organization for Standardization (국제표준화기구)
- 1947년 설립된 설림된 비정부 조직 (NGO)
- 전 세계 160여개국 국가 표준 기관이 모여 만든 기구
- ISO는 그리스어 'isos', '동일하다'라는 뜻에서 유래함
  - '아이소' 또는 '이소'라고 읽음.

OSI: Open System Interconnection (개방형 시스템 상호 연결)
- 상이한 컴퓨터 시스템이 서로 통신할 수 있는 표준을 제공합니다.
- 국제표준화기구에서 만든 개념 모델입니다.

### What is OSI Model?

OSI 모델이란 개방형 시스템 상호 연결(Open System Interconnection)로 국제표준화기구(ISO)에서 만든 모델입니다.

네트워크에 필요한 역할 및 개념을 7개의 계층으로 나누고 있습니다.

### OSI 7 Layer Table

| # | Layer | Protocols | PDU | 계층명 |
|:-:|-------|-----------|-----|--------|
| 7 | Application | HTTP · SMTP · POP3 | Data | 응용 계층 |
| 6 | Presentation | ZIP · TLS · ASCII | Data | 표현 계층 |
| 5 | Session | RTP · RTCP | Data | 세션 계층 |
| 4 | Transport | TCP · UDP | Segment | 전송 계층 |
| 3 | Network | IP · ICMP | Packet | 네트워크 계층 |
| 2 | Data Link | MAC · ICMP | Frame | 데이터 링크 계층 |
| 1 | Physical | Cable · NIC | Bit | 물리 계층 |

# Index

### 7 Application

7계층 - Application Layer (응용 계층)
OSI 모델에서 가장 상위 계층으로, 응용 프로세스가 네트워크에 접근할 수 있는 유일한 수단입니다. 사용자와 직접 맞닿아 있는 계층으로, 아래 계층들이 제공하는 모든 서비스를 직접 활용합니다. 통신 상대 식별, 서비스 품질 결정, 보안 인증 등의 기능을 담당합니다.

### 6 Pressentation

6계층 - Presentation Layer (표현 계층)
데이터의 표현 방식을 담당합니다. 서로 다른 시스템 간에 데이터 형식이 달라도 문제없이 통신할 수 있도록 번역해주는 역할입니다. 전송 문법 협상, 데이터 변환, 압축 등의 기능을 수행합니다.

### 5 Session

5계층 - Session Layer (세션 계층)
두 시스템 간의 대화(세션)를 열고, 유지하고, 닫는 역할입니다. 데이터 교환을 체계적으로 조율하고 동기화 지점을 설정해서 오류 복구를 지원합니다.

### 4 Transport

4계층 - Transport Layer (전송 계층)
세션 엔티티 간에 데이터를 신뢰성 있게 전달하는 계층입니다. 라우팅이나 중계는 신경 쓰지 않고 오직 종단 간(end-to-end) 전송에만 집중합니다. 흐름 제어, 오류 감지, 세그먼트 분할/재조립 등을 담당합니다.

### 3 Network

3계층 - Network Layer (네트워크 계층)
여러 네트워크를 가로질러 데이터를 전달하는 계층입니다. 라우팅과 중계를 담당하며, 전송 계층에게 경로 결정에 대한 부담을 없애줍니다. IP 주소 기반으로 최적 경로를 찾습니다.

### 2 Data Link

2계층 - Data Link Layer (데이터 링크 계층)
직접 연결된 네트워크 장치 간의 데이터 전송을 담당합니다. 물리 계층에서 발생하는 오류를 감지하고 수정하며, 프레임 단위로 데이터를 묶어 전송합니다.

### 1 Physical

1계층 - Physical Layer (물리 계층)
비트 스트림을 실제 물리적 매체(케이블, 전파 등)로 전송하는 계층입니다. 전기적·기계적·기능적 특성을 정의하며, 연결 설정, 해제, 비트 전송을 담당합니다.

# Reference

- C.I.K (2025). 그림으로 개념잡는 네트워크 입문. 앤써북.
- 조남호 (2019.07.17 Published). ISO는 '아이소'라고 읽어주세요!. Samsung SDS. [URL](https://www.samsungsds.com/kr/insights/1233835_4627.html)
- Cloudflare (2026.03.13 Accessed). OSI 모델이란?. [URL](https://www.cloudflare.com/ko-kr/learning/ddos/glossary/open-systems-interconnection-model-osi/)
- ISO/IEC (1994). Information technology — Open Systems Interconnection — Basic Reference Model. ISO. ISO/IEC 7498-1:1994. [URL](https://www.iso.org/standard/20269.html)