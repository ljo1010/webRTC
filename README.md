# webRTC
실행법
1. docker desktop을 다운받는다.
2. powershell에다가 $ docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-dev:2.29.0
 을 입력해 docker에서 서버를 열도록 한다.
3. npm start를 해서 컴파일 한 뒤에 join을 누르면 화상채팅이 가능해진다. 
