# 정처기 필수 암기 363선

## 제 1 과목 소프트웨어 설계

### 소프트웨어 공학
- 소프트웨어의 위기를 극복하기 위한 방안으로 연구된 학문
- 소프트웨어의 개발, 운용, 유지보수에 대한 체계적인 접근 방법
- 소프트웨어의 품질과 생산성을 향상시킬 목적
- 경제적인 비용을 들여 신뢰성 높은 소프트웨어를 개발하기 위해 공학적 원리를 정립하고 이를 적용하는 것

### 소프트웨어 공학의 기본 원칙
- 현대적인 프로그래밍 기술을 계속적으로 적용해야 함
- 개발된 소프트웨어 품질이 유지되도록 지속적으로 검증해야 함
- 소프트웨어 개발 관련 사항 및 결과에 대한 명확한 기록 유지

### 폭포수 유형 (Waterfall Model)
- 이전 단계로 돌아갈 수 없다는 전제하에 각 단계를 확실히 매듭짓고 그 결과를 철저히 검토해 승인 과정을 거친 후 다음 단계 진행하는 개발 방법론
- 보헴(Boehm)이 제시한 고전적 생명 주기 모형
- 가장 오래되고 가장 폭넓게 사용된 전통적인 소프트웨어 생명 주기 모형
- 개발 과정에서 발생하는 요구사항 반영 어려움

### 나선형 모형 (Sprial Model, 점진적모형)
- 보헴이 제안한 것으로, 폭포수 모형과 프로토타입 모형의 장점에 위험 분석 기능을 추가한 모형
- 나선을 따라 돌듯 여러 번의 소프트웨어 개발 과정을 거쳐 점전직으로 완벽한 최종 소프트웨어를 개발하는 것
- `계획 수립 -> 위험 분석 -> 개발 및 검증 -> 고객 평가` 과정이 반복적으로 수행됨

### 애자일 모형(Agile Model)
- 고객의 요구사항 변화에 유연하게 대응할 수 있도록 일정한 주기를 반복하며 개발 과정을 진행
- 애자일 모형을 기반으로 하는 소프트웨어 개발 모형
    - 스크럼(Scrum)
    - XP(eXtreme Programming)
    - 칸반(Kanban)
    - 린(Lean)
    - 크리스탈(Crystal)
    - ASD(Adaptive Software Development)
    - 기능 중심 개발(FDD; Feature Driven Development)
    - DSDM(Dynamic System Development Method)
    - DAD(Disciplined Agile Delivery)

### 애자일 개발 4가지 핵심 가치
- 프로세스와 도구보다는 개인과 상호작용에 더 가치를 둠
- 방대한 문서보다는 실행되는 SW에 더 가치를 둠
- 계약 협상보다는 고객과 협업에 더 가치를 둠
- 계획을 따르기 보단 변화에 반응하는 것이 더 가치 있음

### 스크럼(Scrum) 기법의 주요 용어
- 스크럼 마스터(Scrum Master)
    - 스크럼 프로세스를 따르고, 팀이 스크럼을 효과적으로 활용할 수 있도록 보장하는 역할
- 제품 백로그(Product Backlog)
    - 스크럼 팀이 해결해야 하는 목록으로 소프트웨어 요구사항, 아키텍처 정의 등이 포함됨
- 스프린트(Sprint)
    - 하나의 완성된 최종 결과물을 만들기 위한 주기로 보통 2 ~ 4주 정도의 기간 내에서 진행함
- 속도(Velocity)
    - 한 번의 스프린트에서 한 팀이 어느 정도의 제품 백로그를 감당할 수 있는지에 대한 추정치

### XP(eXtreme Programming)
- 수시로 발생하는 고객의 요구사항에 유연하게 대응하기 위해 고객의 참여와 개발 과정의 반복을 극대화해 개발 생산성을 향상시키는 방법
- 짧고 반복적인 개발 주기, 단순한 설계, 고객의 적극적인 참여를 통해 소프트웨어를 빠르게 개발하는 것을 목적
- 자동화된 테스팅 도구를 사용해 테스트를 지속적으로 수행

### XP의 핵심 가치
- 의사소통(Communication)
- 단순성(Simplicity)
- 용기(Courage)
- 존중(Respect)
- 피드백(Feedback)

### XP의 주요 실천 방법
- Pair Programming(짝 프로그래밍)
    - 다른 사람과 함께 프로그래밍을 수행함으로써 개발에 대한 책임을 공동으로 나눠 갖는 환경을 조성
- Collective Ownership(공동 코드 소유)
    - 개발 코드에 대한 권한과 책임을 공동으로 소유함
- Continuous Integration(지속적인 통합)
    - 모듈 단위로 나눠서 개발된 코드들은 하나의 작업이 완료될 때마다, 지속적으로 통합됨
- Refactoring(리팩토링)
    - 프로그램 기능의 변경 없이, 단순화, 유연성 강화 등을 통해 시스템의 내부 구조를 재구성

### 현행 시스템 파악 절차
- 1단계 : 시스템 구성, 시스템 기능, 시스템 인터페이스 파악
- 2단계 : 아키텍처 구성, 소프트웨어(DBMS, 운영체제 등) 구성 파악
- 3단계 : 하드웨어 구성, 네트워크 구성 파악

### DBMS 분석 시 고려사항
- 가용성
- 성능
- 기술 지원
- 상호 호환성
- 구축 비용

### WAS(Web Application Server)
- 정적인 콘텐츠 처리를 하는 웹 서버와 달리 사용자의 요구에 따라 변하는 동적인 콘텐츠를 처리하기 위해 사용되는 미들웨어
- 종류 : Tomcat, GlassFish, JBoss, Jetty, JEUS, Resin, WebLogic, WebSphere 등

### 비 기능 요구사항
- 성능 요구사항 : 처리 속도 및 시간, 처리량 등의 요구사항
- 보안 요구사항 : 시스템의 데이터 및 기능, 운영 접근을 통제하기 위한 요구사항
- 품질 요구사항 : 품질 평가 대상에 대한 요구사항

### 요구사항 개발 프로세스
```
도출(Elicitation) -> 분석(Analysis) -> 명세(Specification) -> 확인(Validation)
```

### 요구사항 분석
- 소프트웨어 개발의 실제적인 첫 단계로 개발 대상에 대한 사용자의 요구사항을 이해하고 문서화(명세화) 하는 활동을 의미
- 사용자의 요구를 정확하게 추출해 목표를 정하고, 어떤 방식으로 해결할 것인지를 결정
- 사용자 요구의 타당성을 조사하고 비용과 일정에 대한 제약을 설정
- 개발 대상에 대한 사용자의 요구사항 중 명확하지 않거나 모호하여 이해되지 않는 부분을 발견하고 이를 걸러내기 위한 과정
- 사용자의 요구사항은 예외가 많고 지속적으로 변하므로 열거와 구조화가 어려움
- 내용이 중복되거나 하나로 통합되어야 하는 등 서로 상충되는 요구사항이 있으면 이를 중재하는 과정
- 요구사항 분석을 위해 UML(Unified Modeling Language), 자료 흐름도(DFD), 자료 사전(DD), 소단위 명세서(Mini-Spec.), 개체 관계도(ERD), 상태 전이도(STD), 제어 명세서 등의 도구 이용

### 기능 요구사항
- 시스템이 무엇을 하는지, 어떤 기능을 하는지에 대한 사항
- 시스템의 입력이나 출력으로 무엇이 포함되어야 하는지, 시스템이 어떤 데이터를 저장하거나 연산을 수행해야 하는지에 대한 사항
- 시스템이 반드시 수행해야 하는 기능
- 사용자가 시스템을 통해 제공받기를 원하는 기능

### 요구사항 명세 기법
```
구분        |       정형 명세 기법      |       비정형 명세 기법        |
기법        | 수학적 원리 기반          | 상태/기능/객체 중심
            | 모델 기반                | 
작성 방법   | 수학적 기호, 정형화된 표기법| 자연어를 기반으로 작성
            |                          | 다이어그램으로 작성
특징        | 요구사항 정확, 간결 표현  | 일관성이 떨어짐
            |                          | 의사소통이 용이함
종류        | VDM,Z,Petri-net,CSP 등   | FSM, Decision Table, ER 모델링, 
            |                           | State Chart(SADT) 등
```

### 요구사항 확인(요구사항 검증)
- 분석가가 요구사항을 정확하게 이해한 후 요구사항 명세서를 작성했는지 확인(Validation)하는 것이 필요
- 요구사항이 실제 요구를 반영하는지, 서로 상충되는 요구사항은 없는지 등을 점검
- 개발이 완료된 후, 문제가 발견되면 재작업 비용이 발생할 수 있으므로 요구사항 검증은 매우 중요
- 요구사항 검증 과정을 통해 모든 문제를 확인할 수 있는 것은 아님

### 자료 흐름도의 구성 요소
- 이 내용은 사진을 통해 알려주자

