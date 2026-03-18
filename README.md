# 빅피시 결산 대시보드

자동 분류 결산 시스템 (150개 규칙 + 3,840개 학습 패턴)

## Vercel 배포 방법

### 1단계: GitHub에 올리기
1. https://github.com 에서 회원가입 (무료)
2. 우측 상단 "+" → "New repository" 클릭
3. Repository name: `bigfish-dashboard` 입력
4. "Create repository" 클릭
5. 다운로드 받은 이 폴더를 업로드 (또는 git push)

### 2단계: Vercel에 배포
1. https://vercel.com 접속 → "Sign Up" → GitHub 계정으로 로그인
2. "Add New Project" 클릭
3. GitHub에서 `bigfish-dashboard` 선택
4. "Deploy" 클릭 — 끝!

배포 완료되면 `https://bigfish-dashboard.vercel.app` 같은 주소가 생깁니다.

## 사용법
1. 매달 기업은행에서 거래내역 CSV 다운로드
2. 데이터입력 탭에서 업로드 또는 붙여넣기
3. 미분류 건이 있으면 드롭다운에서 분류 선택
4. 대시보드에서 결산 확인

## 데이터 저장
입력한 데이터는 브라우저(localStorage)에 자동 저장됩니다.
같은 컴퓨터, 같은 브라우저에서 접속하면 이전 데이터가 유지됩니다.
