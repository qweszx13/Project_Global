# 간단한 소켓기반 게시글 프로젝트
### 💻JAVA 기반 Socket을 이용하여 게시글 작성,수정,삭제 시스템 종료 기능을 구현하였습니다.

👨‍👨‍👦Team Project로 참여인원은
### KIM Esther
### KIM HyungHO
### KIM DongGyu
으로 구성되어있습니다.

## ⚠️남은 문제

문제가 발생됬던부분

+ github연동과정중에 IDE Tool 설정부분이 맞지않는부분(Eclipse 모듈관련)이 발생하여 Eclipse로 형상관리가 불가능하다고 판단하여 Intellj IDE Tool로 환경설정을 맞춰 코드를 작성하게되었다. 이부분은 Eclipse 관련 지식이 모자라다고 생각되어 추후 조금더 정보를 모아보려고 한다.

+ Socket 에서 연결이 끊김 이후의 상황에대한 부분이 어려웠던것같다. 지금도 해결되지못하는부분은 Client Socket이 강제적으로 끊기게되면 서버쪽의 Stream,Socket 이 Client의    Stream,Socket부분을  찾고 연결시키려고 하는부분은 고치지못했다 정상적으로 Client Socket,Stream을 Close 시킨다면 해당문제는 발생하지않지만 이부분에 관해서도 조금더 찾아봐야할것같다.

+ git 을 사용하면서 branch를 나누지않았던 부분이 아쉬웠다. 처음에는 패키지단위로 나눠서 제작하기때문에 굳이 branch 를 만들지않아도 된다고 판단하였으나 branch를 이용했다면 서로의 기능을 merge할수있는 부분도 있었기에 아쉽다고 생각했다. 다음부터는 branch를 나누고 merge시킬수있도록 해야겠다.

+ Socket 통신시 한글 깨짐현상, 이부분은 Encoding 문제로 Client Receiver에서 정의해줘야하는 부분이 있다는 부분은 알아냈지만 어떤형시으로 정의해야할지를 못찾아 아직수정하지못했다


### KIM Esther - 🗣팀 프로젝트는 너무너무 오랜만이어서 좀 낯설었지만 쿠마상이 잘 이끌어주셔서 처음으로 GitHub도 해보고 GitHub를 통해서 팀원들과 코드 공유하면서 서로 정보도 공유하고 개선점이라던지 이렇게 한거 좋은 것 같다던지 이렇게 피드백하는 점이 좋았다. 조금 더 시간이 있었으면 더 잘할 수 있었을 것 같다는 아쉬움이 남지만  짧은 시간동안 많은걸 보고 느끼고 배울 수 있는 시간이 되었다.
### KIM HyungHo - 🗣수업에서 배운 내용들을 종합해서 코드를 작성하는 것에 대해 복잡하고 어렵다는 생각이 많이 들어 시작하기가 힘들었지만 쿠마상의 조언과 도움으로 코드를 완성해가면서 즐거움을 느꼈다. 처음으로 Github도 사용해 보면서 신기하기도 했고 팀원 끼리 코드리뷰를 하면서 서로의 부족한 점과 보완할 점을 공유한것도 많은 도움이 되었다고 생각한다.
### KIM DongGyu - 🗣코드리뷰를통해 서로 모르는부분에대해서는 다른시각으로 정보를 공유하고,git을 이용한 형상관리부분도 기억에남습니다 1주일만에 만들어진 부분이라 미흡한 부분도 많았지만 조금더 성장할수있는 기회였다고 생각합니다! 



