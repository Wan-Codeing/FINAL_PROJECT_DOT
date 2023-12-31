# SEMI-PROJECT-FUNDABLE
JSP + SPRINGBOOT 기반의 SNS 사이트

## 🖥️ 프로젝트 소개
인스타그램을를 메인으로 여러 SNS사이트를 참고하여 만든 사이트입니다.
<br>

## 🕰️ 개발 기간
* 23.8.23일 - 23.09.21일

### 🧑‍🤝‍🧑 맴버구성
 - 팀장  : 이정완 - 로그인, 회원가입페이지, 내정보 페이지, 친구정보 페이지, 실시간 알림기능, 실시간 로그인체크 기능, 비밀번호암호과, 이메일인증, 휴대폰인증, 피드 신고하기, 검색기능 일부, 비밀번호변경, 회원탈퇴
 - 팀원1 : 오창정 - 채팅페이지, 피드 공유하기, 첫(메인페이지)start, 사이드바,헤더 UI, 메인피드 UI, 메인피드 상세보기 UI
 - 팀원2 : 이준호 - 팔로우/팔로워 페이지, 메인피드 좋아요 저장하기 댓글 기능, 친구추천기능
 - 팀원3 : 김소연 - 검색기능 일부, 검색창 UI, 관리자페이지
 

### ⚙️ 개발 환경
- `Java 11`
- `JDK 11.0.19`
- **IDE** : sts-3.9.14.RELEAS
- **Database** : Oracle DB(11g XE)

## 📌 주요 기능
#### 첫페이지&로그인&회원가입 - <a href="https://github.com/Wan-Codeing/FINAL_PROJECT_DOT/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5%EC%86%8C%EA%B0%9C(%EC%B2%AB%ED%8E%98%EC%9D%B4%EC%A7%80&%EB%A1%9C%EA%B7%B8%EC%9D%B8&%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85)" >상세보기 - WIKI 이동</a>
- 팀원들 소개
- 휴대폰 인증
- 비밀번호 찾기 기능(이메일 인증)
- 로그인 유무 실시간 체크 기능(웹소켓)

#### 마이 페이지&친구 페이지 - <a href="https://github.com/Wan-Codeing/FINAL_PROJECT_DOT/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5%EC%84%A4%EB%AA%85(%EB%A7%88%EC%9D%B4%ED%8E%98%EC%9D%B4%EC%A7%80&%EC%B9%9C%EA%B5%AC%ED%8E%98%EC%9D%B4%EC%A7%80)" >상세보기 - WIKI 이동</a>
- 나의 게시물 관리
- 내 프로필 수정
- 내 찜목록 관리
- 친구 게시물 목록 확인 및 친구 프로필 확인
- 회원 비밀번호 변경 / 회원 탈퇴 기능

#### 메인페이지&팔로워&검색 - <a href="https://github.com/Wan-Codeing/FINAL_PROJECT_DOT/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5%EC%84%A4%EB%AA%85(%EB%A9%94%EC%9D%B8%ED%8E%98%EC%9D%B4%EC%A7%80-%EA%B2%80%EC%83%89-%EC%B9%9C%EA%B5%AC)" >상세보기 - WIKI 이동</a>
- 나와 친구인 유저의 게시물 확인
- 좋아요 및 댓글 및 찜목록 및 신고 기능
- 상세보기 기능
- 나의 팔로우/팔로워  체크 및 팔로잉/언팔로잉 기능
- 팔로우시 실시간 알림기능(웹소켓)
- 해시태그 or 작성자로 검색 가능하게 함
- 검색된 목록들 상세보기 기능
- 헤더에서도 해시태그로 검색가능

#### 채팅 - <a href="https://github.com/Wan-Codeing/FINAL_PROJECT_DOT/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5%EC%84%A4%EB%AA%85(%EC%B1%84%ED%8C%85)" >상세보기 - WIKI이동</a>
- 특정유저 선택(여러명가능) 방을 생성
- 생성된방에서 실시간 채팅 기능(파잋럼부 가능)
- 게시물 공유시 방자동 생성및 생성된 방에도 공유가능
- 채팅 및 공유시 실시간 알림기능(웹소켓)

#### 관리자페이지 - <a href="https://github.com/Wan-Codeing/FINAL_PROJECT_DOT/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5%EC%84%A4%EB%AA%85(%EA%B4%80%EB%A6%AC%EC%9E%90%ED%8E%98%EC%9D%B4%EC%A7%80)" >상세보기 - WIKI이동</a>
- 유저 및 게시물 및 신고 관리
- 신고 및 각유저의 폴루워수를 통해 인플루언서 및 블랙리스트 변경기능

