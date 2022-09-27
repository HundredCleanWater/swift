SwiftUI를 사용하던 중 Color를 직접적으로 코드를 쓰지않고 커스텀하는 방법을 찾아보면서 알게 된 방법을 공유하려 합니다.

 

먼저 기존 사용법을 보겠습니다.

 ![image](https://user-images.githubusercontent.com/90129613/192443295-d19b45db-1b83-4ae9-9ade-c50baa7b0c59.png)

![image](https://user-images.githubusercontent.com/90129613/192443307-4e4b0ccc-c795-48fc-9917-fcc56dc0f7c3.png)

![image](https://user-images.githubusercontent.com/90129613/192443319-ab593fba-7c5f-495e-b303-cb6a296e7ec1.png)



기존 로그인 버튼부분에 Color를 넣기위해서 직접적으로 상수를 선언하여 만들었습니다. 


그렇다면 직접적으로 커스텀을 하여 Color를 지정하는 방법을 알아보도록 하겠습니다.

 ![image](https://user-images.githubusercontent.com/90129613/192443356-9153714b-679c-415f-82a8-25024a0fbf0f.png)



위의 네모부분에 우클릭을 합니다.

 ![image](https://user-images.githubusercontent.com/90129613/192443375-4af1bbfc-cfab-43c0-80a8-2720d73d64a3.png)



그 후 New Color Set을 선택합니다.

![image](https://user-images.githubusercontent.com/90129613/192443395-2a967332-6e69-40ee-80e3-fefc15990711.png)


클릭을 하게 되면 Color를 지정할 수 있는 파일이 생성되는데 초기엔 Color로 입력이 되어있습니다.

더블클릭을 하게 되면 위와같이 이름을 변경 할 수 있고 원하는 네이밍을 하시면 됩니다.

 ![image](https://user-images.githubusercontent.com/90129613/192443408-a6209599-7fe1-40f1-822d-a258e69e016b.png)



그리고 나서 Color에서 Input Method를 클릭하여 원하는 방법으로 설정하면 됩니다.

저는 기존 8-bit 기준으로 사용했어서 8-bit으로 클릭하여 색지정을 해보도록 하겠습니다.

 ![image](https://user-images.githubusercontent.com/90129613/192443431-bac62d5c-44f1-4012-b616-4ea65cd75362.png)



원하는 색상이 나왔습니다.

![image](https://user-images.githubusercontent.com/90129613/192443446-b561906e-89e3-4f73-95f3-558fe078a4dd.png)


그 후 프로젝트가 커지는 것 까지 생각하여 Color를 관리하는 파일을 만들어서 관리를 해주도록 합니다. 

 ![image](https://user-images.githubusercontent.com/90129613/192443456-f35becd8-2045-4202-a5b1-f0446227822f.png)



그 후 코드수정만 해주면 이렇게 깔끔하게 Color를 지정하면서 관리를 해줄 수 있습니다.
