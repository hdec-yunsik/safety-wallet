# 정기점검 안전지갑

건설현장 모바일 정기점검용 단일 HTML 웹페이지입니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다. 권장 이름: `safety-wallet`
2. 이 ZIP을 풀고 모든 파일을 저장소 최상위에 업로드합니다.
3. 저장소의 `Settings` > `Pages`로 이동합니다.
4. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
5. Branch는 `main`, Folder는 `/(root)`를 선택하고 Save를 누릅니다.
6. 잠시 후 Pages 주소가 표시됩니다.

일반적인 주소 형식은 `https://깃허브아이디.github.io/safety-wallet/`입니다.

## 중요 보안 안내

GitHub Pages에 게시된 화면은 인터넷에 공개됩니다. 개인·현장·점검 데이터와 비밀키를 저장소에 올리지 마세요. 현재 웹의 실제 점검 기록과 사진은 각 브라우저의 localStorage에만 저장되므로 기기 간 공유되지 않습니다. OneDrive 자동 저장은 Microsoft Graph와 안전한 백엔드 API를 별도로 구성한 후 연결해야 합니다.

## 초기 관리자 비밀번호

`1234`

운영 전 변경이 필요합니다. 단, 정적 HTML에 넣은 4자리 비밀번호는 소스에서 확인할 수 있으므로 강한 보안 수단이 아닙니다.
