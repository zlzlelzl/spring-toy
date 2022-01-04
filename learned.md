# Spring, Spring boot

Spring은 java 기반 웹 프레임워크이고, 서버, 환경변수, xml bean등 여러가지 설정을 해줘야 실행 가능함. Spring boot는 Spring을 쉽게 사용할 수 있도록 spring initializr를 통해 자주 사용하는 보일러 플레이트를 라이브러리 형태로 제공하여 스프링을 구동할 수 있게 함

# spring initializr

https://start.spring.io/

gradle 추천, artifact로 프로젝트명 설정, dependencies spring web(웹 프레임워크), h2(db), mustache(템플릿엔진), jpa(ORM)

# Maven vs Gradle

Maven은 스프링프로젝트에서 pom.xml으로 쓰고, Gradle은 스프링부트, 안드로이드에서 쓴다.

사용되는 라이브러리가 많으면 관리하는 것이 힘들어진다. Maven은 이러한 문제를 해결해 줄수 있는 도구이다.
기본 Maven의 경우 XML로 라이브러리를 정의하고 활용하도록 되어 있으나, Gradle의 경우 별도의 빌드스크립트를 통하여 사용할 어플리케이션 버전, 라이브러리등의 항목을 설정 할 수 있다. 스크립트 언어로 구성되어 있기때문에, XML과 달리 변수선언, if, else, for등의 로직이 구현가능하여 간결하게 구성 가능하다.

Gradle이 Maven보다 최신이고, 최대 100배 빠르다.

출처 : https://hyojun123.github.io/2019/04/18/gradleAndMaven/

# bean

https://cbw1030.tistory.com/54
http://melonicedlatte.com/2021/07/18/182600.html
bean은 스프링 컨테이너를 통해서 만들어진 객체. 어노테이션으로 상속받아 사용하고, 자주 쓰이는 bean이 있다.

# IoC(Inversion of Control)

제어 역전, 프레임워크와 라이브러리의 차이, 필요에 따라 사용자에게 코드를 강요함

# POJO(Plain Old Java Object)

자바EE(enterprise edition, 기업용이니까 지원하는 기능이 많고 무거움)의 EJB(enterprise javabeans)에 종속되어있는 무거운 객체를 사용하는 것에 반발하여 나온 철학

# MVC

Model(db), View(front), Controller(back)으로 웹 프레임워크를 나눠서 개발하여 협업할 수 있게 함