### 자료 사전의 표기 기호
```
기호           |        의미
=              | 자료의 정의 : ~로 구성되어 있다(is composed of)
+              | 자료의 연결 : 그리고(and)
()             | 자료의 생략 : 생략 가능한 자료(Optional)
[|]            | 자료의 선택 : 또는(or)
{}             | 자료의 반복 : Iteration of
* *            | 자료의 설명 : 주석(Comment)
```

### SADT
- SoftTech 사에서 개발한 구조적 분석 및 설계 도구
- 블록 다이어그램을 채택한 자동화 도구

### UML
- 시스템 분석, 설계, 구현 등 시스템 개발 과정에서 시스템 개발자와 고객 또는 개발자 상호간 의사소통이 원할하게 이루어지도록 표준화한 대표적인 객체지향 모델링 언어
- 구성 요소 : 사물(Things), 관계(Relationships), 다이어그램(Diagram)

### HIPO
- 시스템의 분석 및 설계나 문서화할 때 사용되는 기법으로, 시스템 실행 과정인 입력, 처리, 출력의 기능을 나타냄
- 하향식 소프트웨어 개발을 위한 문서화 도구
- 기호, 도표 등을 사용하므로 보기 쉽고 이해가 쉬움
- 기능과 자료의 의존 관계를 동시 표현 가능
- 시스템의 기능을 여러 개의 고유 모듈들로 분할하여 이들 간 인터페이스를 계층 구조로 표현한 것을 HIPO Chart라고 함
- HIPO Chart의 종류 : 가시적 도표(Visual Table of Contents), 총체적 도표(Overview Diagram), 세부적 도표(Detail Diagram)

### 의존(Dependency) 관계
- 연관 관계와 같이 사물 사이 서로 연관은 있으나 필요에 의해 서로에게 영향을 주는 짧은 시간 동안만 연관을 유지하는 관계를 의미
- 일반적으로 한 클래스가 다른 클래스를 오퍼레이션의 매개변수로 사용하는 경우 나타나는 관계

### 실체화(Realization) 관계
- 사물이 할 수 있거나 해야 하는 기능(오퍼레이션, 인터페이스)로 서로를 그룹화 할 수 있는 관계를 표현
- 한 사물이 다른 사물에게 오퍼레이션을 수행하도록 지정하는 의미적 관계

### 일반화(Generalization) 관계
- 하나의 사물이 다른 사물에 비해 더 일반적인지 구체적인지 표현
- 예를 들어 차는 버스, 트럭, 택시보다 일반적인 개념이고 반대로 버스, 트럭, 택시는 차보다 구체적인 개념

### 스테레오 타입(Stereotype)
- UML에서 표현하는 기본 기능 외에 추가적인 기능을 표현하기 위해 사용
- 길러멧(Guilemet)이라고 부르는 겹화살괄호(<<>>) 사이에 표현할 형태를 기술

### 구조적(정적) 다이어그램
- 클래스 다이어그램
    - 클래스와 클래스가 가지는 속성, 클래스 사이의 관계를 표현하며, 시스템의 구조를 파악하고 구조상의 문제점을 도출할 수 있음
- 객체(Object) 다이어그램
    - 클래스에 속한 사물(객체)들, 즉 인스턴스를 특정 시점의 객체와 객체 사이의 관계로 표현하며, 구현 단계에서 사용됨
- 컴포넌트 다이어그램
    - 실제 구현 모듈인 컴포넌트 간의 관계나 컴포넌트 간의 인터페이스를 표현하며, 구현 단계에서 사용됨
- 배치(Deployment) 다이어그램
    - 결과물, 프로세스, 컴포넌트 등 물리적 요소들의 위치를 표현하며, 구현 단계에서 사용됨
- 복합체 구조(Composite Structure) 다이어그램
    - 클래스나 컴포넌트가 복합 구조를 갖는 경우 그 내부 구조를 표현함
- 패키지 다이어그램
    - 유스케이스나 클래스 등의 모델 요소들을 그룹화한 패키지들의 관계를 표현

### 사용자 인터페이스(UI)의 특징
- 사용자의 편리성과 가독성을 높임으로써 작업 시간을 단축시키고 업무에 대한 이해도를 높여줌
- 사용자 중심으로 설계되어 사용자 중심의 상호 작용이 되도록 함
- 수행 결과의 오류를 줄임
- 사용자의 막연한 작업 기능에 대해 구체적인 방법을 제시해 줌

### 행위(동적) 다이어그램
- 유스케이스 다이어그램
    - 사용자의 요구를 분석하는 것으로 기능 모델링 작업에 사용
- 순차(Sequence) 다이어그램
    - 상호 작용하는 시스템이나 객체들이 주고받는 메시지를 표현
- 커뮤니케이션 다이어그램
    - 순차 다이어그램과 같이 동작에 참여하는 객체들이 주고받는 메시지를 표현하는데, 메시지뿐만 아니라 객체들 간의 연관까지 표현
- 상태(State) 다이어그램
    - 하나의 객체가 자신이 속한 클래스의 상태 변화 혹은 다른 객체와의 상호 작용에 따라 상태가 어떻게 변화하는지를 표현하는 것으로, 럼바우 객체지향 분석 기법에서 동적 모델링에 활용
- 활동(Activity) 다이어그램
    - 시스템이 어떤 기능을 수행하는지 객체의 처리 로직이나 조건에 따른 처리의 흐름을 순서에 따라 표현함
- 상호작용 개요(Interaction Overview) 다이어그램
    - 상호작용 다이어그램 간 제어 흐름을 표현
- 타이밍 다이어그램
    - 객체 상태 변화와 시간 제약을 명시적으로 표현

### 유스케이스 다이어그램의 구성 요소
- 시스템 / 시스템 범위
    - 시스템 내부에서 수행되는 기능들을 외부 시스템과 구분하기 위해 시스템 내부의 유스케이스들을 사각형으로 묶어 시스템의 범위를 표현
- 액터  
`시스템과 상호작용을 하는 모든 외부 요소로, 사람이나 외부 시스템을 의미`  
    - 주액터 : 시스템을 사용함으로써 이득을 얻는 대상으로, 주로 사람이 해당
    - 부액터 : 주액터의 목적 달성을 위해 시스템에 서비스를 제공하는 외부 시스템으로, 조직이나 기관 등이 될 수 있음
- 유스케이스
    - 사용자가 보는 관점에서 시스템이 액터에게 제공하는 서비스 또는 기능을 표현
- 관계(Relationship)
    - 유스케이스 다이어그램에서 관계는 액터와 유스케이스, 유스케이스와 유스케이스 사이에서 나타날 수 있으며, 연관 관계, 포함 관계, 확장 관계, 일반화 관계를 표현할 수 있음

### 오퍼레이션(Operation)
- 클래스가 수행할 수 있는 동작으로, 함수(메소드)라고도 함

### 순차 다이어그램의 구성 요소
- 액터(Actor)
- 객체(Object)
- 생명선(Lifeline)
- 실행 상자(Active Box)
- 메시지(Message)

### 사용자 인터페이스의 구분
- CLI(Command Line Interface)
    - 명령과 출력이 텍스트 형태로 이뤄지는 인터페이스
- GUI(Graphic User Interface)
    - 아이콘이나 메뉴를 마우스로 선택하여 작업을 수행하는 그래픽 환경의 인터페이스
- NUI(Natural User Interface)
    - 사용자의 말이나 행동으로 기기를 조작하는 인터페이스

### 목업(Mockup)
- 디자인, 사용 방법 설명, 평가 등을 위해 와이어프레임 보다 좀 더 실제 화면과 유사하게 만든 정적인 형태의 모형
- 시각적으로만 구성 요소를 배치하는 것으로 실제로 구현되지는 않음

### 주요 모바일 제스처(Mobile Gesture)
- Tap(누르기)
    - 화면을 가볍에 한 번 터치하는 동작
- Double Tap(두번 누르기)
    - 화면을 빠르게 두 번 터치하는 동작
- Press(오래 누르기)
    - 화면의 특정 위치를 손가락으로 꾹 눌리는 동작
- Flick(빠르게 스크롤)
    - 화면에 손가락을 터치하면서 수평 또는 수직으로 빠르게 드래그하는 동작
- Pinch(두 손가락으로 넓히기/좁히기)
    - 두 손가락으로 화면을 터치한 후 두 손가락을 서로 다른 방향으로 움직이는 동작

### 사용자 인터페이스의 원칙 - 직관성
- 누구나 쉽게 이해하고 사용할 수 있어야 한다는 원칙

### 사용자 인터페이스 설계 지침
- 사용자 중심
    - 사용자가 쉽게 이해하고 편리하게 사용할 수 있는 환경을 제공하며, 실사용자에 대한 이해가 바탕이 되어야 함
- 사용성
    - 사용자가 소프트웨어를 얼마나 빠르고 쉽게 이해할 수 있는지, 얼마나 편리하고 효율적으로 사용할 수 있는지를 말하는 것으로, 사용자 인터페이스 설계시 가장 우선적으로 고려해야 함
- 가시성
    - 메인 화면에 주요 기능을 노출시켜 최대한 조작이 쉽도록 설계해야 함
- 심미성
    - 디자인적으로 완성도 높게 글꼴이나 색상을 적용하고 그래픽 요소를 배치하여 가독성을 높일 수 있도록 설계해야 함
