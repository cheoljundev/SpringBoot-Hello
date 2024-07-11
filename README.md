![springboot-hello](https://socialify.git.ci/ruiyeclub/SpringBoot-Hello/image?description=1&forks=1&issues=1&language=1&name=1&owner=1&pulls=1&stargazers=1&theme=Light)
## SpringBoot 올인원 패키지

Spring Boot는 Pivotal 팀에서 제공하는 새로운 프레임워크로, 새로운 Spring 애플리케이션의 초기 설정 및 개발 과정을 간소화하기 위해 설계되었습니다.
이 프레임워크는 특정한 방식으로 설정을 수행하여 개발자가 템플릿화된 설정을 정의할 필요가 없도록 합니다.
이와 같은 방식으로 Spring Boot는 급성장하는 빠른 애플리케이션 개발 분야에서 리더가 되고자 합니다.

**중요 공지 사항:**

1. master 브랜치는 최신 Spring Boot 2.3.0을 기반으로 구축되었습니다!

## 하위 프로젝트 목록

각 하위 프로젝트마다 블로그 글을 통해 자세한 설명을 제공하려고 합니다 :point_right:

| 프로젝트 이름                          | 상세 설명                                                                                  |
| ------------------------------------- | ----------------------------------------------------------------------------------------- |
| springboot-aop-log                    | AOP를 사용하여 로그 기록                                                                   |
| springboot-async                      | Async 비동기 호출 통합                                                                     |
| springboot-easyexcel                  | 더 나은 알리바바 엑셀 도구 EasyExcel 사용                                                   |
| springboot-fastjson2                  | fastjson2 사용                                                                             |
| springboot-flyway                     | Flyway 데이터베이스 버전 관리 통합                                                          |
| springboot-hibernate-validator        | [Hibernate Validator 통합](https://www.cnblogs.com/ruiyeclub/p/13141467.html)               |
| springboot-hutool                     | Java 유틸리티 라이브러리                                                                   |
| springboot-i18n                       | i18n 통합을 통한 백엔드 국제화 구현                                                         |
| springboot-japidocs                   | API 문서 생성 도구                                                                         |
| springboot-jpa                        | JPA를 통합하여 CRUD 구현                                                                  |
| springboot-jwt                        | [JWT 통합을 통한 인터페이스 권한 인증](https://www.cnblogs.com/ruiyeclub/p/12951145.html)  |
| springboot-lambda                     | Java8 기능 Lambda 표현식                                                                   |
| springboot-mail                       | [메일 통합, MailUtils를 사용하여 메일 전송](https://www.cnblogs.com/ruiyeclub/p/13394493.html) |
| springboot-mongodb                    | MongoDB 데이터베이스 통합, mongoTemplate을 사용하여 MongoDB 조작                             |
| springboot-mybatis-plus               | Mybatis-Plus 통합                                                                          |
| springboot-oss-qiniu                  | Qiniu 클라우드 스토리지 통합, QiniuUtil을 사용하여 파일 업로드 구현                         |
| springboot-rabbitmq                   | RabbitMQ 메시지 큐 통합                                                                    |
| springboot-redis                      | Redis 데이터베이스, redisTemplate을 사용하여 Redis 조작                                     |
| springboot-redis-lock                 | Redis 분산 잠금 통합                                                                       |
| springboot-redis-mq                   | Redis를 사용하여 메시지 큐 기능 구현                                                       |
| springboot-redis-ratelimit            | Redis를 사용하여 인터페이스 속도 제한 기능 구현                                             |
| springboot-scheduled                  | 정기 작업                                                                                  |
| springboot-shiro                      | [Shiro 권한 관리 통합](https://www.cnblogs.com/ruiyeclub/p/12469920.html)                  |
| springboot-sms                        | 알리바바 SMS 문자 메시지 서비스 통합                                                       |
| springboot-socket.io                  | socket.io 서버와 클라이언트를 통합하여 통신 구현                                            |
| springboot-swagger3                   | [Swagger3 통합을 통한 자동 API 문서 생성](https://www.cnblogs.com/ruiyeclub/p/13334826.html) |
| springboot-thymeleaf                  | Thymeleaf 템플릿 엔진 통합                                                                 |
| springboot-undertow                   | Tomcat 서버를 대체하여 Undertow 서버 사용                                                  |
| springboot-upload                     | [로컬 파일 업로드 구현](https://www.cnblogs.com/ruiyeclub/p/12732154.html)                  |
| springboot-validation                 | Validation 파라미터 검증 통합                                                              |
| springboot-vue-axios                  | vue+axios를 사용하여 간단한 CRUD 구현                                                      |
| springboot-websocket                  | Websocket 통합                                                                             |
| springboot-wxpay                      | WeChat 미니 프로그램 결제 기능 통합                                                        |
| springboot-xxl-job                    | XXL-JOB 분산 작업 스케줄링 플랫폼 통합                                                    |

## 환경

* JDK 1.8
* Maven 최신 버전
* Spring Boot 2.3.0
* Intellij IDEA
* MySQL 5.7
* MongoDB
* Git 버전 관리
* Redis 캐시
* XXL-JOB 분산 작업 스케줄링 플랫폼

## 후속 계획

1. Qiniu 클라우드 객체 스토리지 추가 [√]
2. EasyExcel 통합 [√]
3. 메일 전송 통합 [√]
4. JPA 데이터베이스 조작 통합 [√]
5. 국제화(i18n) 통합 [√]
6. RabbitMQ 메시지 큐 추가 [√]
7. Quartz 정기 작업 통합 [√]
8. MyBatis 다중 데이터 소스 조작
9. Markdown 문서 편집기 통합
10. ElasticSearch 전체 텍스트 검색 엔진 통합
11. Kafka 메시지 큐 통합
12. Sentinel 인터페이스 속도 제한 통합
13. Seata 분산 트랜잭션 미들웨어 통합

## 문제 피드백

1. Issue를 제출하여 이 프로젝트를 함께 개선해 주세요.
2. 이메일: ruiyeclub@foxmail.com
3. 개인 홈페이지: [http://www.ruiyeclub.cn/](http://www.ruiyeclub.cn/)
4. 개인 홈페이지: [https://ttlikeu.top/](https://ttlikeu.top/)
