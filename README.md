![Group 1000003995](https://github.com/lotteon2/BITBOX/assets/81145399/72275a38-842c-454c-acef-6b1b123b2ab5)

# BITBOX
📌 롯데 e커머스 교육생들을 위한 커뮤니티 & 학생관리 시스템

자세한 내용은 아래 링크 참조

[[BITBOX 473fc7d91622402f82e71ff23881f84f.pdf](https://github.com/lotteon2/BITBOX/files/13246376/BITBOX.473fc7d91622402f82e71ff23881f84f.pdf)](https://shy-scribe-79f.notion.site/BITBOX-473fc7d91622402f82e71ff23881f84f?pvs=4)

## 목차

1. [기획의도](#1-기획의도)
2. [기술스택](#2-기술스택)
3. [시스템 아키텍쳐](#3-시스템-아키텍쳐)
4. [기능 설명](#4-기능-설명)
5. [기술적 고민](#5-기술적-고민)
6. [회고](#6-회고)

## 1. 기획의도
팀원 모두 준비생 단계에서 롯데e커머스 교육 관련 정보 부족으로 어려움을 겪었습니다. 교육생이 되고 나서도 선배들과의 소통이 부족하다 느꼈고 또한 학생 입장에서 출결과 성적을 확인할 수 없는 것에 불편함을 느꼈습니다. 따라서 위의 문제들을 해결하기 위해 커뮤니티 서비스 및 학생관리 서비스를 기획하게 되었습니다.
<br />

## 2. 기술스택
- Language : 'Java', 'TypeScript'
- Front-End: 'React' 'Tailwind' 'Recoil' 'Zustand' 'ReactQuery' 'Antd' 'React-Quill'
- Bach-End: 'SpringBoot' 'SpringBatch' 'SpringCloud' 'Gradle' 'ApacheKafka' 'Oauth2'
- Database : 'Mysql' 'DynamoDB' 'Redis'
- Infra: 'AWSEC2' 'AWSS3' 'Jenkins' 'Docker' 'Zipkin' 'Prometheus' 'Grafana'
- 프로젝트 관리: 'Github' 'Notion'
<br />

## 3. 시스템 아키텍쳐

<br /> 

![image](https://github.com/lotteon2/BITBOX/assets/81145399/4185886d-c41c-4ff9-b0b2-66f06f198a57)

<br />

## 4. 기능 설명

<b>1. 알럼나이 - 교육생, 수료생</b>
    <br />- 전체 / 기수별 게시판

<b>2. 데브로그 - 취준생(Read), 교육생, 수료생</b>
    <br />- 수료생 및 교육생 진행 프로젝트 홍보

<b>3. 선배들의 이야기 - 취준생(Read), 교육생, 수료생</b>
    <br />- 면접 후기 / 관련 정보 공유

<b>4. 커뮤니티 - 취준생, 교육생, 수료생</b>
    <br />- 질의응답
    <br />- 정보 공유

<b>5. 출결 관리 - 교육생</b>
    <br />- 위치 기반
    <br />- 입실 / 퇴실
    <br />- 출결 정보 확인

<b>6. 사유서 관리 - 교육생</b>
    <br />- 사유서 작성

<b>7. 관리자</b>
  5-1. 전체 관리자
          <br />- 매니저 CRUD
          <br />- 교육생 관리 (CRUD)
          <br />- 출결 관리(RU)
          <br />- 사유서 관리 (RU)
          <br />- 성적 관리 (CRUD)
          <br />- 시험 관리 (CRUD)
  5-2. 매니저
          <br />- 교육생 관리 (CRUD)
          <br />- 출결 관리(RU)
          <br />- 사유서 관리 (RU)
          <br />- 성적 관리 (CRUD)
          <br />- 시험 관리 (CRUD)
  5-3. 강사
          <br />- 출결 관리(RU)
          <br />- 성적 관리 (CRUD)

<b>8. 채팅 - 취준생(답변 확인 시 유료), 교육생, 수료생</b>
          <br />- 정기 결제(특정 기간 내 무제한 사용)
          <br />- 단건 결제(특정 횟수 사용)

<b>9. 알림</b>
          <br />- 내 게시글 댓글
          <br />- 출석 체크
          <br />- 구독권 만료
<br />
## 5. 회고
❤️ 김명준
서비스가 나뉘면서 생기는 문제들을 카프카, 레디스 등을 활용해서 고민하고 해결해볼 수 있어서 좋았다. 시간 여유가 없어 캐싱을 못한 것이 아쉬웠다. 롯데 e커머스에서 DynamoDB가 중요스택에 있어 활용해보고 싶었지만, 제대로 사용해보지 못한 점도 아쉬웠다. 다음 프로젝트에서 조금 더 고민해봐야 할 것 같다. 각자 주로 맡은 역할 잘 해줘서 좋았고, 부족한 부분은 도움줘서 고마웠어! 최종 프로젝트 힘내고 입사하고 나서도 잘 지내자!😁

💜 김정윤
다들 진짜 너무 고생 많았다.. MSA 구조를 때문인지 기획 단계에서 많이 버벅이고 또 구현할때도 힘들긴 했는데 다행히 잘 마무리 지어서 좋았다😺 다음 프로젝트에서는 좀 더 잘할 수 있길 빌면서🙏  다음 프로젝트도 다들 화이팅!!!

💛 마혜경
MSA를 처음 해봐서 그런가 도메인을 잘 못 쪼개 초기에는 어려움도 많았지만 커넥트로 정합성을 맞추고 반정규화하는등 다양한 시도를 해볼 수 있어서 좋았어! 이번 프로젝트를 계기로 다음에는 설계를 좀 더 탄탄히 해야겠다는 생각이 들었어! 다들 정말 고생 많았어! 최종에서도 화이팅하자!🙌

💚 전종민
개발하다가 기획, 설계 단계에서 놓쳤던 부분들이 나와서 구조나 흐름이 어색한 부분들이 생겨 아쉬운 점이 있었지만 담당자들 간에 소통하며 해결했다. HTTP에 대한 공부를 해야겠다는 생각이 들었다. 게이트웨이 route 설정은 yml로 하지 않는 것이 좋겠다는 생각이 들었다. MSA의 단점, MSA에서 발생할 수 있는 문제점들을 겪어본 것 같아 다음 프로젝트에서는 좀 더 설계를 잘 할 수 있지 않을까라는 생각이 들었다. 특히 프론트 친구들 고생 많았습니다~!~!

💙 최성훈
모놀리식만 경험하다가 이걸 강제로 도메인으로 쪼개다보니 여러가지 문제가 있었고 그런 문제를 해결하면서 많은 성장을 할 수 있었던 것 같습니다.


### 👨‍👩‍👦‍👦  팀원소개
|  김명준  |  김정윤  |  마혜경  |  전종민 | 최성훈  |
| :----------: |  :--------:  |  :---------: |  :---------: | :---------: |
| [<img src="https://avatars.githubusercontent.com/u/100829030?v=4" width="100px" height="100px"><br/>Github](https://github.com/MJun111)| [<img src="https://avatars.githubusercontent.com/u/81145399?v=4" width="100px" height="100px"><br/>Github](https://github.com/indl1670) | [<img src="https://avatars.githubusercontent.com/u/72402747?v=4" width="100px" height="100px"><br/>Github](https://github.com/Hyevvy) | [<img src="https://avatars.githubusercontent.com/u/38072189?s=64&v=4" width="100px" height="100px"><br/>Github](https://github.com/wakkpu)| [<img src="https://avatars.githubusercontent.com/u/33412452?v=4" width="100px" height="100px"><br/>Github](https://github.com/realsuperman) |
| 인프라 / 커뮤니티 | UX,UI / 프론트 / 회원 관리 | 프론트 / 관리자 | 인증&인가 / 알림 | 채팅 / 결제 |