- 접근성
    - 사용자의 연령, 성별, 인종 등 다양한 계층이 사용할 수 있도록 설계해야 함
- 오류 발생 해결
    - 오류가 발생하면 사용자가 쉽게 인지할 수 있도록 설계해야 함

### ISO/IEC 12119
- ISO/IEC 9126을 준수한 품질 표준, 테스트 절차를 포함하여 규정
- 패키지 소프트웨어의 일반적인 제품 품질 요구사항 및 테스트를 위한 국제 표준

### 소프트웨어 품질 특성 - 기능성(Functionality)
- 소프트웨어가 사용자의 요구사항을 정확하게 만족하는 기능을 제공하는지 여부를 나타냄
- 하위 특성
    - 적절성/적합성, 정밀성/정확성, 상호운용성, 보안성, 준수성

### 소프트웨어 품질 특성 - 신뢰성(Reliability)
- 소프트웨어가 요구된 기능을 정확하고 일관되게 오류 없이 수행할 수 있는 정도를 나타냄

### 소프트웨어 품질 특성 - 사용성(Usability)
- 사용자와 컴퓨터 사이 발생하는 어떤 행위에 대해 사용자가 쉽게 배우고 사용할 수 있으며, 향후 다시 사용하고 싶은 정도를 나타냄

### 소프트웨어 품질 특성 - 이식성(Portability)
- 소프트웨어가 다른 환경에서도 얼마나 쉽게 적용할 수 있는지 정도를 나타냄

### UI 요소 - 라디오 버튼
- 여러 항목 중 하나만 선택할 수 있는 사용자 인터페이스 요소

### 소프트웨어 아키텍처의 설계 과정
```
설계 목표 설정 -> 시스템 타입 결정 -> 아키텍처 패턴 적용 -> 서브시스템 구체화 -> 검토
```

### 모듈화(Modularity)
- 소프트웨어의 성능을 향상시키거나 시스템의 수정 및 재사용, 유지 관리 등이 용이하도록 시스템의 기능들을 모듈 단위로 나누는 것을 의미
- 모듈화를 통해 기능의 분리가 가능하여 인터페이스가 단순해진다.
- 모듈화를 통해 프로그램의 효율적인 관리가 가능하고 오류의 파급 효과를 최소화 가능
- 모듈의 크기를 너무 작게 나누면 개수가 많아져 모듈간의 통합 비용이 많이 들고, 너무 크게 나누면 개수가 적어 통합 비용은 적게 들지만 모듈 하나의 개발 비용이 많이 듬

### 추상화의 유형
- 과정 추상화
- 데이터(자료) 추상화
- 제어 추상화

### 파이프 - 필터 패턴
- 데이터 스트림 절차의 각 단계를 필터(Filter) 컴포넌트로 캡슐화하여 파이프(Pipe)를 통해 데이터를 전송하는 패턴
- 필터 간 데이터 이동 시 데이터 변환으로 인한 오버헤드 발생

### MVC(Model-View-Controller) 패턴
- 모델
    - 서브시스템의 핵심 기능과 데이터를 보관
- 뷰
    - 사용자에게 정보를 표시
- 컨트롤러
    - 사용자로부터 입력된 변경 요청을 처리하기 위해 모델에게 명령을 보냄

### 메시지(Message)
- 객체들 간 상호작용을 하는 데 사용되는 수단으로, 객체에게 어떤 행위를 하도록 지시하는 명령 또는 요구사항

### 클래스(Class)
- 공통된 속성과 연산(행위)을 갖는 객체의 집합으로, 객체의 일반적인 타입(Type)을 의미
- 클래스에 속한 각각의 객체를 인스턴스(Instance)라 함

### 캡슐화(Encapsulation)
- 데이터(속성)와 데이터를 처리하는 함수를 하나로 묶는 것을 의미
- 캡슐화된 객체는 외부 모듈의 변경으로 인한 파급 효과가 적음
- 캡슐화를 수행하면 인터페이스가 단순해짐
- 캡슐화된 객체들은 재사용이 용이

### 상속(Inheritance)
- 이미 정의된 상위 클래스(부모 클래스)의 모든 속성과 연산을 하위 클래스(자식 클래스)가 물려받는 것

### 객체지향 분석 방법론 - Coad와 Yourdon 방법
- E-R 다이어그램을 사용해 객체의 행위를 모델링하며, 객체 식별, 구조 식별, 주제 정의, 속성과 인스턴스 연결 정의, 연산과 메시지 연결 정의 등의 과정으로 구성하는 기법

### 럼바우(Rumbaugh)의 분석 기법
- 객체(Object) 모델링
    - 정보 모델링이라고도 하며, 시스템에서 요구되는 객체를 찾아내어 속성과 연산 식별 및 객체들 간의 관계를 규정하여 객체 다이어그램으로 표시하는 것
- 동적(Dynamic) 모델링
    - 상태 다이어그램(상태도)을 이용하여 시간의 흐름에 따른 객체들 간 제어 흐름, 상호 작용, 동작 순서 등의 동적인 행위를 표현하는 모델링
- 기능(Functional) 모델링
    - 자료 흐름도(DFD)를 이용해 다수의 프로세스들 간의 자료 흐름을 중심으로 처리 과정을 표현한 모델링

### 객체지향 설계 원칙(SOLID) 원칙
- 단일 책임 원칙(SRP; Single Responsibility Principle)
    - 객체는 단 하나의 책임만 가져야 한다는 원칙으로, 응집도는 높고, 결합도는 낮게 설계하는 것을 의미
- 개방 폐쇄 원칙(OCP; Open-Closed Principle)
    - 기존의 코드를 변경하지 않고 기능을 추가할 수 있도록 설계해야 한다는 원칙으로, 공통 인터페잇를 하나의 인터페이스로 묶어 캡슐화하는 방법이 대표적
- 리스코프 치환 원칙(LSP; Liskov Substitution Principle)
    - 자식 클래스는 최소한 자신의 부모 클래스에서 가능한 행위는 수행할 수 있어야 한다는 설계 원칙으로, 자식 클래스는 부모 클래스의 책임을 무시하거나 재정의하지 않고 확장만 수행하도록 해야함
- 인터페이스 분리 원칙(ISP; Interface Segregation Principle)
    - 자신이 사용하지 않는 인터페이스와 의존 관계를 맺거나 영향을 받지 않아야 한다는 원칙으로, 단일 책임 원칙이 객체가 갖는 하나의 책임이라면, 인터페이스 분리 원칙은 인터페이스가 갖는 하나의 책임
- 의존 역전 원칙(DIP; Dependency Inversion Principle)
    - 각 객체들 간 의존 관계가 성립될 때, 추상성이 낮은 클래스보다 추상성이 높은 클래스와 의존 관계를 맺어야 한다는 원칙으로, 일반적으로 인터페이스를 활용하면 이 원칙은 준수됨

### 모듈(Module)
- 모듈화를 통해 분리된 시스템의 각 기능들로, 서브 루틴, 서브시스템, 소프트웨어 내의 프로그램, 작업 단위 등과 같은 의미로 사용됨
- 모듈은 단독으로 컴파일이 가능하며, 재사용 할 수 있음
- 모듈은 다른 모듈에서의 접근이 가능

### 결합도의 종류
- 자료(Data) 결합도
    - 모듈 간의 인터페이스가 자료 요소로만 구성될 때의 결합도
- 스탬프(Stamp) 결합도
    - 모듈 간의 인터페이스로 배열이나 레코드 등의 자료 구조가 전달될 때의 결합도
- 제어(Control) 결합도
    - 어떤 모듈이 다른 모듈 내부의 논리적인 흐름을 제어하기 위해 제어 신호를 이용해 통신하거나 제어 요소를 전달하는 결합도
- 외부(External) 결합도
    - 어떤 모듈에서 선언한 데이터(변수)를 외부의 다른 모듈에서 참조할 때의 결합도
- 공통(Common) 결합도
    - 공유되는 공통 데이터 영역을 여러 모듈이 사용할 때의 결합도
- 내용(Content) 결합도
    - 한 모듈이 다른 모듈의 내부 기능 및 그 내부 자료를 직접 참조하거나 수정할 때의 결합도

### 결합도의 정도(약함->강함)
```
자로 결합도 -> 스탬프 결합도 -> 제어 결합도 -> 외부 결합도 -> 공통 결합도 -> 내용 결합도
```

### 응집도의 정도(약함->강함)
```
우연적 응집도 -> 논리적 응집도 -> 시간적 응집도 -> 절차적 응집도 -> 교환적 응집도 -> 순차적 응집도 -> 기능적 응집도
```

### 응집도의 종류
- 기능적(Functional) 응집도
    - 모듈 내부의 모든 기능 요소들이 단일 문제와 연관되어 수행될 경우의 응집도
- 순차적(Sequential) 응집도
    - 모듈 내 하나의 활동으로부터 나온 출력 데이터를 그 다음 활동의 입력 데이터로 사용할 경우의 응집도
