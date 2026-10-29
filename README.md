# 이동원 지원 자료 · GitHub Pages 배포 폴더

## 주소와 역할
- `/` → `index.html`: AI·AX 구현 포트폴리오. 문제·설계·화면·데이터 흐름·검증 근거.
- `/career/` → `career/index.html`: 회사별 경력·책임·성과 및 최근 주요 수행 내역.
- `/info/` → `info/index.html`: 기존 경력 소개 전체를 보존한 Info 페이지. 소개·경력요약·경력·프로젝트·기술·학력을 제공합니다.
- `/downloads/lee-dongwon-resume.pdf`: 핵심 역량·대표 성과·경력·학력을 요약한 4페이지 이력서.
- `assets/`: 프로젝트 이미지와 공통 Pretendard 웹폰트·라이선스.
- `diagrams/`: 흐름도 SVG와 편집용 Mermaid 원본.

## 배포
이 폴더 안의 내용을 `wodbow12.github.io` 저장소의 GitHub Pages 배포 루트에 복사하세요. 기존 메인 대신 포트폴리오가 열립니다. 폴더 구조를 유지하고 `.nojekyll`도 함께 포함하세요. 별도 빌드나 패키지 설치는 필요하지 않습니다.
경력기술서는 같은 탭의 `career/`로 연결되고, 이력서 버튼은 PDF 다운로드로 연결됩니다. 공개 저장소에 올리면 이력서에 기재된 연락처도 공개됩니다.

## 문서 편집
HTML은 각 페이지를 편집하면 됩니다. 이력서는 `downloads/resume.html`과 `downloads/resume.css`를 편집하고 PDF를 다시 저장합니다. `resume-content.md`는 이전 요약본이며, 자세한 방법은 `downloads/README.md`를 참고하세요.

## 기존 경력 소개 보존
`info/index.html`은 `07ad404560a8644b2aabe41b959aed94072578b4` 커밋의 `career/index.html`에서 복원했습니다. 기존 소개 3문단과 경력·프로젝트·기술·학력 본문은 유지하고, 페이지 제목과 공통 메뉴만 현재 주소 구성에 맞게 변경했습니다. 현재 `/career/`의 최신 경력기술서는 그대로 유지합니다.
