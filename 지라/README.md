## JIRA

#### JIRA 사용이유

- 팀원 모두가 알고 있는 하나의 공유된 지표 필요
- 장애나 이슈가 있을 때 팀원들과 실시간 공유 필요



#### 이슈 타입

- Story : 사용자의 요구 사항이나 개발의 대상 
- Task : Story의 하위 작업으로 Story를 위해 실제로 작업해야 하는 일
- Bug : 개발과정 중 보고된 버그
- Epic : 이슈 들의 큰 틀



#### 이슈 작업 절차

1. PM이 요구 사항을 취합하여 User Story 작성
2. User Story를 구현하기 위해 Task를 User Story 아래 작성한다.
3. 생성된 Task를 개발자에게 Assign한다.
4. 개발자가 Task를 In Progress로 바꾼다.
5. 개발자가 진행 내용이나 의사 소통이 필요한 정보를 Comment로 적는다.
6. 개발 도중 발생한 Bug를 작성한다.
7. 개발자가 개발을 완료하면 상태를 Resolve Issue(해결된 상태)로 상태를 바꾸고 PM에게 다시 이슈를 Assign한다.
8. PM이 Resolved된 이슈들이 제대로 반영되었는지 확인한 후 Close(완전종료)상태로 변경한다.



### JQL

- JIRA QUERY LANGUAGE

- Jira Issue를 검색하기 위해 제공하는 언어로 SQL과 비슷한 문법을 가진다.

  ```
  status = "In Progress" and "Start date[Date]"<-10d
  ```

  



