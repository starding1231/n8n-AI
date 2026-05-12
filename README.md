# 리코멘드 Landing Page

이 프로젝트는 Vite + React 기반의 랜딩 페이지입니다.

## GitHub Pages 배포 방법

이 프로젝트에는 GitHub Actions를 통한 자동 배포 설정이 포함되어 있습니다.

1. 이 리포지토리를 GitHub에 업로드합니다.
2. GitHub 리포지토리의 **Settings > Pages** 메뉴로 이동합니다.
3. **Build and deployment > Source** 항목에서 `GitHub Actions`를 선택합니다.
4. 이제 `main` 브랜치에 푸시할 때마다 자동으로 빌드되고 배포됩니다.

## 수동 빌드 방법

```bash
npm install
npm run build
```

빌드된 파일은 `dist` 폴더에 생성됩니다.
