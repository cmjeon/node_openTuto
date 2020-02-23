https://pm2.keymetrics.io/

npm install pm2 -g //pm2 설치

pm2 start main.js //앱 자동실행 시작

pm2 stop main.js //앱 자동실행 중지

pm2 monit //모니터링 기능

pm2 list //등록된 앱 확인

pm2 start main.js --watch //앱을 실행하면서 변경사항 감시

pm2 log //앱로그 확인