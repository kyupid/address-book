# 주소록 프로젝트

## 프로젝트 개요
이 프로젝트는 자바를 사용하여 주소록 애플리케이션을 구현하는 것을 목표로 합니다. 주소록은 사용자가 연락처 정보를 저장, 조회, 수정, 삭제할 수 있는 기능을 제공합니다.

## 프로젝트 목적
- **자바 프로그래밍 실력 향상**: 자바의 기본적인 문법과 객체지향 프로그래밍(OOP) 개념을 실제 프로젝트에 적용함으로써 실력을 향상시킵니다.
- **자료구조 구현 경험**: 표준 라이브러리가 아닌 직접 자료구조를 구현함으로써 자료구조에 대한 이해를 깊게 합니다.
- **소프트웨어 개발 과정 이해**: 실제 소프트웨어 개발 과정에서 겪을 수 있는 문제 해결 과정을 경험합니다.

## 기능 요구사항

### 1. 자료구조 직접 구현
- **연락처 저장 구조**: 연락처 정보를 저장하기 위한 자체 구현된 데이터 구조 (예: 링크드 리스트, 트리 구조)를 개발합니다.
- **효율성 고려**: 데이터 추가, 삭제, 검색 등의 연산이 효율적으로 이루어질 수 있도록 구조를 설계합니다.

### 2. CRUD 기능
- **생성(Create)**: 새로운 연락처를 추가할 수 있는 기능.
  - 필수 정보 입력: 이름, 전화번호, 이메일 등.
  - 선택 정보 입력: 주소, 생일, 메모 등.
- **읽기(Read)**: 저장된 연락처 목록을 조회할 수 있는 기능.
  - 전체 목록 조회
  - 특정 조건에 따른 조회 (예: 이름으로 검색)
- **수정(Update)**: 기존 연락처의 정보를 수정할 수 있는 기능.
  - 특정 연락처 선택 후 정보 수정
- **삭제(Delete)**: 저장된 연락처를 삭제할 수 있는 기능.
  - 특정 연락처 선택 후 삭제

### 3. 콘솔 인터페이스
- **메인 메뉴**: 사용자가 주요 기능을 선택할 수 있는 콘솔 메뉴를 제공합니다.
- **입력 안내**: 사용자가 정보를 입력할 때 명확한 안내를 제공합니다.
- **결과 출력**: 연락처 조회 및 기타 작업의 결과를 콘솔에 출력합니다.

### 추가 기능
- **데이터 유효성 검사**: 입력된 데이터의 형식과 유효성을 검증합니다.
  - 전화번호, 이메일 형식 검증
- **검색 기능**: 이름, 이메일 등의 기준으로 연락처를 검색할 수 있는 기능을 구현합니다.
- **사용자 친화적 인터페이스**: 인터페이스가 직관적이고 사용하기 쉽도록 설계합니다.
- **예외 처리**: 잘못된 입력이나 시스템 오류에 대한 적절한 예외 처리를 구현합니다.
- **단위 테스트**: 핵심 기능에 대한 단위 테스트를 작성하여 프로그램의 안정성을 검증합니다.

프로젝트 일정을 계획할 때, 각 단계에 충분한 시간을 할당하는 것이 중요합니다. 여기서 제시한 1달 기간 동안의 일정 계획은 다음과 같습니다:

## 전체 프로젝트 일정 (총 기간: 1달)

### 1주차: 자료구조 구현
- **목표**: 필요한 자료구조를 설계하고 구현합니다.
- **주요 활동**:
  - 자료구조 선택: 연락처 정보 저장에 가장 적합한 자료구조(예: 연결 리스트, 트리, 해시 테이블)를 결정합니다.
  - 구현: 선택된 자료구조를 자바로 구현합니다.
  - 기본 테스트: 기본적인 작동을 확인하기 위한 간단한 테스트를 수행합니다.
- **팁**: 자료구조의 효율성과 확장 가능성을 고려하여 설계하세요.

### 2주차: CRUD 기능
- **목표**: 연락처에 대한 생성(Create), 읽기(Read), 수정(Update), 삭제(Delete) 기능을 구현합니다.
- **주요 활동**:
  - 기능 구현: 각 CRUD 작업을 위한 메소드를 구현합니다.
  - 인터페이스 연동: 콘솔 인터페이스와 CRUD 기능을 연동합니다.
  - 기능 테스트: 각 CRUD 기능이 제대로 작동하는지 확인합니다.
- **팁**: 사용자 친화적인 인터페이스와 명확한 사용자 안내 메시지를 제공하세요.

### 3주차: 추가 기능 및 사용자 인터페이스
- **검색 기능 및 데이터 유효성 검사 추가**
- **콘솔 인터페이스 개선**: 사용자 경험을 개선하기 위해 인터페이스를 다듬습니다.

### 4주차: 최종 검토 및 테스트
- **예외 처리 및 오류 수정**
- **단위 테스트**: 각 기능에 대한 광범위한 테스트를 수행합니다.
- **문서화 및 정리**: 코드 주석 추가, README 파일 업데이트 등

## 참고사항
- **유연성 유지**: 프로젝트 진행 중에 일정이 변경될 수 있으니 유연하게 대처하세요.
- **정기적인 검토**: 주차별 목표 달성도를 확인하고 필요한 조정을 하세요.
- **문제 해결**: 문제가 발생하면 신속하게 해결 방안을 모색하세요.

## 프로젝트 구조
- `src`: 소스 코드를 포함하는 디렉토리.
- `test`: 단위 테스트 코드를 포함하는 디렉토리.
- `doc`: 프로젝트 문서화를 위한 디렉토리.

## 개발 환경
- **언어**: Java
- **개발 도구**: IntelliJ IDEA, Eclipse 등 Java IDE
- **버전 관리**: Git

---