- 교환적(Communication) 응집도
    - 동일한 입력과 출력을 사용해 서로 다른 기능을 수행하는 구성 요소들이 모였을 경우의 응집도
- 절차적(Procedural) 응집도
    - 모듈이 다수의 관련 기능을 가질 때 모듈 안의 구성 요소들이 그 기능을 순차적으로 수행할 경우의 응집도
- 시간적(Temporal) 응집도
    - 특정 시간에 처리되는 몇 개의 기능을 모아 하나의 모듈로 작성할 경우의 응집도
- 논리적(Logical) 응집도
    - 유사한 성격을 갖거나 특정 형태로 분류되는 처리 요소들로 하나의 모듈이 형성되는 경우의 응집도
- 우연적(Coincidental) 응집도
    - 모듈 내부의 각 구성 요소들이 서로 관련 없는 요소로만 구성된 경우의 응집도

### N-S 차트(Nassi-Schneiderman Chart)
- 논리의 기술에 중점을 둔 도형을 이용한 표현 방법으로 박스 다이어그램, Chapin Chart라고도 함
- 연속, 선택 및 다중 선택, 반복 등의 제어 논리 구조를 표현
- GOTO나 화살표를 사용하지 않음
- 조건이 복합되어 있는 곳의 처리를 시각적으로 명확히 식별하는 데 적합
- 이해하기 쉽고, 코드 변환이 용이

### 재사용(Reuse)
- 이미 개발된 기능을 새로운 시스템이나 기능 개발에 사용할 수 있는 정도를 의미
- 재사용 규모에 따른 분류
    - 함수와 객체, 컴포넌트, 애플리케이션

### 팬인(Fan-In) / 팬아웃(Fan-Out)
- 팬인
    - 어떤 모듈을 제어(호출)하는 모듈의 수
- 팬아웃
    - 어떤 모듈에 의해 제어(호출)되는 모듈의 수

### 효과적인 모듈 설계 방안
- 결합도는 줄이고 응집도는 높여 모듈의 독립성과 재사용성을 높임
- 모듈의 제어 영역 안에서 그 모듈의 영향 영역을 유지 시킴
- 복잡도의 중복성을 줄이고 일관성을 유지
- 모듈의 기능은 예측이 가능해야 하며 지나치게 제한적이어서는 안됨
- 유지보수가 용이해야 함

### 디자인 패턴(Design Pattern)
- 각 모듈의 세분화된 역할이나 모듈들 간의 인터페이스와 같은 코드를 작성하는 수준의 세부적인 구현 방안을 설계할 때 참조할 수 있는 전형적인 해결 방식 또는 예제를 의미
- 디자인 패턴 유형
    - 생성 패턴, 구조 패턴, 행위 패턴

### 생성 패턴(Creational Pattern)
- 추상 팩토리(Abstract Factory)
    - 구체적인 클래스에 의존하지 않고, 인터페이스를 통해 서로 연관-의존하는 객체들의 그룹으로 생성하여 추상적으로 표현
- 빌더(Builder)
    - 작게 분리된 인스턴스를 건축 하듯 조합하여 객체를 생성
- 팩토리 메서드(Factory Method)
    - 객체 생성을 서브 클래스에서 처리하도록 분리하여 캡슐화된 패턴으로, 상위 클래스에서 인터페이스만 정의하고 실제 생성은 서브 클래스가 담당. 가상 생성자(Virtual Constructor)패턴 이라고도 함
- 프로토 타입(Prototype)
    - 원본 객체를 복제하는 방법으로 객체를 생성하는 패턴
- 싱글톤(Singleton)
    - 하나의 객체를 생성하면 생성된 객체를 어디서든 참조할 수 있지만, 여러 프로세스가 동시에 참조할 수는 없음

### 구조 패턴(Structural Pattern)
- 어댑터(Adapter)
    - 호환성이 없는 클래스들의 인터페이스를 다른 클래스가 이용할 수 있도록 변환해주는 패턴
- 브리지(Bridge)
    - 구현부에서 최상층을 분리하여, 서로가 독립적으로 확장할 수 있도록 구성한 패턴
- 컴포지트(Composite)
    - 여러 객체를 가진 복합 객체와 단일 객체를 구분 없이 다루고자 할 때 사용하는 패턴
- 데코레이터(Decorator)
    - 객체 간의 결합을 통해 능동적으로 기능들을 확장할 수 있는 패턴으로, 임의의 객체에 부가적인 기능을 추가하기 위해 다른 객체들을 덧붙이는 방식으로 구현
- 퍼싸드(Facade)
    - 복잡한 서브 클래스들을 피해 더 상위에 인터페이스를 구성함으로써 서브 클래스들의 기능을 간편하게 사용할 수 있도록 하는 패턴
- 플라이웨이트(Flyweight)
    - 인스턴스가 필요할 때마다 매번 생성하는 것이 아니고 가능한 한 공유해서 사용함으로써 메모리를 절약하는 패턴
- 프록시(Proxy)
    - 접근이 어려운 객체와 여기에 연결하려는 객체 사이에서 인터페이스 역할을 수행하는 패턴

### 행위 패턴(Behavioral Pattern)
- 책임 연쇄(Chain of Responsibility)
    - 요청을 처리할 수 있는 객체가 둘 이상 존재하여 한 객체가 처리하지 못하면 다음 객체로 넘어가는 형태의 패턴
- 커맨드(Command)
    - 요청을 객체의 형태로 캡슐화하여 재이용하거나 취소할 수 있도록 요청에 필요한 정보를 저장하거나 로그에 남기는 패턴
- 인터프리터(Interpreter)
    - 언어에 문법 표현을 정의하는 패턴으로, SQL이나 통신 프로토콜과 같은 것을 개발할 때 사용함
- 반복자(Iterator)
    - 자료 구조와 같이 접근이 잦은 객체에 대해 동일한 인터페이스를 사용하도록 하는 패턴
- 중재자(Mediator)
    - 수많은 객체들 간 복잡한 상호작용(Interface)을 캡슐화하여 객체로 정의하는 패턴
- 메멘토(Memento)
    - 특정 시점에서의 객체 내부 상태를 객체화함으로써 이후 요청에 따라 객체를 해당 시점의 상태로 돌릴 수 있느 기능을 제공하는 패턴으로 Ctrl+Z와 같은 되돌리기 기능을 개발할 때 주로 사용
- 옵저버(Observer)
    - 한 객체의 상태가 변화하면 객체에 상속되어 있는 다른 객체들에게 변화된 상태를 전달하는 패턴
- 상태(State)
    - 객체의 상태에 따라 동일한 동작을 다르게 처리해야 할 때 사용하는 패턴
- 전략(Strategy)
    - 동일한 계열의 알고리즘들을 개별적으로 캡슐화하여 상호 교환할 수 있게 정의하는 패턴
- 템플릿 메소드(Template Method)
    - 상위 클래스에서 골격을 정의하고, 하위 클래승서 세부 처리를 구체화하는 구조의 패턴
- 방문자(Visitor)
    - 각 클래스들의 데이터 구조에서 처리 기능을 분리하여 별도의 클래스로 구성하는 패턴

### 요구사항 검증 방법
- 동료검토(Peer Review)
    - 요구사항 명세서 작성자가 명세서 내용을 직접 설명하고 동료들이 이를 들으며 결함을 발견하는 형태의 검토 방법
- 워크스루(Walk Through)
    - 검토 회의 전 요구사항 명세서를 미리 배포하여 사전 검토한 후 짧은 검토 회의를 통해 결함을 발견하는 형태의 검토 방법
- 인스펙션(Inspection)
    - 요구사항 명셋 작성자를 제외한 다른 검토 전문가들이 요구사항 명세서를 확인하며 결함을 발견하는 형태의 검토 방법
- 동료검토와 워크스루가 비공식적인 검토 방법인데 반해 인스펙션은 공식적인 검토 방법

### 미들웨어(Middleware)
- 분산 컴퓨팅 환경에서 서로 다른 기종 간의 하드웨어나 프로토콜, 통신 환경 등을 연결
- 운영체제와 응용 프로그램, 또는 서버와 클라이언트 사이에서 원만한 통신이 이루어지도록 다양한 서비스를 제공
- 위치 투명성을 제공
- 사용자가 미들웨어의 내부 동작을 확인하려면 별도의 응용 소프트웨어를 사용해야 함
- 시스템들을 1:1, 1:N, N:M 등 여러 가지 형태로 연결할 수 있음
- 종류 : DB, RPC, MOM, TP-Monitor, ORB, WAS 등

## 제 2과목 소프트웨어 개발

### 자료 구조의 분류
- 선형 구조 : 배열(Array), 선형 리스트(Linear List), 스택(Stack), 큐(Queue), 데크(Deque)
- 비 선형 구조 : 트리(Tree), 그래프(Graph)

### 스택(Stack)
- 리스트의 한쪽 끝으로만 자료의 삽입, 삭제 작업이 이루어지는 자료 구조
- 스택은 가장 나중에 삽입된 자료가 가장 먼저 삭제되는 후입선출(LIFO) 방식으로 자료를 처리

### 스택의 응용 분야
- 함수 호출의 순서 제어
- 인터럽트의 처리
- 수식 계산 및 수식 표기법
- 컴파일러를 이용한 언어 번역
- 부 프로그램 호출 시 복귀 주소 저장
- 서브루틴 호출 및 복귀 주소 저장

### 스택의 삽입(Push)과 삭제(Pop)
- PUSH는 스택에 자료를 입력하는 명령이고, POP은 스택에서 자료를 출력하는 명령

### 방향/무방향 그래프의 최대 간선 수
- n개의 정점으로 구성된 무방향 그래프에서 최대 간선 수는 n(n-1)/2이고, 방향 그래프에서 최대 간선 수는 n(n-1)이다.

### 트리(Tree)
- 트리는 정점(Node)과 선분(Branch)을 이용해 사이클을 이루지 않도록 구성한 그래프의 특수한 형태임
    - 디그리(Degree, 차수) : 각 노드에서 뻗어나온 가지의 수
    - 단말 노드(Terminal Node) : 자식이 하나도 없는 노드, 즉 디그리가 0인 노드

### 수식의 표기법(Infix -> Postfix)
- Infix로 표기된 수식에서 연산자를 해당 피연산자 두 개의 뒤(오른쪽)에 오도록 이동하면 Postfix가 됨
```
X = A / B * (C + D) + E -> X A B / C D + * E + =

1. 연산 우선순위에 따라 괄호로 묶는다.
( X = ( ( (A / B) * (C + D) ) + E ) )
2. 연산자를 해당 괄호의 뒤로 옮긴다.
X = ( ( (A / B) * (C + D)) + E)
(A/B)에서 (AB)/
(C+D)에서 (CD)+
( (AB)/ * (C+D)+ )에서 (AB)/(C+D)*
이런 형태로 변경하면
( X ( ( (AB) / (CD) + ) * E ) + ) =
3. 괄호를 제거
X A B / C D + * E + =
```

### 이진 트리의 운행법
- Preorder 운행법의 방문 순서
    - Root -> Left -> Right
- Inorder 운행법의 방문 순서
    - Left -> Root -> Right
- Postorder 운행법의 방문 순서
    - Left -> Right -> Root

### 퀵 정렬(Quick Sort)
- 레코드의 많은 자료 이동을 없애고 하나의 파일을 부분적으로 나누어 가면서 정렬하는 방법으로, 키를 기준으로 작은 값은 왼쪽에, 큰 값은 오른쪽 서브파일로 분해시키는 방식으로 정렬
- 분할(Divide)과 정복(Conquer)을 통해 자료를 정렬

### 삽입 정렬(Insertion Sort)
```
ex. 8, 5, 6, 2, 4를 삽입 정렬로 정렬하시오.
- 초기 상태 : 8 5 6 2 4
- 1 회전 : 8 [5] 6 2 4 -> 5 8 6 2 4
    - 두 번째 값 5를 첫 번째 값과 비교해 첫 번째 자리에 삽입하고 8을 한 칸 뒤로 이동시킴
- 2 회전 : 5 8 [6] 2 4 -> 5 6 8 2 4
    - 세 번째 값 6을 첫 번째, 두 번째 값과 비교해 8자리에 삽입하고 8을 한 칸 뒤로 이동
- 3 회전 : 5 6 8 [2] 4 -> 2 5 6 8 4
    - 네 번째 값 2를 처음부터 비교하여 맨 처음에 삽입하고 나머지를 한 칸 씩 뒤로 이동
- 4 회전 : 2 5 6 8 [4] -> 2 4 5 6 8
    - 마지막 값 4를 처음부터 비교하여 5 자리에 삽입하고 나머지를 한 칸씩 뒤로 이동
```

### 선택(Selection) 정렬
```
- n개의 레코드 중에서 최소값을 찾아 첫 번째 레코드 위치에 놓고, 나머지 (n-1)개 중에서 다시 최소값을 찾아 두 번째 레코드 위치에 놓는 방식을 반복하여 정렬

ex. 8, 5, 6, 2, 4를 선택 정렬로 정렬하시오
- 초기 상태 : 8 5 6 2 4
- 1 회전 : [8] 5 6 2 4 -> [5] 8 6 2 4 -> [2] 8 6 5 4
- 2 회전 : 2 [8] 6 5 4 -> 2 [6] 8 5 4 -> 2 [5] 8 6 4 -> 2 [4] 8 6 5
- 3 회전 : 2 4 [8] 6 5 -> 2 4 [6] 8 5 -> 2 4 [5] 8 6
- 4 회전 : 2 4 5 [8] 6 -> 2 4 5 [6] 8
```

### 버블 정렬(Bubble Sort)
```
- 주어진 파일에서 인접한 두 개의 레코드 키 값을 비교하여 그 크기에 따라 레코드 위치를 서로 교환

ex. 8, 5, 6, 2, 4를 버블 정렬로 정렬하시오.
- 초기 상태 : 8 5 6 2 4
- 1 회전 : 5 8 6 2 4 -> 5 6 8 2 4 -> 5 6 2 8 4 -> 5 6 2 4 8
- 2 회전 : 5 6 2 4 | 8 -> 5 2 6 4 8 -> 5 2 4 6 8
- 3 회전 : 5 2 4 | 6 8 -> 2 5 4 6 8 -> 2 4 5 6 8
- 4 회전 : 2 4 | 5 6 8

| 앞에꺼만 버블정렬을 수행하면 되는 형태
```

### 힙 정렬 (Heap Sort)
- 전이진 트리를 이용한 정렬 방식
- 평균과 최악 모두 시간 복잡도는 O(nlog2n) 이다.

### 2-Way 합병 정렬(Merge Sort)
- 이미 정렬되어 있는 두 개의 파일을 한 개의 파일로 합병하는 정렬 방식
- 평균과 최악 모두 시간 복잡도는 O(nlog2n) 이다.

### 테스트와 디버깅의 목적
- 테스트(Test)를 통해 오류를 발견한 후 디버깅(Debugging)을 통해 오류가 발생한 소스 코드를 추적하며 수정

### 이분 검색(이진 검색)
- 반드시 순서화(정렬)된 파일이어야 검색 가능
- 비교 횟수를 거듭할 때마다 검색 대상이 되는 데이터의 수가 절반으로 줄어듬
- 탐색 효율이 좋고 탐색 시간이 적게 소요됨
- 중간 레코드 번호(M) : (F + L) / 2
    - 단, F : 첫 번째 레코드 번호, L : 마지막 레코드 번호

### 주요 해싱 함수
- 제산법(Division) : 레코드 키(K)를 해시표(Hash Table)의 크기보다 큰 수 중에서 가장 작은 소수(Prime, Q)로 나눈 나머지를 홈 주소로 삼는 방식
- 제곱법(Mid-Square) : 레코드 키 값(K)을 제곱한 후, 그 중간 부분의 값을 홈 주소로 삼는 방식
- 폴딩법(Folding) : 레코드 키 값(K)을 여러 부분으로 나눈 후 각 부분의 값을 더하거나 XOR(배타적 논리합)한 값을 홈 주소로 삼는 방식
- 숫자 분석법(Digit Analysis) : 키 값을 이루는 숫자의 분포를 분석하여 비교적 고른 자리를 필요한 만큼 택해서 홈 주소로 삼는 방식

### 스키마 3 계층
- 외부 스키마
    - 사용자나 응용 프로그래머가 각 개인의 입장에서 필요로 하는 DB의 논리적 구조를 정의한 것
- 개념 스키마
    - DB의 전체적인 논리적 구조로서, 개체 간의 관계와 제약 조건을 나타내고, DB의 접근 권한, 보안 및 무결성 규칙에 관한 명세를 정의
- 내부 스키마
    - 물리적 저장장치의 입장에서 본 DB의 구조로서, 실제로 DB에 저장될 레코드의 형식을 정의하고 저장 데이터 항목의 표현 방법, 내부 레코드의 물리적 순서 등을 나타냄

### IDE(통합 개발 환경)의 기능
- 코딩(Coding)
    - C, JAVA 등의 프로그래밍 언어로 컴퓨터 프로그램을 만드는 기능
- 컴파일(Compile)
    - 개발자가 작성한 고급 언어로 된 프로그램을 컴퓨터가 이해할 수 있는 목적 프로그램으로 번역하여 컴퓨터에서 실행 가능한 형태로 변환하는 기능
- 디버깅(Debugging)
    - 소프트웨어나 하드웨어의 오류나 잘못된 동작, 즉 버그(Bug)를 찾아 수정하는 기능
- 배포(Deployment)
    - 소프트웨어를 사용자에게 전달하는 기능

### 빌드 자동화 도구
- Ant
    - 아파치 소프트웨어 재단에서 개발한 소프트웨어로, 자바 프로젝트의 공식적인 빌드 도구로 사용됨
- Maven
    - Ant의 대안으로 개발된 소프트웨어
- Jenkins
    - JAVA 기반의 오픈 소스 형태로, 가장 많이 사용되는 빌드 자동화 도구
- Gradle
    - Groovy를 기반으로 한 오픈 소스 형태의 자동화 도구로, 안드로이드 앱 개발 환경에서 사용

### 소프트웨어 패키징
- 모듈별로 생성한 실행 파일들을 묶어 배포용 설치 파일을 만드는 것을 말함
- 개발자가 아니라 사용자 중심으로 진행

### 소프트웨어 패키징 시 고려사항
- 사용자에게 배포되는 소프트웨어이므로 내부 콘텐츠에 대한 암호화 및 보안을 고려함
- 다른 여러 콘텐츠 및 단말기 간 DRM(디지털 저작권 관리) 연동을 고려함

### DRM(디지털 저작권 관리)의 구성 요소
- 클리어링 하우스(Clearing House)
    - 저작권에 대한 사용 권한, 라이선스 발급, 사용량에 따른 결제 관리 등을 수행하는 곳
- 콘텐츠 제공자(Contents Provider)
    - 콘텐츠를 제공하는 저작권자
- 패키저(Packager)
    - 콘텐츠를 메타 데이터와 함께 배포 가능한 형태로 묶어 암호화하는 프로그램
- 콘텐츠 분배자(Contents Distributor)
    - 암호화된 콘텐츠를 유통하는 곳이나 사람
- DRM 컨트롤러(DRM Controller)
    - 배포된 콘텐츠의 이용 권한을 통제하는 프로그램
- 보안 컨테이너(Security Container)
    - 콘텐츠 원본을 안전하게 유통하기 위한 전자적 보안 장치

### DRM(디지털 저작권 관리)의 기술 요소
- 암호화
    - 콘텐츠 및 라이선스 암호화 기술
- 키 관리
    - 콘텐츠를 암호화한 키에 대한 저장 및 분배 기술
- 식별 기술
    - 콘텐츠에 대한 식별 체계 표현 기술
- 정책 관리
    - 라이선스 발급 및 사용에 대한 정책 표현 및 관리 기술
- 크랙 방지
    - 크랙에 의한 콘텐츠 사용 방지 기술

### 소프트웨어 설치 매뉴얼
- 설치 매뉴얼은 사용자를 기준으로 작성함
- 기본 사항 : 소프트웨어 개요, 설치 관련 파일, 설치 아이콘, 프로그램 삭제, 관련 추가 정보

### 소프트웨어 사용자 매뉴얼 작성 순서
```
작성 지침 정의 -> 사용자 매뉴얼 구성 요소 정의 -> 구성 요소별 내용 작성 -> 사용자 매뉴얼 검토
```

### 형상 관리(SCM)
- 소프트웨어의 개발 과정에서 소프트웨어의 변경 사항을 관리하기 위해 개발된 일련의 활동
- 소프트웨어 개발의 전체 비용을 줄이고, 개발 과정의 여러 방해 요인이 최소화되도록 보충하는 것을 목적으로 함
- 관리 항목
    - 소스 코드, 프로젝트 계획, 분석서, 설계서, 프로그램, 테스트 케이스 등
- 형상 관리 도구
    - Git, CVS, Subversion 등

### 형상 관리 기능
- 형상 식별
    - 형상 관리 대상에 이름과 관리 번호를 부여하고, 계층(Tree) 구조로 구분해 수정 및 추적이 용이하도록 하는 작업
- 버전 제어
    - 소프트웨어 업그레이드나 유지 보수 과정에서 생성된 다른 버전의 형상 항목을 관리하고, 이를 위해 특정 절차와 도구를 결합시키는 작업
- 형상 통제
    - 식별된 형상 항목에 대한 변경 요구를 검토 해 현재의 기준선(Base Line)이 잘 반영될 수 있도록 조정하는 작업
- 형상 감사
    - 기준선의 무결성을 평가하기 위해 확인, 검증, 검열 과정을 통해 공식적으로 승인하는 작업
- 형상 기록
    - 형상의 식별, 통제, 감사 작업의 결과를 기록-관리하고 보고서를 작성하는 작업

### 소프트웨어의 버전 등록 관련 주요 기능
- 체크아웃(Check-Out)
    - 프로그램을 수정하기 위해 저장소(Repository)에서 파일을 받아옴
- 체크인(Check-In)
    - 체크아웃 한 파일의 수정을 완료한 후 저장소(Repository)의 파일을 새로운 버전으로 갱신함
- 커밋(Commit)
    - 체크인을 수행할 때 이전에 갱신된 내용이 있는 경우에는 충돌(Conflict)을 알리고 diff 도구를 이용해 수정한 후 갱신을 완료

### RCS(Revision Control System)
- 여러 개발자가 프로젝트를 수행할 때 시간에 따른 파일 변화 과정을 관리하는 소프트웨어 버전 관리 도구
- 소스 파일을 동시에 수정하는 것을 방지하고, 다른 방향으로 진행된 개발 결과를 합치거나 변경 내용을 추적 할 수 있음

### 분산 저장소 방식
- 버전 관리 자료가 하나의 원격 저장소와 분산된 개발자 PC의 로컬 저장소에 함께 저장되어 관리되는 방식
- 대표적인 종류에는 Git이 있음

### 확인(Validation) / 검증(Verification)
- 확인(Validation)
    - 사용자의 입장에서 개발한 소프트웨어가 고객의 요구사항에 맞게 구현되었는지를 확인하는 것
- 검증(Verification)
    - 개발자의 입장에서 개발한 소프트웨어가 명세서에 맞게 만들어졌는지를 점검하는 것

### 파레토 법칙(Pareto Principle)
- 소프트웨어 테스트에서 오류의 80%는 전체 모듈의 20%내에서 발견된다는 법칙

### 결함 집중
- 애플리케이션 대부분의 결함이 소수의 특정 모듈에 집중해서 발생하는 것을 의미
- 파레토 법칙이 좌우함
- 결함은 발생한 모듈에서 계속 추가로 발생할 가능성이 높음

### 강도(Stress) 테스트
- 시스템에 과도한 정보량이나 빈도 등을 부과하여 과부하시에도 소프트웨어가 정상적으로 실행되는지를 확인하는 테스트

### 화이트박스 테스트(White Box Test)
- 모듈의 원시 코드를 오픈시킨 상태에서 원시 코드의 논리적인 모든 경로를 테스트하여 테스트 케이스를 설계 하는 방법
- 원시 코드(모듈)의 모든 문장을 한 번 이상 실행함으로써 수행됨
- 프로그램의 제어 구조에 따라 선택, 반복 등의 분기점 부분들을 수행함으로써 논리적 경로를 제어함

### 화이트박스/블랙박스 테스트 종류
- 화이트박스 테스트 종류
    - 기초 경로 검사, 제어 구조 검사(조건 검사, 루프 검사, 데이터 흐름 검사)
- 블랙박스 테스트 종류
    - 동치 분할 검사, 경계값 분석, 원인-효과 그래프 검사, 오류 예측 검사, 비교 검사
- 기초 경로(Base Path = Basis Path)
    - 수행 가능한 모든 경로를 의미

### 단위 테스트(Unit Test)
- 코딩 직후 소프트웨어 설계의 최소 단위인 모듈이나 컴포넌트에 초점을 맞춰 테스트하는 것
- 단위 테스트로 발견 가능한 오류
    - 알고리즘 오류에 따른 원치 않는 결과, 탈출구가 없는 반복문의 사용, 틀린 계산 수식에 의한 잘못된 결과

### 인수 테스트의 종류
- 알파 테스트
    - 개발자의 장소에서 사용자가 개발자 앞에서 행하는 테스트 기법
- 베타 테스트
    - 선정된 최종 사용자가 여러 명의 사용자 앞에서 행하는 테스트 기법으로, 필드 테스팅(Field Testing)이라고도 불림

### 통합 테스트
- 하향식 통합 테스트
    - 프로그램의 상위 모듈에서 하위 모듈 방향으로 통합하면서 테스트하는 기법으로, 깊이 우선 통합법이나 넓이 우선 통합법을 사용
- 상향식 통합 테스트
    - 프로그램의 하위 모듈에서 상위 모듈 방향으로 통합하면서 테스트하는 기법

### 테스트 드라이버(Test Driver)
- 테스트 대상의 하위 모듈을 호출하는 도구로, 매개 변수(Parameter)를 전달하고, 모듈 테스트 수행 후의 결과를 도출
- 상위 모듈 없이 하위 모듈이 있는 경우 하위 모듈을 구동
- 상향식 통합 테스트에 사용

### 테스트 스텁(Test Stub)
- 제어 모듈이 호출하는 타 모듈의 기능을 단순히 수행하는 도구로, 일시적으로 필요한 조건만을 가지고 있는 시험용 모듈
- 상위 모듈은 있지만 하위 모듈이 없는 경우 하위 모듈을 대체
- 하향식 통합 테스트에 사용

### 테스트 케이스(Test Case)
- 구현된 소프트웨어가 사용자의 요구사항을 정확하게 준수했는지를 확인하기 위해 설계된 입력 값, 실행 조건, 기대 결과 등으로 구성된 테스트 항목에 대한 명세서
- 테스트 케이스는 테스트 목표와 방법을 설정한 후 작성

### 테스트 오라클
- 참(True) 오라클
    - 모든 테스트 케이스의 입력 값에 대해 기대하는 결과를 제공하는 오라클로, 발생된 모든 오류를 검출
- 샘플링(Sampling) 오라클
    - 특정한 몇몇 테스트 케이스의 입력 값들에 대해서만 기대하는 결과를 제공하는 오라클
- 추정(Heuristic) 오라클
    - 특정 테스트 케이스의 입력 값에 대해 기대하는 결과를 제공하고, 나머지 입력 값들에 대해서는 추정으로 처리하는 오라클
- 일관성 검사(Consistent) 오라클
    - 애플리케이션의 변경이 있을 때, 테스트 케이스의 수행 전과 후의 결과 값이 동일한지를 확인하는 오라클

### 테스트 케이스 생성 도구
- 자료 흐름도
    - 자료 원시 프로그램을 입력받아 파싱한 후 자료 흐름도를 작성
- 기능 테스트
    - 주어진 기능을 구동시키는 모든 가능한 상태를 파악해 이에 대한 입력 작성
- 입력 도메인 분석
    - 원시 코드의 내부를 참조하지 않고, 입력 변수의 도메인을 분석하여 테스트 데이터를 작성
- 랜덤 테스트
    - 입력 값을 무작위로 추출해 테스트

### 성능 테스트 도구(Performance Test Tools)
- 애플리케이션의 처리량, 응답 시간, 경과 시간, 자원 사용률 등을 인위적으로 적용한 가상의 사용자를 만들어 테스트를 수행함으로써 성능의 목표 달성 여부 확인

### 결함(Fault)
- 오류(Error) 발생, 작동 실패 등과 같이 소프트웨어가 개발자가 설계한 것과 다르게 동작하거나 다른 결과가 발생되는 것을 의미

### 주요 최악의 시간 복잡도
```
O(1) - 입력값(n)에 관계 없이 일정하게 문제 해결에 하나의 단계 만을 거침
ex. 스택의 삽입(Push), 삭제(Pop)
O(nlog2n) - 문제 해결에 필요한 단계가 n(log2n)번 만큼 수행
ex. 힙 정렬(Heap Sort), 2-Way 합병 정렬(Merge Sort)
```

### 순환 복잡도(Cyclomatic Complexity) 계산
- 그림으로 확인

### 클린 코드 작성 원칙
- 가독성
    - 누구든지 코드를 쉽게 읽을 수 있도록
- 단순성
    - 코드를 간단하게 작성
- 의존성 배제
    - 코드가 다른 모듈에 미치는 영향을 최소화
- 중복성 최소화
    - 코드의 중복을 최소화
- 추상화
    - 상위 클래스/메소드/함수에서는 간략하게 애플리케이션의 특성을 나타내고, 상세 내용은 하위 클래스/메소드/함수에서 구현

### 외계인 코드(Alien Code)
- 아주 오래되거나 참고문서 또는 개발자가 없어 유지 보수 작업이 어려운 코드를 의미

### 소스 코드 품질 분석 도구 - 정적 분석 도구
- 작성한 소스 코드를 실행하지 않고 코딩 표준이나 코딩 스타일, 결함 등을 확인
- 자료 흐름이나 논리 흐름을 분석하여 비정상적인 패턴을 찾을 수 있음
- 종류
    - pmd, checkstyle, cppcheck 등

### EAI의 구축 유형
- Point-to-Point
    - 애플리케이션을 1:1로 연결
- Hub & Spoke
    - 단일 접점인 허브 시스템을 통해 데이터를 전송하는 중앙 집중형 방식
- Message Bus(ESB 방식)
    - 애플리케이션 사이에 미들웨어를 두어 처리하는 방식
- Hybrid
    - Hub & Spoke와 Message Bus의 혼합 방식

### JSON(JavaScript Object Notation)
- 속성-값 쌍(Attribute-Value Pairs)으로 이루어진 데이터 객체를 전달하기 위해 사람이 읽을 수 있는 텍스트를 사용하는 개방형 표준 포맷

### AJAX(Asynchronous JavaScript and XML)
- 자바 스크립트 등을 이용해 클라이언트와 서버 간 XML 데이터를 교환 및 제어함으로써 이용자가 웹 페이지와 자유롭게 상호 작용할 수 있도록 하는 비동기 통신 기술을 의미

### IPSec(IP Security)
- 네트워크 계층에서 IP 패킷 단위의 데이터 변조 방지 및 은닉 기능을 제공하는 프로토콜
- 암호화와 복호화가 모두 가능한 양방향 암호 방식

### 인터페이스 보안 기능 적용 - 네트워크 영역
- 인터페이스 송-수신간 스니핑 등을 이용한 데이터 탈취 및 변조 위협을 방지하기 위해 네트워크 트래픽에 대한 암호화를 설정
- 암호화는 인터페이스 아키텍처에 따라 IPSec, SSL, S-HTTP 등의 다양한 방식으로 적용

### 데이터 무결성 검사 도구
- 시스템 파일의 변경 유무를 확인하고, 파일이 변경되었을 경우 이를 관리자에게 알려주는 도구
- 크래커 등이 시스템에 침입하면 백도어를 만들어 놓거나 시스템 파일을 변경해 자신의 흔적을 감추는데, 무결성 검사 도구를 이용해 이를 감지할 수 있음
- 종류
    - Tripwire, AIDE, Samhain 등

### 인터페이스 구현 검증 도구
- xUnit
    - JUnit, CppUnit,NUnit,HttpUnit 등 다양한 언어에 적용되는 단위 테스트 프레임워크
- STAF
    - 서비스 호출 및 컴포넌트 재사용 등 다양한 환경을 지원하는 테스트 프레임워크
- FitNesse
    - 웹 기반 테스트케이스 설계, 실행, 결과 확인 등을 지원하는 테스트 프레임워크
- NTAF
    - FitNesse와 STAF의 장점을 통합한 NHN(Naver)의 테스트 자동화 프레임워크
- watir
    - Ruby를 사용하는 애플리케이션 테스트 프레임워크

## 제 3과목 데이터베이스 구축

### 개념적 설계(정보 모델링, 개념화)
- 정보의 구조를 얻기 위해 현실 세계의 무한성과 계속성을 이해하고, 다른 사람과 통신하기 위해 현실 세계에 대한 인식을 추상적 개념으로 표현하는 과정
- 개념적 설계 단계에선 개념 스키마 모델링과 트랜잭션 모델링을 병행 수행
- 개념적 설계 단계에선 요구 분석 단계에서 나온 결과인 요구 조건 명세를 DBMS에 독립적인 E-R 다이어그램으로 작성
- DBMS에 독립적인 개념 스키마를 설계

### 논리적 설계(데이터 모델링)
- 현실 세계에서 발생하는 자료를 컴퓨터가 이해하고 처리할 수 있는 물리적 저장장치에 저장할 수 있도록 변환하기 위해 특정 DBMS가 지원하는 논리적 자료 구조로 변환(mapping)시키는 과정
- 개념 세계의 데이터를 필드로 기술된 데이터 타입과 이 데이터 타입들 간의 관계로 표현되는 논리적 구조의 데이터로 모델화
- 개념적 설계가 개념 스키마를 평가 및 정제하고 DBMS에 따라 서로 다른 논리적 스키마를 설계하는 단계
- 트랜잭션의 인터페이스를 설계
- 관계형 DB라면 테이블을 설계하는 단계

### 물리적 설계
- 논리적 설계 단계에서 논리적 구조로 표현된 데이터를 디스크 등의 물리적 저장장치에 저장할 수 있는 물리적 구조의 데이터로 변환하는 과정
- 물리적, 설계 단계에서는 다양한 DB 응용에 대해 처리 성능을 얻기 위해 DB 파일의 저장 구조 및 액세스 경로를 결정
- 저장 레코드의 형식, 순서, 접근 경로, 조회가 집중되는 레코드와 같은 정보를 사용해 데이터가 컴퓨터에 저장되는 방법을 묘사
- 물리적 설계 시 고려할 사항
    - 트랜잭션 처리량, 응답 시간, 디스크 용량, 저장 공간의 효율화 등

### 데이터 모델에 표시할 요소
- 구조(Structure)
    - 논리적으로 표현된 개체 타입들 간의 관계로서 데이터 구조 및 정적 성질을 표현
- 연산(Operation)
    - DB에 저장된 실제 데이터를 처리하는 작업에 대한 명세로서 DB를 조회하는 기본 도구
- 제약 조건(Constraint)
    - DB에 저장될 수 있는 실제 데이터의 논리적인 제약 조건

### E-R 다이어그램
- E-R 모델의 기본 아이디어를 시작적으로 표현하기 위한 그림
```
그림으로 확인
```

### E-R(개체-관계) 모델
- 개념적 데이터 모델의 가장 대표적인 것으로, 1976년 피터 첸(Peter Chen)에 의해 제안된 기본적인 구성 요소가 정립됨
- E-R 모델은 개체와 개체 간의 관계를 기본 요소로 이용해 현실 세계의 무질서한 데이터를 개념적인 논리 데이터로 표현하기 위한 방법으로 많이 사용되고 있음
- E-R 모델은 특정 DBMS를 고려한 것은 아님

