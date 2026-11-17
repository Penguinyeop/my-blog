# my-blog

한국어 기술 블로그의 공개 콘텐츠 저장소입니다.

- `_posts/`에는 사람이 승인하고 발행 시각이 된 한국어 본문만 추가합니다.
- 미발행 원고, Notion 원본, 영문 번역 대기본, 승인 이력, 금지 목록, 인증정보는 저장하지 않습니다.
- GitHub Actions는 main 변경 시 Jekyll 빌드를 검사합니다.
- 실제 배포는 Settings → Pages → Source를 GitHub Actions로 선택하고, 저장소 변수 `PAGES_ENABLED=true`를 설정한 뒤 실행합니다.
- 예상 URL은 https://penguinyeop.github.io/my-blog/ 이며, 실제 배포 성공 전에는 사용 가능하다고 간주하지 않습니다.
- 예약 시각 전 원고를 이 공개 저장소에 올리면 사이트 표시 여부와 관계없이 공개됩니다.

배포 구성 참고: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages
