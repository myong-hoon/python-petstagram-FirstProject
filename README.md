# petstagram

스파르타 코딩클럽 15일 메이킹 챌린지 4기 5조 작품입니다.

왕초보 5명이서 만들어낸 결과물입니다.

flask mongodb requests boto3 를 이용해서 구현했습니다.

기능설명

1. 원페이지로 섹션을 5구역으로 나눔
2. Home에는 하트를 가장많이받은 반려동물을 나타냄
3. Photo 페이지에는 등록된 반려동물을 나타내며 슬라이드를 통해 좌우로 움직임 카드에 마우스를 갖다대면 뒷면으로 전환되며 하트 누르기 가능(![image](https://user-images.githubusercontent.com/92171034/136588397-5a548b07-d274-41dd-83e5-708edd6cf045.png)
4. 검색기능으로 입력한 태그를 바탕으로 분류가 가능
5. 추가하기 버튼으로 반려동물을 추가할수 있음
6. 반려동물을 추가할때 사진 및 정보를 ajax로 넘겨 aws s3 bucket에 올리고 mongodb에는 url 만저장
7. Vidio 섹션에는 유튜브 링크를 연결하여 유튜브 홈페이지로 이동할수있도록 구현
8. Quiz 섹션에는 반려동물 상식을 퀴즈로 풀수있도록 제공(www.fyrebox.com) 이용
9. Contact 섹션에는 다른 사이트를 연결할수 있도록 구현

