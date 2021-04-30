# modak-4.30
# 1. 댓글 익명 처리 완료
쉽지 않았다. 익명처리 자체는 별로 난이도가 있지 않았지만, 카운트를 부여하는 것은 꽤나 헤맸었다. 결론은 런트랜잭션에 파이어스토어 애드스냅샷 넣어도 상관없다. 
코드 정리만 잘하고, 엘스만 잘 구분해서 넣으면 된다. 엘스 괜히 무시하려 하지말고. 예외사항을 꼼꼼히 따진다. 코드가 길어지더라도 한 펑션에 다 넣어서 하는 것도 지금은 나쁘지 않다. 
# 2. 패이지 상단 모닥 정중앙에 오게하기
애초에 잘 되지 않았다. 그래서 아예 없애버리고 새로운 툴바를 디테일뷰에 적용하는 것으로 했다. 결국 앱바라는 기능과 비슷했는데, 쉽게 될줄 알았지만 쉽지는 않았다. 이제는 완벽히 숙지했다. 
배울점은 다른 사용자의 방법을 찾는 것도 좋지만, 공식문서를 찾아보는 것이 좋다는 것이다. 공식문서가 이제는 이해가 되는 수준에 왔기에 충분히 봐도 된다. 이것 또한 공식문서로 해결했다.
# 3. 글 삭제와 수정 구현하기
글 삭제는 상당히 쉬웠다. 사실 여기서 해멨던 것은 상위의 툴바를 구현하는 것이 쉽지가 않아서였지 그다음은 사실 바로 아이디어가 떠올랐기에 그리 어렵지 않았다. 삭제는 한줄만 작성하면 되는 것이었고, 글 수정은 에딧컨텐츠라는 애드컨텐츠의 틀을 들고 온것을 새로 만들었다. 주의할점은 액티비티를 만들 때 복사해서 만들게 되면 자동으로 마니페스트에 적용이 안된다는 점이다. 이를 유의하도록 하자. 
그리고 오류를 읽을 때 단면만 봐서 해당 코드를 클릭하지말고 전체 오류를 읽어보도록 하자. 이제 꽤나 이해가 가니까
# 해야할 것
(1)지역과 게시판, (2)글 신고하기 구현, (3)복지관 홈페이지 연결, (4)나이, 성별 추가, (5)디자인적 ui 다듬기, (6)전화번호 로그인 구현, (7)복지혜택 페이지 구현
