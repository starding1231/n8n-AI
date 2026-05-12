# 리코멘드 Landing Page

이 프로젝트는 Vite + React 기반의 랜딩 페이지입니다.

## GitHub Pages 배포 방법

이 프로젝트는 `gh-pages` 패키지를 사용하여 편리하게 배포할 수 있습니다.
배포 주소는 `https://starding1231.github.io/-n8n-AI-/`로 설정되어 있습니다.

1. 먼저 GitHub 리포지토리에 코드를 푸시합니다.
2. 터미널에서 다음 명령어를 실행합니다:
   ```bash
   npm run deploy
   ```
3. GitHub 리포지토리의 **Settings > Pages** 메뉴로 이동합니다.
4. **Build and deployment > Source** 항목에서 `Deploy from a branch`를 선택하고, 브랜치를 `gh-pages`로 설정합니다.

### 주의사항
- `vite.config.ts`의 `base` 설정이 `/-n8n-AI-/`로 되어 있어야 정상적으로 작동합니다.
- Node.js 버전은 로컬 환경에 맞춰 사용하시면 됩니다. (18 버전 이상 권장)


## 수동 빌드 방법

```bash
npm install
npm run build
```

빌드된 파일은 `dist` 폴더에 생성됩니다.
