# 테마점검 APP rev.1

## GitHub Pages 배포
1. GitHub `safety-wallet` 저장소에서 **Add file > Upload files**를 선택합니다.
2. 이 패키지의 `index.html`, `.nojekyll`, `README.md`, `SECURITY.md`를 업로드합니다.
3. Commit message에 `rev.1 UI 및 체크리스트 반영`을 입력하고 **Commit changes**를 누릅니다.
4. Settings > Pages에서 Source를 `Deploy from a branch`, Branch를 `main`, Folder를 `/(root)`로 설정합니다.
5. 기존 저장소라면 index.html 교체 커밋만으로 자동 재배포됩니다.

## 테스트 주소
`https://hdec-yunsik.github.io/safety-wallet/`

## 저장 방식의 한계
현재 rev.1은 브라우저 localStorage에 저장합니다. GitHub Pages는 정적 호스팅이므로 서로 다른 휴대폰의 기록이 통합되지 않습니다. 실제 운영 전 OneDrive/SharePoint/API 백엔드가 필요합니다.
