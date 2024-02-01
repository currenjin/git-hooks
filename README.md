# Git-Hooks
Git Hooks 활용 예제를 모아놓는 레포지토리입니다.

## ktlint-spring
`kotlin + spring`에서 `ktlint`를 사용해 `pre-push`를 테스트한 작업입니다.

### Pre-push
`git push` 직전 `git hook`에 의해 동작하는 스크립트를 정의한 파일입니다.

**어떻게 동작하는가?**
- Git Hook은 `.git/hooks` 디렉토리의 스크립트 파일에 의해 실행됩니다.
- 하지만, 레포지토리에 푸시할 수 없어 개발자 모두가 공유하기엔 어려움이 있습니다.
- 때문에, 코드 컴파일 시 Git Hook 경로를 `.git/hooks`에서 `.githooks`로 변경합니다.
- 상세 스타일은 `.editorconfig`에서 정의합니다.
