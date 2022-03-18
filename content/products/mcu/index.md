---
title: "주 제어기 (MCU)"
subtitle: "Main Control Unit"
summary: "Main Control Unit"
authors: []
tags: []
categories: [ "board" ]
draft: false
weight: 4100

# Featured Image:
image:
  preview_only: true
---

{{< toc2 >}}

## MCU (NXT_H_001)

{{< figure src="mcu-nxt_h_001.png" caption="MCU (NXT_H_001)" >}}

- VMS 관리 제어 시스템
- 국토관리청 **ITS VMS 표준화 규격 적용**
- 한국도로공사 **VMS 표준화 규격 적용**
- **주제어유닛, 환경모니터링유닛, 전원공급장치로 구성**
- VMS 표출제어기와 TCP/IP(이더넷) 송수신 방식 적용

{{< figure src="mcu-overview.png" caption="관리부 구성도" >}}

{{< figure src="mcu-detail.png" caption="관리제어부 상세도" >}}

## 주제어 유닛 (MCU: Main Control Unit)

{{< figure src="mcu-board.png" caption="" >}}

### SPECIFICATION

항 목 | 내 용 | 비 고
:-: | :-: | :-:
PROCESSOR | Quad Core 2.0GHz 이상
저장장치 | SSD 128G | OS 및 프로그램
R T C | CALENDAR, TIME(BATTERY BACKUP)방식
COM 포트 | RS-232C 2PORT / DEBUG / 환경유닛 / 예비
이더넷포트 | 10/100M 이상 이더넷 포트 2개이상 | 전면부
DVI 포트 | VCU와 연결용 | 후면부
USB 포트 | USB 2.0 2포트 | 전면부
WATCHDOG | 프로그램 다운시 자동복구 기능
그래픽 LCD | 8인치 LCD 모니터 내장 / RGB방식 | 교체가능구조
OS | 임베디드 OS ( WIN 10 정품)
UPGRADE | VMS 주제어기 프로그램 원격 업그레이드
입력전압 | DC 12V
동작온도 | -10 ~ 50℃ 이상

## 환경 모니터링 유닛 (Status Board Unit)

{{< figure src="mcu-status.png" caption="" >}}

### SPECIFICATION

항 목 | 내 용 | 비 고
:-: | :-: | :-:
메인 프로세서 | 8BIT PROCESSOR 이상
메인 메모리 | 4KB 이상
데이터 메모리 | 4KB 이상
CPU CLOCK | 16MHz 이상
통신 포트 | RS-232C 포트 2개 이상
감시 기능 | 도어: 문열림(OFF), 닫힘(ON)
감시 기능 | 온도: -40℃ ~ 120℃ | 서브센서부 취득
감시 기능 | 습도: 0% ~ 100% | 서브센서부 취득
제어 기능 | 모듈용 직류전원공급장치 제어 (Remote Control) | DC HIGH : ON, LOW : OFF
제어 기능 | 함체 Fan 제어 | DC HIGH : ON, LOW : OFF<br>온도에따른 Fan 제어
제어 기능 | 함체 Fan 제어 | DC HIGH : ON, LOW : OFF<br>온도에따른 Heater 제어
제어 기능 | Spare Port | DC HIGH : ON, LOW : OFF
사용전압 | DC12V

## 직류전원공급장치 (Power Board)

{{< figure src="mcu-power.png" caption="" >}}

### SPECIFICATION

항 목 | 규 격 | 비 고
:-: | :-: | :-:
입력전압 | AC 220V 교류
입력전압 주파수 범위 | 60Hz (57~63Hz) ± 3.0㎐ × 단상
출력전압 | DC 12V
출력전압 전압조정 범위 | 고정
출력전압 리플 및 잡음 | 50mVp-p / 150mVp-p
출력전압 소비 전력 | 최대 200Watts

## 다운로드

종류 | 파일
---- | ----
카탈로그 | [NEXTONE-MCU-카탈로그_20220318.pdf](NEXTONE-MCU-카탈로그_20220318.pdf)
인증서 | [NEXTONE-MCU_방송통신기자재등의적합등록필증_20220310.pdf](NEXTONE-MCU_방송통신기자재등의적합등록필증_20220310.pdf)<br>[NEXTONE-MCU_방송통신기자재등(전자파적합성)시험성적서_20220310.pdf](NEXTONE-MCU_방송통신기자재등(전자파적합성)시험성적서_20220310.pdf)
