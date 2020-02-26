API : Application Programming Interface
fs.readFile의 경우
> 누군가는 만들고 누군가는 사용한다.

https://nodejs.org/ko/docs 접속
> 해당 버전의 모듈과 기능을 알 수 있음

http 선택
> 설명확인

http.createServer 확인
> 첫번째 인자는 requestListener, 감싸고 있는 대괄호는 첫번째 인자에 인자가 있을 수도 없을 수도 있다는  뜻

var app = http.createServer(function(request, response){
    ...
}) > 실제 구현하고 있는 부분은 requestListner 부분인 것임

app 에 http.server를 할당

app.listen(3000) : app(http.server)을 3000번 포트에 대기


