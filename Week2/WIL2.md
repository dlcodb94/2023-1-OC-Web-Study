1.  git의 명령어 add, commit, push는 각각 어떤 역할을 하는지 정리하고, git pull과 fetch의 차이점을 정리하시오.

\- **add** **명령어** : 다음 변경(commit)을 기록할 때까지 변경분을 모아두기 위해 사용.

따라서 commit 명령어를 통해 명시적으로 기록을 남기기 전까지 git 저장소의 변경 이력에는 어떤 영향도 주지 않음.

\- **commit** **명령어** : staging area의 모든 파일을 commit함.

저장소에는 하나의 스냅샷으로 기록됨.

\- **push** **명령어** : local repository 에서 remote repository로 코드 변경분을 업로드 하기 위해 사용.

\- **git pull****과 fetch****의 차이점 :**

둘 다 local git에게 remote repository에서 최신 메타데이터 정보를 확인하라는 명령을 전달하는데,

fetch는 remote repository에 변경사항이 있는지 확인만 할 뿐, 변경된 데이터를 local git에 실제로 가져오지 않는다.

pull은 remote repository에서 변경된 메타데이터 정보를 확인하고 최신 데이터를 복사하여 local git에 실제로 가져온다.