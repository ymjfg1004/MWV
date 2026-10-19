# MWV — Mobile Wireframe & Color Concept Previewer

모바일 와이어프레임을 블럭으로 구성하고, **Primary / Secondary 두 컬러**를 입혀 서비스의 **컨셉 컬러**를 즉시 확인하는 웹 도구입니다.

## 주요 기능
- **블럭 에디터**: 제목·텍스트·버튼·이미지·박스·아바타·뱃지·구분선을 클릭 또는 드래그앤드롭으로 배치
- **자유 배치 / 리사이즈**: 블럭을 옆·아래로 자유롭게 놓고, 핸들로 크기 조절. 넘치면 가로·세로 스크롤
- **템플릿**: 대시보드·피드·상세·갤러리·로그인 — 선택하면 편집 가능한 블럭으로 로드
- **컬러 시스템**: Primary / Secondary (HEX · 컬러피커), **ON/OFF** 토글(끄면 그레이 와이어프레임)
- **캔버스 설정**: 배경색 지정, 상단바 **iOS / Android** 전환
- **저장**: 현재 디자인을 이름과 함께 리스트로 저장(localStorage)·불러오기·삭제

## 기술 스택
- 순수 **HTML / CSS / JavaScript** (프레임워크·빌드 없음)
- 상태 저장: 브라우저 **localStorage**
- 정적 단일 페이지 → **Vercel** 정적 호스팅

## 로컬 실행
`index.html`을 브라우저로 열면 바로 동작합니다. (별도 서버 불필요)

## 배포 (Vercel)
```bash
npm i -g vercel
cd MWV
vercel --prod
```
또는 이 저장소를 Vercel 대시보드에서 **Import** → 프레임워크 "Other" → 그대로 Deploy.
