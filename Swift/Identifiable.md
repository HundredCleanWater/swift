swiftUI Tutorials를 보면서 swiftUI에 대해 연습을 하던 중 동적리스트를 만들 때 id값을 직접적으로 사용하지 않고 Identifiable 프로토콜을 사용하여 id값을 넘겨주는 방식이 있어서 정리를 해보려고 합니다. 

먼저 apple 공식 문서에 있는 Identifiable에 대한 정의를 보겠습니다.

![image](https://user-images.githubusercontent.com/90129613/191139006-19421c68-81a1-4558-9222-8ed432ce90c0.png)

인스턴스가 안정적인 ID를 가진 개체 값을 갖고 있는 인스턴스 타입을 정의 할 때 채택하여 사용하는 프로토콜이라고 합니다.

직접적으로 예시를 보면서 어떻게 사용을 하는지 보도록 하겠습니다.

![image](https://user-images.githubusercontent.com/90129613/191139296-6d64bbb1-8ad2-4ae7-bdc0-7bea7adfcd0e.png)


기존에는 위와같이 id값을 데이터와 함께 전달을 하는 방식으로 진행을 하면서 데이터를 식별 할 수 있도록 만들었습니다. 

![image](https://user-images.githubusercontent.com/90129613/191139171-0a2fdf10-46af-4711-852e-0ec61b81e91b.png)


하지만 위와 같이 데이터를 읽을 때 디코딩 할 속성 Identifiable만 추가를 하게 된다면 

![image](https://user-images.githubusercontent.com/90129613/191139218-ef5e5bdd-f036-4cd1-b8f2-2ef6628bb384.png)


![image](https://user-images.githubusercontent.com/90129613/191139209-ea78e15f-00f2-4ccd-8861-715764f09541.png)

id값을 삭제를 하더라도 데이터를 식별 할 수 있게 됩니다.
