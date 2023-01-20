## Cookie와 SameSite 속성

- 쿠키는 브라우저에 데이터를 저장하기 위한 수단 중 하나이다. 브라우저에서 서버로 요청을 전송할 때 그 요청에 대한 서버의 응답에 Set-Cookie 헤더가 포함되어 있는 경우, 브라우저는 Set-Cookie에 있는 데이터를 저장하고, 이 저장된 데이터를 쿠키라고 한다.
  - 예시
  ```
  Set-Cookie: Authentication=임의의값; Max-Age=86400; Path=/; Expires=Tue, 10 Jan 2023 09:45:59 GMT; HttpOnly; Secure; SameSite=None
  ```
- SameSite 쿠키

# 졸려워서 내일 하기로 해