### 튜플(Tuple)
- 릴레이션을 구성하는 각각의 행을 말함
- 파일 구조에서 레코드와 같은 의미
- 튜플의 수를 카디널리티(Cardinality) 또는 기수, 대응 수라고 함

### 속성(Attribute)
- DB를 구성하는 가장 논리적 단위
- 파일 구조상의 데이터 항목 또는 데이터 필드에 해당 됨
- 속성은 개체의 특성을 기술함
- 속성의 수를 디그리(Degree) 또는 차수라고 함

### 도메인(Domain)
- 하나의 속성이 취할 수 있는 같은 타입의 원자(Atomic)값들의 집합
- 메인은 실제 속성 값이 나타날 때 그 값의 합법 여부를 시스템이 검사하는데에도 이용

### 후보키(Cardinality Key)
- 릴레이션을 구성하는 속성들 중 튜플을 유일하게 식별하기 위해 사용되는 속성들의 부분집합으로, 유일성과 최소성을 모두 만족

### 릴레이션의 특징
- 한 릴레이션에 포함된 튜플들은 모두 상이
- 한 릴레이션에 포함된 튜플 사이에는 순서가 없음
- 튜플들의 삽입, 삭제 등의 작업으로 인해 릴레이션은 시간에 따라 변화
- 릴레이션 스키마를 구성하는 속성들 간의 순서는 중요하지 않음
- 속성의 유일한 식별을 위해 속성의 명칭은 유일해야 하지만, 속성을 구성하는 값은 동일한 값이 있을 수 있음
- 속성은 더 이상 쪼갤 수 없는 원자값만을 저장

### 기본키(Primary Key)
- 후보키 중 특별히 선정된 키로 중복된 값과 NULL 값을 가질 수 없음
- 한 릴레이션에서 특정 튜플을 유일하게 구별할 수 있는 속성

### 대체키(Alternate Key)
- 후보키가 둘 이상일 때 기본키를 제외한 나머지 후보키를 의미함
- 보조키라고도 함

### 슈퍼키(Super Key)
- 한 릴레이션 내에 있는 속성들의 집합으로 구성된 키로서 릴레이션을 구성하는 모든 튜플등 중 슈퍼키로 구성된 속성의 집합과 동일한 값은 나타나지 않음
- 슈퍼키는 릴레이션을 구성하는 모든 튜플에 대해 유일성은 만족시키지만, 최소성은 만족시키지 못함

### 외래키(Foreign Key)
- 다른 릴레이션의 기본키를 참조하는 속성 또는 속성들의 집합을 의미
- 한 릴레이션에 속한 속성 A와 참조 릴레이션의 기본키인 B가 동일한 도메인 상에서 정의되었을 때의 속성 A를 외래키라고 함

### 개체 무결성(Entity Integrity, 실체 무결성)
- 기본 테이블의 기본키를 구성하는 어떤 속성도 Null 값이나 중복값을 가질 수 없다는 규정

### 도메인 무결성(Domain Integrity, 영역 무결성)
- 주어진 속성 값이 정의된 도메인에 속한 값이어야 한다는 규정

### 참조 무결성(Referential Integrity)
- 외래키 값은 Null이거나 참조 릴레이션의 기본키 값과 동일해야 함. 즉 릴레이션은 참조할 수 없는 외래키 값을 가질 수 없다는 규정
- 외래키와 참조하려는 테이블의 기본키는 도메인과 속성 개수가 같아야 함

### 사용자 정의 무결성(User-Defined Integrity)
- 속성 값들이 사용자가 정의한 제약 조건에 만족해야 한다는 규정

### 관계대수
- RDBMS에서 원하는 정보와 그 정보를 검색하기 위해 어떻게 유도하는가를 기술하는 절차적 언어
- 관계대수는 릴레이션을 처리하기 위해 연산자와 연산 규칙을 제공하는 언어로 피연산자가 릴레이션이고, 결과도 릴레이션임
- 질의에 대한 해를 구하기 위해 수행해야 할 연산의 순서를 명시
- 관계대수에는 RDBMS에 적용하기 위해 특별히 개발한 순수 관계 연산자와 수학적 집합 이론에서 사용하는 일반 집합 연산자가 있음
- 순수 관계 연산자
    - Select, Project, Join, Division
- 일반 집합 연산자
    - UNION(합집합), INTERSECTION(교집합), DIFFERENCE(차집합), CARTESIAN PRODUCT(교차곱)

### Select
- 릴레이션에 존재하는 튜플 중에서 선택 조건을 만족하는 튜플의 부분집합을 구해 새로운 릴레이션을 만드는 연산
- 릴레이션의 행(가로)에 해당하는 튜플을 구하는 것이므로 수평 연산이라고도 함
- 연산자의 기호는 그리스 문자 시그마를 사용함

### Join
- 공통 속성을 중심으로 두 개의 릴레이션을 하나로 합쳐서 새로운 릴레이션을 만드는 연산
- Join의 결과로 만들어진 릴레이션의 차수는 조인된 두 릴레이션의 차수를 합한 것과 같음
- Join의 결과는 Cartesian Product(교차곱)를 수행한 다음 Select를 수행한 것과 같음
- 연산자의 기호는 나비모양을 사용함

### Division
- X ⊃ Y인 두 개의 릴레이션 R(X)와 S(Y)가 있을 때, R의 속성이 S의 속성 값을 모두 가진 튜플에서 S가 가진 속성을 제외한 속성만을 구하는 연산
- 연산자의 기호는 ÷ 를 사용
- 표기 형식
    - R [속성r ÷ 속성s] S

### Cartesian Product(교차곱)
- 두 릴레이션에 존재하는 모든 튜플들을 대응시켜 새로운 릴레이션을 만드는 연산
- 연산의 결과 차수는 두 릴레이션의 차수를 합한 것과 같고 튜플은 두 릴레이션의 튜플 수를 곱한 것과 같음

### 관계해석
- 관계 데이터 모델의 제안자인 코드(E. F. Codd)가 수학의 Predicate Calculus(술어 해석)에 기반을 두고 RDBMS를 위해 제안함
- 관계해석은 관계 데이터의 연산을 표현하는 방법으로, 원하는 정보를 정의할 때는 계산 수식을 사용함
- 관계해석은 원하는 정보가 무엇이라는 것만 정의하는 비절차적 특성을 지님
- 기본적으로 관계해석과 관계대수는 RDBMS를 처리하는 기능과 능력면에서 동등하며, 관계대수로 표현한 식은 관계해석으로 표현할 수 있음
```
- 관계 해석 주요 기호
기호        |       구성 요소       |       설명        
∀                전칭 정량자           가능한 모든 튜플에 대하여(For All)
∃                존재 전량자           하나라도 일치하는 튜플이 있음(There Exists)
```

### 정규화(Normalization)의 개념 및 목적
- 함수적 종속성 등의 종속성 이론을 이용해 잘못 설계된 관계형 스키마를 더 작은 속성의 세트로 쪼개어 바람직한 스키마로 만들어 가는 과정
- 데이터 구조의 안전성 및 무결성을 유지
- 어떠한 릴레이션이라도 DB내에서 표현 가능하게 만듬
- 효과적인 검색 알고리즘을 생성할 수 있다.
- 데이터 중복을 배제해 이상(Anomaly)의 발생 방지 및 자료 저장 공간의 최소화가 가능
- 데이터 삽입 시 릴레이션을 재구성할 필요성을 줄임
- 자료 검색과 추출의 효율성을 추구

### 이상(Anomaly)의 개념 및 종류
- 정규화를 거치지 않으면 DB 내에 데이터들이 불필요하게 중복되어 릴레이션 조작 시 예기치 못한 곤란한 현상이 발생하는데, 이를 이상(Anomaly)이라 하며, 삽입 이상, 삭제 이상, 갱신 이상이 있음.
- 삽입 이상(Insertion Anomaly)
    - 릴레이션에 데이터를 삽입할 때 의도와는 상관없이 원하지 않은 값들도 함께 삽입되는 현상
- 삭제 이상(Deletion Anomaly)
    - 릴레이션에서 한 튜플을 삭제할 때 의도와는 상관없는 값들도 함께 삭제되는 연쇄가 일어나는 현상
- 갱신 이상(Update Anomaly)
    - 릴레이션에서 튜플에 있는 속성값을 갱신할 때 일부 튜플의 정보만 갱신되어 정보에 모순이 생기는 현상

### 1NF(제1정규형)
- 릴레이션에 속한 모든 도메인(Domain)이 원자값(Atomic Value)만으로 되어 있는 정규형. 즉 릴레이션의 모든 속성 값이 원자 값으로만 되어 있는 정규형

### 2NF(제2정규형)
- 릴레이션 R이 1NF이고, 기본키가 아닌 모든 속성이 기본키에 대해 완전 함수적 종속을 만족하는 정규형

### 함수적 종속(Functional Dependency)
- 데이터들이 어떤 기준값에 의해 종속되는 것을 의미
ex. <수강> 릴레이션이