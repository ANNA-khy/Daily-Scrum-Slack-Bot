## 2022-03-25
> 오늘은 어떤 일을 했나요?
* workflow(gradle.yml) 실패 => 성공
  * root 폴더 바로 밑에 gradle 파일들이 있는게 아니라 /Server 밑에 있던게 문제였다.
  * build-root-direct: Server를 추가했다(gradle-build-action이 실행되는 디렉토리가 root가 아니라 root 밑의 Server 디렉토리) -> gradlew가 실행할 수 없음
  * Server/gradlew 을 실행할 수 있도록 명령어 추가 => 성공!
> 내일은 어떤 일을 할 건가요?
* Slack shortcut 생성?
> 현재 겪고 있는 장애, 어려움은 무엇인가요?
* workflow 실패했는데 해결했다.
* slack bot을 처음 만들어보는 것이라 내가 계획한 대로 될지 모르겠다.

