# hello-java

이 프로젝트는 스탠드얼론에서 클라이언트/서버, 웹, 모바일까지 다양한 구조의 애플리케이션 개발을 경험할 수 있도록 기획된 자바 프로젝트입니다. 이 프로젝트를 통해 지난 30년 간 진화해 온 다양한 애플리케이션 아키텍처를 단계별로 실습해 볼 수 있습니다. 

## 누구를 위한 프로젝트인가요?

* **자바 기본 문법을 익혔지만 그 이후에 뭘 해야 할 지 막막함**을 느끼는 사람.
* **자바 문법을 배우고 있는** 개발 입문자. 
* C/C++, C#, PHP, Python 등 **다른 프로그래밍 언어를 알고 있는데 자바를 빠르게 배우고 싶은** 사람.
* **프로그래밍 관련 교육 과정을 받은 적**이 있으나 **프로그램을 짜라고 하면 자신이 없는** 사람.
* **신입 개발자**인데 **곧 프로젝트 유지 보수에 투입**되는 사람.
* **실무 개발을 경험하고 싶은** 컴퓨터공학, 경영정보, 전기/전자공학 등 **소프트웨어 관련 학과 재학생**

## 프로젝트를 통해 무엇을 얻을 수 있나요?

이 프로젝트를 통해 **자바 문법이 실전에서 어떻게 활용**되는지 배울 수 있고, 과거에서 최근까지 **약 30여년에 걸쳐 진화**해 온 **다양한 애플리케이션 아키텍처를 압축해서 경험**할 수 있습니다.

애플리케이션을 단계적으로 진화시켜 가는 과정 속에서 **적용 기술의 용도와 동작원리를 보다 깊게 이해** 할 수 있으며, **프로그래밍에 대한 시야를 넓힐 수** 있습니다. 단순한 프로그래밍 역량 강화를 넘어서 실무에서 개발 경험이 쌓이기 시작하면 **더 빠르게 성장**할 것입니다.

특히 **자료 구조를 직접 구현**하고 기존의 유명 **프레임워크와 라이브러리를 모방**해 보는 실습도 포함하였는데, 이는 **자바 문법의 이해도를 높이고** 실무에서 만나게 될 다양한 구조의 **프레임워크나 라이브러리에 대한 적응력을 높여** 줄 것입니다.


## 프로젝트 주제는 무엇인가요?

실습할 프로젝트는 ***수업 관리 시스템*** 입니다. 강사와 학생에게 **지능적인 수업 환경**을 제공하는 애플리케이션입니다.

**주요 기능**은 다음과 같습니다.

- 강사 및 학생 관리
- 수업 관리
- 과제 관리
- 실시간 의사 소통

## 프로젝트에서 어떤 기술을 사용하나요?

**자바 기본 API** 뿐만 아니라 실무에서 자주 사용되는 **외부 라이브러리 및 프레임워크**도 활용합니다. 또한 다양한 **구현 및 설계 기법**을 적용합니다. 

자바 기본 API는 다음과 같습니다. 

- 컬렉션 프레임워크: **List**, **Set**, **Map**
- 파일 입출력: **I/O Stream API**
- JDBC 프로그래밍: **SQL** 및 **JDBC API**
- 네트워킹 프로그래밍: **TCP** 및 **UDP** 통신
- 스레드 프로그래밍: **멀티 스레드**와 동기화 기법, **스레드풀**
- 리플렉션 프로그래밍: **Reflection API**

외부 라이브러리와 프레임워크는 다음과 같습니다.

- **Mybatis** SQL 맵퍼 라이브러리
- **JSON** 데이터 처리 라이브러리: **Gson**, **Jackson**
- **Spring 프레임워크**: IoC 컨테이너 및 WebMVC

구현 및 설계 기법은 다음과 같습니다.

- **자료구조** 구현: **Array List**, **Linked List**, **Stack**, **Queue**
- **마틴 파울러**의 **'리팩토링'** 기법
- **SOLID** 객체지향 설계 원칙
- **GRASP(General Responsibility Assignment Software Patterns)** 객체지향 설계 원칙 및 패턴
- **GoF**의 **디자인 패턴**

위의 기술을 사용하는 과정에서 **객체지향 문법의 의미와 용도를 깊게 이해**할 수 있습니다. 

- 클래스의 용도
- 스태틱과 인스턴스 멤버 비교
- 인스턴스의 의미와 생성자의 역할
- 상속의 장점과 단점
- 캡슐화와 접근 제어
- 상속 외의 기능 확장 기법
- 오버라이딩과 오버로딩의 의미
- 추상 클래스와 추상 메서드의 용도
- 인터페이스와 추상 클래스 비교
- 중첩 클래스와 람다 활용법
- 제네릭의 용도
- 예외처리의 의미
- 스트림 연산(aggregate operations)

## 프로젝트를 단계적으로 진행한다고 했는데 어떤 방식인가요?

콘솔 입출력에서 웹 애플리케이션까지 단계적으로 진화하도록 구성하였습니다. 각 단계마다 구현 목표가 있으며, 구현에 필요한 자바 문법과 API, 라이브러리 활용법을 소개합니다.

프로젝트의 각 단계를 따라가다 보면, **자료구조에 따라 데이터를 다루는 방법**이나 **리팩터링을 통해 코드를 유지보수 하기 좋게 만드는 방법**, **GoF의 디자인 패턴으로 기능 변경이나 확장이 용이한 구조로 애플리케이션을 설계하는 방법** 등을 배울 수 있습니다.

다음은 단계 별 애플리케이션 아키텍처와 버전입니다.

- 1.x - CLI 기반 스탠드얼론 애플리케이션
- 2.x - 네트워킹 및 스레드 기반 클라이언트/서버 애플리케이션
- 3.x - 데이터베이스 기반 애플리케이션
- 4.x - 애플리케이션 서버 기반 애플리케이션
- 5.x - 서블릿/JSP 기반 웹 애플리케이션
- 6.x - 스프링 프레임워크 기반 웹 애플리케이션
- 7.x - 스프링부트 기반 웹 애플리케이션
- 8.x - AJAX 기반 프론트엔드-백엔드 웹 애플리케이션

## 프로젝트를 따라가려면 어떤 준비가 필요한가요?

프로젝트는 다음 도구를 사용합니다.

- 운영체제: macOS 또는 Windows 11 또는 Linux 
- Java SE 21(JDK 21)
- 편집기: Visual Studio Code, IntelliJ IDEA Community
- 빌드 도구: Gradle
- 버전 관리 도구: Git
- DBMS: MySQL
- WAS: Tomcat, Undertow
- 프레임워크: SpringBoot
