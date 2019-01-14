# Spring Boot Integration 예제

스프링 공식 예제를 바탕으로 작성
https://spring.io/guides/gs/integration/

전혀 다른 input 과 output을 연결 해주는 Enterprise Integration Pattern을 Spring에서 구현한 프로젝트

## 예제
예제는 Spring Blog의 feed를 받아와 /tmp/si/SpringBlog 파일에 Speing Blog의 제목과 링크를 저장하는 예제임

## 테스트 예제

`SyndEntryImpl`를 활용하여 payload Message를 생성 한 후 `MessageChannel`의 객체인 new를 통해 메시지를 전달(File Write와 동일하게 동작)하여 파일의 내용을 확인하는 예제

