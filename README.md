# Git-Hooks
Git Hooks 활용 예제를 모아놓는 레포지토리입니다.

## ktlint-spring
kotlin + spring에서 ktlint를 사용해 pre-push를 테스트한 작업입니다.

### Pre-push
`git push` 직전 `git hook`에 의해 동작하는 스크립트를 정의한 파일입니다.

**어떻게 동작하는가?**
1. `git hook`은 `.git/hooks/pre-push`에 의해 실행됩니다.
2. `.git/hooks/pre-push`파일은 푸시가 불가능해, `.githooks/pre-push` 파일을 생성해 심볼릭 링크로 관리합니다.
