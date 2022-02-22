# Developer Maker Project    

#1. 프로젝트 생성


#2. 패키지 생성
- Structure By Layer : controller, service, repository, dto, entity  
- We recommend that you follow Java’s recommended package naming conventions and use a **reversed domain name**  
- The use of the “default package” is generally discouraged, and should be avoided.
- We generally recommend that you locate your main application class in a root package above other classes.

- 참고
  - [Spring Boot Reference Guide - Structuring your code](https://docs.spring.io/spring-boot/docs/2.0.0.M2/reference/htmlsingle/#using-boot-structuring-your-code)  
  - [Spring Boot – Code Structure](https://www.geeksforgeeks.org/spring-boot-code-structure/#:~:text=There%20is%20no%20specific%20layout,divide%20the%20project%20into%20modules.)
  - [Springboot 에서 @ComponentScan 설정 및 사용법](https://oingdaddy.tistory.com/254)

#3. Controller
  1. 사용자의 입력이 최초로 받아지는 곳
  2. @RestController vs @Controller
    1. restController 타입의 빈으로 등록을 한다는 뜻
    2. controller + response body 추가

- 참고
  - [Spring Boot Reference Guide - @RestController](https://docs.spring.io/spring-boot/docs/2.0.0.M2/reference/htmlsingle/#getting-started-first-application-annotations)
  - [Difference between @RestController and @Controller Annotation in Spring MVC and REST](https://www.javacodegeeks.com/2017/08/difference-restcontroller-controller-annotation-spring-mvc-rest.html#:~:text=The%20%40Controller%20is%20a%20common,of%20%40Controller%20%2B%20%40ResponseBody%20.)