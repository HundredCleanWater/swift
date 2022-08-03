과제를 하던 중 String으로 넘어온 값을 Date로 바꿔 표시하는 작업을 진행했다.

![image](https://user-images.githubusercontent.com/90129613/182560459-11c676c4-e58c-4eeb-a73e-c287637518a0.png)

regDtm은 Date를 의미하며 String값으로 받는다.

![image](https://user-images.githubusercontent.com/90129613/182560577-739f4753-bee3-4012-af9b-803ad49db4e9.png)

현재 화면에 나오는 date

date가 yyyyMMddHHmmss형식으로 넘어온 것을 확인하였고,

![image](https://user-images.githubusercontent.com/90129613/182560654-292cd8f9-b8ef-4edb-b681-8097b14d2767.png)

date를 yyyy-MM-dd 형식으로 바꿔주기위해 위와같이 로직을 구현했다.  그 결과,

![image](https://user-images.githubusercontent.com/90129613/182560715-c47b3340-ea2a-4138-b120-36a2fe767365.png)

완벽하게 구현이 됐다.