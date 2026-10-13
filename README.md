# sing-practice — 노래일기(소리일기)

노래 연습 일기 안드로이드 앱. 앱 소스와 설명은 [`songdiary/`](songdiary/README.md)에 있어요.

- 앱 화면: `songdiary/www/` · 안드로이드(Capacitor): `songdiary/native/` · 도구: `songdiary/tools/` · 테스트: `songdiary/tests/`
- 빌드·배포: `.github/workflows/songdiary-apk.yml` — 앱이 바뀐 푸시마다 앱 안 업데이트(`songdiary-ota` 브랜치)와
  구글 드라이브 APK를 만들어요. 저장소 Settings → Secrets → Actions에 `SONGDIARY_DRIVE_URL`, `SONGDIARY_DRIVE_KEY`가 있어야 해요.

2026-10-13에 `ggumtak/myroutine`(스킨케어 루틴 앱)에서 커밋 기록째 옮겨 왔어요.
