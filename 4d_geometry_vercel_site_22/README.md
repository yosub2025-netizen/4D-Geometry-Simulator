# 4차원 기하학 교수 학습 시뮬레이터 모음

이 폴더는 Vercel에 바로 배포할 수 있는 정적 웹사이트입니다.

## 구성
- `index.html`: 메인 카드형 링크 페이지
- `simulators/`: 업로드한 HTML 시뮬레이터 22개

## Vercel 배포 방법
1. 이 폴더 전체를 GitHub 저장소에 업로드합니다.
2. Vercel에서 `New Project`를 누릅니다.
3. 해당 GitHub 저장소를 선택합니다.
4. Framework Preset은 `Other` 또는 기본값으로 두고 Deploy를 누릅니다.
5. 배포 후 `https://프로젝트명.vercel.app` 주소가 생성됩니다.

## 주의
일부 시뮬레이터는 Tailwind, Three.js, MathJax 등 외부 CDN을 사용하므로 인터넷 연결이 필요할 수 있습니다.
