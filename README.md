# Node.js 웹 앱의 도커라이징

아래 링크에 기재된 코드 예제 입니다.
https://nodejs.org/ko/docs/guides/nodejs-docker-webapp/

```sh
docker build -t qpitlove/node-web-app .

docker images

# docker run --rm -p 49160:8080 -d qpitlove/node-web-app
docker run --rm -p 49165:8080 qpitlove/node-web-app
```
