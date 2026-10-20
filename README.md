# mail-assets

메일 본문·공개 콘텐츠에 쓰는 **정적 이미지 호스트**입니다.

- 공개 주소: `https://labiter777.github.io/mail-assets/a/<sha12>/<파일명>`
- 주소는 **내용 주소(content-addressed)** 입니다. 같은 바이트는 같은 주소, 다른 바이트는 다른 주소.
  → 한 번 발송된 메일의 이미지 주소는 **덮어쓰이지 않습니다.**
- **이 저장소의 `a/` 아래 파일은 지우지 않습니다.** 지우면 이미 보낸 메일의 이미지가 깨집니다.
- TLS 는 GitHub 가 자동 갱신합니다(443, 사람 손 필요 없음).
- 올리는 도구: 마케팅 콘솔 저장소의 `ops/mail_assets_publish.mjs`
- 목록: `manifest.json`
