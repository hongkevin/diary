개발일기(Development Diary)
=====

** 12월27일(화요일) **

1. ejs vs. mustache

2. C# - disabled, extensions

** 12월26일(월요일) **

1. AWS deploy from C#(AWS toolkit), lambda(gulp)

** 12월24일(토요일) **

1. 9XD 개발자 모임 

** 12월21일(수요일) **

1. C# - linq join(left outer join), class 생성 

2. jQuery - Documentation 참고

** 12월20일(화요일) **

1. EC5 - forEach, map, reduce, filter, every, some

2. C# - app.config, Zigbang.edmx => DB스키마 변경

3. html, css, js, jQuery - form 통합, 변수통일

** 12월19일(월요일) **

1. C#, ASP.net - https://teamtreehouse.com/library/c-basics/perform/repl

2. 블로그 새 글(DB - 테이블 생성) - https://medium.com/@hongkevin/db-1-mysql-%ED%85%8C%EC%9D%B4%EB%B8%94-%EC%83%9D%EC%84%B1-%EC%8B%9C-%EA%B3%A0%EB%A0%A4%ED%95%A0-%EA%B2%83%EB%93%A4-cdf376d396fc#.pi29yivvt


** 12월17일(토요일) **

1. 중급개발자되기 - https://www.youtube.com/watch?v=_X-Betqyyxw

2. NginX 설정 - https://brunch.co.kr/@cheese10yun/3


** 12월17일(토요일) **

1. D3.js - https://github.com/d3/d3/wiki

2. 블로그 - 꾸준하게 심도있게 작성하기 - https://medium.com/@hongkevin

** 12월16일(금요일) **

1. 자바스크립트 완벽가이드
- forEach: 세 가지 인자를 넘기면서 호출(배열의 원소값, 원소의 인덱스값, 배열)
- map: 배열 원소 하나씩 넘기면서 호출

2. 어드민
- DB 컬럼 추가 필요 -> creator(등록자), updator(수정자), Nullable("-"로 일괄표기)
- 수정은 제목, 링크, 이미지URL
- 이미지 업로드 참고

3. 기사관리 관련 API
- lambda 프로젝트 -> api/content/notices 참고

** 12월 14일(수요일) **

1. AWS Elastic Beanstalk
- 이미 생성된 EC2 와는 연결을 할 수 없다.
- EB 를 생성하면서 연결되는 EC2, RDS 등의 정보를 바꿀 수 있다.

2. 젠킨스 검토
- webhook 개념을 적용 - https://www.linkedin.com/pulse/how-build-automated-continuous-deployment-pipeline-jenkins-demiris

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

