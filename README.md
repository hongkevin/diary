개발일기(Development Diary)
=====
** 12월 12일(월요일) **

1. Jira Cloud 검토

- EC2에 직접 JIRA software 를 설치해서 사용하던 것을 Cloud 로 이전(검토)
- 1) Storage 지원용량(현재 S3 사용중)
- 2) DB 접근 가능여부(jira-report 고려)
- 3) 속도 이슈
- 4) 플러그인

- 1) 500명 이하까지는 25GB - https://confluence.atlassian.com/cloud/atlassian-cloud-storage-policy-744721619.html
- 2) DB 접근 불가능, API 로 진행가능 - https://answers.atlassian.com/questions/19146189/access-to-the-database-from-jira-on-the-cloud
- * JIRA API 링크: https://docs.atlassian.com/jira/REST/cloud/
- 3) 속도는 많이 개선된 형태 - 2016년 기준(From 서영님)
- 4) 플러그인은 BigPicture 가 클라우드를 지원하지 않음

2. 젠킨스 검토

- http://www.flask.moe/jenkins/github
- Jenkins w/ Github OR Bitbucket
- 브랜치 전략과 풀리퀘스트 전략, 그리고 테스트 코드 작성 및 테스트 커버리지 이슈 검토 필요

3. 코드리뷰

- 석준님 C# 코드 중심으로

