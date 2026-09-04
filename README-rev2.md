# 정기점검 안전지갑 rev.2

## 1. Supabase Edge Function
`supabase-admin-api-index.ts` 전체를 Supabase Dashboard의 `admin-api/index.ts`에 붙여넣고 Deploy 합니다. Verify JWT는 OFF를 유지합니다.

## 2. GitHub Pages
`index.html`을 기존 `safety-wallet` 저장소 루트에 업로드해 기존 파일을 교체합니다.

권장 커밋: `feat: rev.2 Supabase 중앙 저장 연동`

## 3. 테스트
점검 등록 전에 점검자, 협력사, 테마가 서버에서 표시되는지 확인합니다. 관리자 메뉴는 Supabase Secret에 저장한 공통 비밀번호를 사용합니다.
