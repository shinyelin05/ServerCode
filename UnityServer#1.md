# ServerCode

```
ushort playerLen = BitConverter.ToUInt16(segment.Array, segment.Offset + count);
```
수정해준다.

![image](https://user-images.githubusercontent.com/77713669/236679953-995515d3-9b2a-4548-a715-b8f6a24e4db1.png)
 
 바이트 배열로 넣어준다.

![image](https://user-images.githubusercontent.com/77713669/236680070-cea55c8a-c0b4-46fa-8b57-2bcade40b2e7.png)

세그먼트로 작성

![image](https://user-images.githubusercontent.com/77713669/236680116-fe4bad2d-2594-4d77-8627-ddaf901421df.png)

-> 에러가 어느 정도 해결

---

![image](https://user-images.githubusercontent.com/77713669/236680404-4963fc38-f639-4335-9314-cff4d116308e.png)
세그먼트 어레이에다가 똑같이 복사

![image](https://user-images.githubusercontent.com/77713669/236681356-8a6a6b01-dc79-41cf-98a3-55c937a2a323.png)
0번과 1번으로 교체


##NetWorkManager
![image](https://user-images.githubusercontent.com/77713669/236682974-3a9f2183-7a62-4e55-ad80-3128f9b7d993.png)

복사하고 시작을 한다.





