
![image](https://user-images.githubusercontent.com/77713669/236683309-507862e7-05f4-42bd-b2b4-9f82412b32a1.png)

플레이어를 만들고, 간단하게 이름으로 찾는 방법으로 구현한다.


![image](https://user-images.githubusercontent.com/77713669/236684040-b8a75160-bad6-4f7c-b989-36fa80b5f9fd.png)
메인 스레드 문제다

#PacketQueue.cs의 클래스를 구현한다.

![image](https://user-images.githubusercontent.com/77713669/236684230-0c143cc9-f1ba-4ac8-9880-7cbb1efbd4f2.png)
싱글톤 느낌으로 어디에서나 사용할 수 있도록 한다.

![image](https://user-images.githubusercontent.com/77713669/236684690-669ae0fc-2902-40d1-84d6-73b5eac95651.png)
핸드 패킷에 호출한다.

![image](https://user-images.githubusercontent.com/77713669/236684972-f05973dc-434e-45c5-af42-cc0d284b41a3.png)
여기서 인자가 s와 p인 이유는 OnRecvPacketd의 반환값을 보면 된다.

#



