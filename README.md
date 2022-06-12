# git_practice

- ## git branch 용어 정리

  ### 1. Master Branch

  저장소를 처음으로 생성하면 git은 자동으로 master branch를 생성, 따로 branch를 생성하지 않으면 모든 작업들이 master branch에서 이루어진다.

  ### 2. 통합 Branch

  언제든 배포할 수 있는 버전을 만드는 Branch, 보통 master branch가 이 역할을 한다.

  ### 3. Topic Branch

  기능 추가, 버그 수정과 같은 단위 작업을 위한 branch, 통합 브랜치로부터 파생되며, 완료되면 통합 branch로 병합된다.

  ### 4. Checkout

  Git에서 작업할 branch를 선택해야 한다. 맨 처음에는 master branch로 지정되어 있는데, 다른 branch로 넘어가는 행위를 checkout이라고 한다.

  ### 5. Head

  현재 사용중인 branch의 선두 부분

  ### 6. Merge

  여러 개의 branch를 하나로 모으는 것.

  ### 7. Rebase

  Merge와 같은 개념이지만 이력이 남지 않는다.

- 참고자료
  https://inpa.tistory.com/453
