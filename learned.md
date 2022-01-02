# Maven vs Gradle

Maven같은경우는 스프링프로젝트에서 pom.xml이란 이름으로 쓰고,
Gradle은 스프링부트, 안드로이드에서 쓰는걸로 알고있다.

사용되는 라이브러리가 많으면 관리하는 것이 힘들어진다. Maven은 이러한 문제를 해결해 줄수 있는 도구이다.
기본 메이븐의 경우 XML로 라이브러리를 정의하고 활용하도록 되어 있으나, Gradle의 경우 별도의 빌드스크립트를 통하여 사용할 어플리케이션 버전, 라이브러리등의 항목을 설정 할 수 있다. 스크립트 언어로 구성되어 있기때문에, XML과 달리 변수선언, if, else, for등의 로직이 구현가능하여 간결하게 구성 가능하다.

Gradle은 메이븐보다 최대 100배 빠르다.

출처 : https://hyojun123.github.io/2019/04/18/gradleAndMaven/

# spring initializr



https://start.spring.io/

gradle 추천, artifact로 프로젝트명 설정, dependencies spring web

# bean, IoC

bean은