# 클로저 기반 보안 강화 Bank Account Management System

## 💡 프로젝트 소개

이 프로젝트는 **JavaScript의 클로저(Closure) 개념을 심층적으로 이해하고, 이를 활용하여 객체(생성자 함수)의 캡슐화(Encapsulation)를 강화**하는 방법을 연구하고 실제 구현한 사례입니다. 흔히 알려진 방식보다 강력한 객체 보안, 즉 **Security Kernel** 확보의 필요성을 느껴, 기존 '은행 입출금 관리 서비스' 프로젝트에 클로저 기반의 보안 메커니즘을 적용하여 그 실용성과 효용성을 검증했습니다.

## 🚀 주요 기능 및 특징

* **클로저 기반 캡슐화 강화:** JavaScript 생성자 함수를 클로저 패턴으로 구현하여, 외부에서 객체의 내부 상태에 직접 접근하고 변경하는 것을 효과적으로 제어합니다.
* **보안 커널 확보 연구:** 민감한 금융 데이터의 무단 접근 및 수정을 방지하기 위한 보안 계층을 구축하는 데 중점을 두었습니다.
* **실용적인 은행 입출금 관리 시스템:** 입금, 출금, 잔액 조회 등 기본적인 은행 업무 기능을 제공합니다.
* **Node.js 기반:** 서버 측 로직 구현에 Node.js를 사용하여 JavaScript 생태계 내에서 구현되었습니다.

## 🛠️ 기술 스택

* **언어:** JavaScript (ES6+)
* **런타임 환경:** Node.js
* **개발 환경:** MacOS
* **배포 환경:** Windows/Linux Native App (예상)


## 🗓️ 프로젝트 기간 및 참여 인력

* **기간:** 2024년 8월
* **참여 인력:** 1인 (시스템 설계 및 개발: 본인)


## ⚙️ 개발 과정 및 문제 해결 경험

본 프로젝트는 JavaScript의 생성자 함수, 클래스, 객체에 대한 심도 있는 학습에서 시작되었습니다. 특히 클로저를 활용한 생성자 함수의 캡슐화 보장 아이디어를 고안하고 이를 실제 서비스에 적용하는 과정에서 많은 도전 과제가 있었습니다.

* **IIFE 패턴 적용의 어려움:** 객체 및 클래스를 IIFE(Immediately Invoked Function Expression) 함수 패턴으로 전환하는 과정에서 수많은 시행착오를 겪었습니다. 클로저의 기본적인 작동 원리를 파악하고 이를 응용 수준까지 숙달하는 데 많은 노력이 필요했습니다.
* **학습 곡선 및 범용성:** 클로저를 활용한 이 아이디어는 개발자의 이해 수준에 따라 높은 학습 곡선을 가질 수 있음을 확인했습니다. 이를 모든 개발자가 쉽게 사용할 수 있는 라이브러리나 모듈로 만들려 시도했으나, 개발 과정에서 직접 구현하는 것이 더 효율적이라고 판단하여 별도의 심화 프로젝트로 진행하지는 않았습니다.

이러한 과정을 통해 클로저의 강력한 기능과 잠재력을 깊이 있게 이해할 수 있었습니다.


## 💡 차후 발전 방향 (계획)

기본적인 클래스, Getter, Setter를 사용할 경우 모든 사용자가 특정 객체를 임의로 수정 및 조회할 수 있는 반면, 클로저 및 함수형 프로그래밍 기법을 사용하면 객체에 대한 임의의 수정 및 조회를 단계적으로 조절할 수 있음을 확인했습니다.

하지만, 현재의 JavaScript 및 클로저 기반의 캡슐화만으로는 Java 스택의 JVM(Java Virtual Machine)이 제공하는 수준의 강력한 기밀성을 완전히 대체하기는 어렵다는 결론에 도달했습니다.

따라서, 향후 프로젝트에서는 **JVM 수준의 강력한 기밀성을 보장**할 수 있도록 **C / C++ 등 컴파일러 기반 언어의 특성을 이용한 라이브러리 "Mint"를 고안**하고 있습니다. 이를 구현하기 위해서는 **WebAssembly에 대한 깊이 있는 이해**가 필수적임을 확인했으며, 이 방향으로 추가 연구를 진행할 계획입니다.


## 🔗 프로젝트 링크

* **GitHub Repository:** [https://github.com/irondenker/closure-banking-service](https://github.com/irondenker/closure-banking-service)
