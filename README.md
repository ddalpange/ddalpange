# 👨🏻‍💻 Yohan Kim

- 연락처: ddalpange@gmail.com 
- 병역상태: 면제

오직 일에만 집중할 수 있는 회사를 찾고 있습니다.

스프린트 기간을 최대한 짧게 하는 것을 좋아하며 데이터 기반으로 일을 하려 노력합니다.  
회복 탄력성이 강하고 가설 검증 기반의 디버깅 능력이 우수합니다.  
이상한 일들을 많이 해서 버그를 많이 만나 몽키 패칭을 잘합니다.  
배포를 자주 하는 문화를 만들기 위해 노력합니다.

## 📌 Work Experience

### 당근마켓 (2023.04 ~ 현재)

**소프트웨어 엔지니어**

###  [뤼이드](https://www.riiid.co/ko/main) (2020.11 ~ 2022.11)

**소프트웨어 엔지니어**
- Schema based development
  - Protobuf 기반으로 webview와 native, server 인터페이스 작성
  - 작성된 schema를 통해 반복적인 코드를 기계적으로 자동 생성
  - Open API Schema를 기반으로 rest api들의 반복적인 코드를 기계적으로 자동 생성
  - 스키마 저장소를 분리하여 PR을 통해 api tech spec 논의
- 컴파일 / 번들링 방식 연구 및 개선
  - css-in-js로 인한 babel 의존성을 제거하고 swc로 컴파일러 교체
  - esm, cjs 두 모듈링을 지원하기 위한 작업 진행
  - 모노레포에서 각 패키지들의 hmr을 지원
- Trunk Based Development 구현하기 위한 일들을 진행
  - yarn2 + ultra-runner를 사용한 초기 모노레포 셋업
  - pnpm + turbo를 통한 모노레포 개선
  - PR 검증과 프로덕트 배포를 위한 CI&CD 작성
  - 빌드 캐싱을 통해 배포 속도 대폭 개선 
  - 모노레포로 인한 각종 빌드 이슈 해결 
  - 배포 프로세스 정의
- 테스트 코드 작성
  - 커버리지 80%를 목표로 유닛테스트 작성
  - E2E 테스트를 위해 Cypress를 셋업하고 QA Engineer 온보딩 진행
  - 스키마를 통해 목 데이터 생성기, msw 코드를 자동으로 생성해 유닛 테스트, 스토리북에 활용
- 사내 백오피스 구현
  - 공용 컴포넌트, 로직, 컨버터 작성 후 라이브러리로 말아서 배포
  - 어드민 데이터그리드, 공통 필터 구현 스펙 논의 
- 기존 코드리뷰 방법을 보완하기 위해 [Graphite](https://graphite.dev)를 사용하여 Stacked Changes 방법을 팀내 전파
- 3개월 정도 미국 지사에서 영어권 엔지니어들과 협업
- 소수 오픈소스 프로젝트 기여 (Pbkit, Storybook 등)
- 다수 웹뷰 프로덕트 MVP 구현 및 유지보수
- CLI 툴링 작성 (코드 마이그레이션, 컴포넌트 코드 생성 등)

### [클래스101](https://class101.net) (2019.03 ~ 2020.06)

**소프트웨어 엔지니어**

- 커머스 셀
  - 퍼널 줄이기 A/B 테스트를 통한 결제 컨버전 400% 개선
  - 쿠폰 및 구성품 선택 UX 개선 
  - 배송 추적 UX 개선
  - 커머스 도메인 레거시 대응
  - 각종 결제, 배송 에러 트러블 슈팅
  
- 프론트엔드 챕터 DRI
  - Class101 CSR 프로젝트를 SSR을 지원하도록 변경
  - SEO 최적화를 위해 메타태그, 사이트맵, 스키마 등을 세팅
  - 서버리스 이미지 압축 서비스에서 다양한 포멧(webp, png, jpg)을 지원하도록 변경 
  - 스크린 크기에 따른 반응형 이미지 최적화로 이미지 리소스 용량을 82% 절감 
  - 50mb ~ 100mb 단위로 JS 청크 스플리팅 적용 
  - 사이트 총 리소스를 25.8mb에서 11.4mb로 55% 절감
  - 브라우저, 자바스크립트 렌더링 최적화로 노트8 기준 TTI를 158초 -> 21초로 절감
  - 인피니티 스크롤 개선 및 관성 스크롤 적용해 스크롤 UX 최적화
  - 센트리, 슬랙을 통한 에러 모니터링 셋업
  - 어드민 공통 필터, 테이블 추상화
  - 알림 서버 개선 (분당 최대 전송 횟수 40개 -> 20,000개)
  - 프론트엔드 개발자 채용 가이드 문서 제작
  - 기술 블로그 개발 및 공유 문화 전파
  - 리액트 모노레포 프로젝트 에러 핸들링 
  - Graphql Apollo 구조 설계 및 트러블 슈팅 

### [노루](http://knowru.com) (2018.03 ~ 2019.03)

**프론트엔드 프로그래머**

- 다양한 차트라이브러리를 활용해 데이터 시각화 작업 (오픈소스 컨트리뷰션)
- 심플한 소스코드 관리자 설계 (Diff, Versioning 등)
- RxJS의 사용하여 스트림 기반의 반응형 프로그래밍에 대해 고민하였음.
- WebRTC를 이용한 양방향 영상 통신 구현
- Gatsby + Bulma 를 통해 회사 소개 사이트 구축

### [트래포트](https://m.travelhow.com) (2016.07 ~ 2017.08)

**프론트엔드 프로그래머**

- 호텔, 액티비티 서비스 아키텍쳐 설계
- 여행 올인원 커머스 개발

## 🎨 Contributions

- Pbkit, Storybook, Toolbelt, Tui Chart, Hexo Minos

## 🚀 Projects

- [클래스101](https://class101.net)
- [클래스101 UI](https://ui.class101.dev/)
- [클래스101 기술 블로그](https://class101.dev/)
- [Knowru](https://www.knowru.com)
- [Oowa](https://oowa.io)
- [Knowru Limited](https://www.knowrulimited.com)
- [AI Interview](https://www.ai-interview.com)
- 트래블하우 [PC](https://www.travelhow.com), [Mobile](https://m.travelhow.com), [Biz](https://biz.travelhow.biz)


## 🔗 Links

| Site       | Link                         |
| ---------- | ---------------------------- |
| **Blog**   | https://ddalpange.github.io  |
| **Email**  | ddalpange@gmail.com          |
| **Github** | https://github.com/ddalpange |
