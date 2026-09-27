# 부산광역시피클볼협회장배 접수 사이트

구성
- 1~5부
- 남자복식 / 여자복식 / 혼합복식
- 각 부문 16팀 자동 마감
- 같은 급수·같은 종목의 선수 중복 접수 차단
- 남/여복 + 혼복 교차 출전 허용
- 휴대전화 기반 중복 검사

## Netlify 배포
1. 이 프로젝트를 GitHub 저장소에 올립니다.
2. Netlify에서 Add new project → Import an existing project로 저장소를 연결합니다.
3. 배포합니다. package.json의 @netlify/database 의존성으로 Database가 프로비저닝되고 migration이 적용됩니다.
4. 배포 후 생성되는 `프로젝트명.netlify.app` 주소가 참가 신청 링크입니다.

※ Netlify Database는 현재 Credit-based plan에서 제공됩니다. 실제 대회 전 테스트 접수를 반드시 해 보세요.
